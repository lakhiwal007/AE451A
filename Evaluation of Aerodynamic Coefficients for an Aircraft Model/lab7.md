<h1 align ="center">Indian Institute of Technology Kanpur</h1>





<h1 align ="center">AE451A</h1>

<h3 align = "center">Experiments in Aerospace Engineering - III</h3>





<h3 align = "center">Experiment No. 7</h3>

<h1 align = "center">Aerodynamic forces and moments on a generic aircraft model</h1>





### Submitted By:

Ankit Lakhiwal (180102)

[ankitl@iitk.ac.in](To:ankitl@iitk.ac.in)

Aerospace Engineering Department, IIT Kanpur

October 4, 2021



## 1. Objective

- Estimation  of  aerodynamic  forces and moments  acting  on  the  generic aircraft  model under  test.

## 2. Inroduction and Theory

> ##### **Principle of operation**

Our aircraftmodelis mounted on the balance accurately. Soit transmitsthe load to the balance  during experiment.  Balance is  attached  to the  mechanism which provides pitching,  yawing  and  rolling moment  to  the aircraft  model.  We  are  using Six component  force balance which is a  cylindrical  body  on  which  an  aerodynamics model  can  be  mounted  to  measure  different  forces  acting  on  it  by  aerodynamic loading. Whetstone  bridge  card  (SCXI-1000)  is a constant  DC  voltage  supply  is required  to  activate  the  bridges.  For  this a  SCXI-1314NI  card  is  used  which facilitates DC voltage supply. Data  acquisition  card  (PXI-1033)  which is the voltage output  of  the  strain  gauges  is  required  to  be  measured  under  the  loading  on  the balance. For this a data acquisition card PXI-1033 with maximum of 16 voltage input channels  is  used. Also Labview  software  facilitated  to  provide/acquire  the input/output voltage signals to/from the strain gauge bridges using a specially built VI program.Usually, non-dimensionalized raw signal (mV/VEx) has been saved during the test and analyzed later.A linear least square fit for the variation of the normalized outputs with respects to a particulars load components is obtained

> ##### **Sign conventions**

In general, right hand rule or Euler's convention is followed for all the axes system. Direction of positive forces and moments in body and wind axes are shown in the figure.

<div style = "columns:2;">
    <ul>
        <u>Axes:</u>
        <li>x- axis	:	positive forward</li>
		<li>y- axis	:	positive to starboard</li>
		<li>z- axis	:	positive downward</li>
    </ul>
	<ul>
        <u>Forces in model axes:</u>
        <li>Axial force		: 	A</li>
		<li>Side force 		: 	Y</li>
		<li>Noraml force	: 	N</li>
    </ul>
	<ul>
        <u>Moments in model axes:</u>
        <li>Rolling moment, l			:	starboard wing down</li>
		<li>Pitching moment, m		:	nose up</li>
		<li>Yawing moment, n		  :	nose toward starboard</li>
    </ul>
    <figure>
    	<img src="C:\Users\lakhi\Documents\AE451A\Evaluation of Aerodynamic Coefficients for an Aircraft Model\signConvention.png" alt="sign convention" style="zoom:60%;" />
    </figure>
</div>

<div style="columns:2;">
	<ul>
    	    <u>Forces in wind axes:</u>
			<li>Drag force, D  : along the wind direction</li>
			<li>Side force, S :  to starboard</li>
        	<li>Lift force, L : Normal to wind direction</li>
    </ul>
    <ul>
    	    <u>Moments in wind axes:</u>
			<li>Rolling moments lw : starboard wing down</li>
			<li>Pitching moments mw : nose up</li>
        	<li>Yawing moments, nw : nose towards starboard</li>
    </ul>
</div>

> ##### **Force and moments equations**

1. <u>Balance axis system</u>

   $$
   \vec{F_i} = C_{ij}\vec{E_j}\\
   \vec{F_i} = \{A_x,N_1,N_2,S_1,S_2,R_m\} \qquad \vec{E_j} = \{E_{A_x},E_{N_1},E_{N_2},E_{S_1},E_{S_2},E_{R_m}\}\\
   A_{x_{bc}} = A_x \qquad \qquad \qquad R_{m_{bc}} = R_{m} \\
   S_{bc} = S_1 + S_2 \qquad \qquad M_{p_{bc}} = (N_1 - N_2)*d \\
   N_{bc} = N_1 + N_2 \qquad \qquad M_{y_{bc}} = (S_1 - S_2)*d
   $$
   
2. <u>Body axis system</u>
   $$
   \vec{F_B} = T_b^B\vec{F_b} \qquad  \vec{M_B} = T_b^B\vec{M_b}\\ \\
   T_b^B = \begin{bmatrix}
   			cos\alpha_bcos\psi_b & cos\alpha_bsin\psi_b & -sin\alpha_b\\
   			(sin\phi_bsin\alpha_bsin\psi_b -cos\phi_bsin\psi_b) & (sin\phi_bsin\alpha_bsin\psi_b + cos\phi_bcos\psi_b) & (sin\phi_bcos\alpha_b)\\
   			(cos\phi_bsin\alpha_bcos\psi_b + sin\phi_bsin\psi_b) & (cos\phi_bsin\alpha_bsin\psi_b - sin\phi_bcos\psi_b) & (cos\phi_bcos\alpha_b)
   		\end{bmatrix} \\\\
   		where \space \alpha_b = 0,\space \psi_b = 0 \space and \space \phi_b = 0\\\\
   		T_b^B = \begin{bmatrix}
   			1 & 0 & 0 \\
   			0 & 1 & 0 \\
   			0 & 0 & 1
   		\end{bmatrix}
   $$
   
3. <u>Wind axis system</u>
   $$
   \vec{F_w} = T_B^w\vec{F_B} \qquad  \vec{M_w} = T_B^w\vec{M_B}\\ \\
   T_B^w = \begin{bmatrix}
   			cos\alpha_wcos\psi_w & cos\alpha_w sin\psi_w & -sin\alpha_w \\
   			(sin\phi_w sin\alpha_w sin\psi_w -cos\phi_w sin\psi_w) & (sin\phi_w sin\alpha_w sin\psi_w + cos\phi_w cos\psi_w) & (sin\phi_w cos\alpha_w)\\
   			(cos\phi_w sin\alpha_w cos\psi_w  + sin\phi_w sin\psi_w) & (cos\phi_w sin\alpha_w sin\psi_w - sin\phi_w cos\psi_w) & (cos\phi_w cos\alpha_w)
   		\end{bmatrix} \\\\
   		where \space \alpha_w \neq 0,\space \psi_w = 0 \space and \space \phi_w = 0\\\\
   		T_B^w = \begin{bmatrix}
   			cos\alpha_w & 0 & -sin\alpha_w \\
   			0 & 1 & 0 \\
   			sin\alpha_w & 0 & cos\alpha_w
   		\end{bmatrix}
   $$
   

Therefore, the relations of forces at balance, body and wind axes with right hand axes convention are as follow
$$
\vec{F_b} = \begin{bmatrix}
    F_{Xb} \\
    F_{Yb} \\
    F_{Zb} \end{bmatrix} =
  \begin{bmatrix}
    Ax_{b} \\
    Y_{b} \\
    N_{b} 
  \end{bmatrix},
  \vec{F_B} = 
  \begin{bmatrix}
    F_{XB} \\
    F_{YB} \\
    F_{ZB} 
  \end{bmatrix}
  =
  \begin{bmatrix}
    -A \\
    Y \\
    -N 
  \end{bmatrix},\space and \space
  \vec{F_w} = 
  \begin{bmatrix}
    F_{X_w} \\
    F_{Y_w} \\
    F_{Z_w} 
  \end{bmatrix}
  =
  \begin{bmatrix}
    -D \\
    S  \\
    L 
  \end{bmatrix}
$$

Subscript 'b' stands for balance axes, 'B' standsfor Body axes and 'w' for wind axes

Moment component are consistent with the positive convention of the axes. Thus equation of moments in the balance, body and wind axes will be
$$
\vec{M_b} = \begin{bmatrix}
    M_{X_b} \\
    M_{Y_b} \\
    M_{Z_b} \end{bmatrix} =
  \begin{bmatrix}
    Mr_{b} \\
    Mp_{b} \\
    My_{b} 
  \end{bmatrix},
  \vec{M_B} = 
  \begin{bmatrix}
    M_{X_B} \\
    M_{Y_B} \\
    M_{Z_B} 
  \end{bmatrix}
  =
  \begin{bmatrix}
    l \\
    m \\
    n 
  \end{bmatrix},\space and \space
  \vec{M_w} = 
  \begin{bmatrix}
    M_{X_w} \\
    M_{Y_w} \\
    M_{Z_w} 
  \end{bmatrix}
  =
  \begin{bmatrix}
    l_w \\
    m_w  \\
    n_w 
  \end{bmatrix}
$$
The angles are measured w.r.t. wind axis and clockwise rotation from reference axis to the target axis is considered positive.

## 3. Equipment's

1. Six component force balance
2. Whetstone bridge card (SCXI-1000)
3. Data acquisition card (PXI-1033)
4. Labview software
5. Aircraft models used to do experiment.

## 4. Procedure and Measurements

1. Setting the model on  six component balance  in wind tunnel
2. No wind experiment when no air flow over aircraft model
3. Wind test experimentwhen air flowing over aircraft model in wind tunnel
4. Calculation of aerodynamic coefficients in body as well as in wind axis

> ##### **Aircraft model parameters**

| S.No. | Parameters                                           | Dimension    |
| ----- | ---------------------------------------------------- | ------------ |
| 1.    | Root chord (c)                                       | 0.390 m      |
| 2.    | Wing span (b)                                        | 0.551 m      |
| 3.    | Planform area (A)                                    | 0.1074 $m^2$ |
| 4.    | Horizontal displacemt, reference point (dx)          | 0.21 m       |
| 5.    | Distance between balance center and force guages (d) | 0.035 m      |

​																*Table 1. Aircraft model parameters*

## 5. Calculation

<img src="C:\Users\lakhi\Documents\AE451A\Evaluation of Aerodynamic Coefficients for an Aircraft Model\calc1.jpg" style="zoom:15%;" />

<img src="C:\Users\lakhi\Documents\AE451A\Evaluation of Aerodynamic Coefficients for an Aircraft Model\calc2.jpg" style="zoom:12%;" />

<img src="C:\Users\lakhi\Documents\AE451A\Evaluation of Aerodynamic Coefficients for an Aircraft Model\calc3.jpg" style="zoom:15%;" />

<img src="C:\Users\lakhi\Documents\AE451A\Evaluation of Aerodynamic Coefficients for an Aircraft Model\calc4.jpg" style="zoom:15%;" />

<img src="C:\Users\lakhi\Documents\AE451A\Evaluation of Aerodynamic Coefficients for an Aircraft Model\calc5.jpg" style="zoom:12%;" />

## 6. Data Analysis

> ##### **Inverse Calibration Coefficient Matrix**

![calibration matrix](C:\Users\lakhi\Documents\AE451A\Evaluation of Aerodynamic Coefficients for an Aircraft Model\caliMarix.png)

​												*Table 2. Inverse calibration coefficient matrix*

> ##### **Wind Axis Coefficient Graph**

<img src="C:\Users\lakhi\Documents\AE451A\Evaluation of Aerodynamic Coefficients for an Aircraft Model\WingAxisGraph.png" alt="Wing Axis Coefficient Graph" style="zoom:90%;border:1px solid" />

## 7. Precautions

1. Check the individual resistance of the bridges. 
2. Check  the  bridge  for  shorts  with  the  grounds.  This  should  show  a  very  high resistance of the order of mega ohms.
3. DO NOT SHORT THE OUTPUT  LEADS ONCE THE POWER SUPPLY IS "ON".
4. Check the direction of the outputs by applying small loads.
5. Allow the bridges to warms up for at least one hour actual measurement. 
6. Check the Balance voltage which should not be exceed limit of 6-component strain gage balance

## 8. Questions

1. What are the different aerodynamic forces acting on a model? 

   **Ans.** **Forces :** Lift, Drag, Side force, 

​			**Moments :**	Rolling Moment, Pitching Moment and Yawing Moment

2. What are the working principles of this force balance? 

   **Ans.** The forces are calculated by measuring the strain due to the application of a load which is measured by strain gages (works on Wheatstone bridge principle). Force is calculated from the strain via Hookes Law.

3. What are the other types of balances? 

   **Ans.** Strain gage Load cells, Piezoelectric crystals, Hydraulic load cells, Pneumatic load cells, Magneto-elastic force transducer, etc.,

4. What  are  the  advantages  and  disadvantages  of  mechanical  balance compared to strain gage type?

   **Advantages**: The ease with which they can be used, their relatively low cost and the fact that they are reusable. Additionally, some types require no special instrumentation. 

   **Disadvantages**: Relatively bulky size, long gage lengths and the fact that the variety of practical applications is extremely limited.

5. Why we do no wind analysis in force measurement experiment?

   **Ans.** No wind data is used to calculate the non-aerodynamic (gravity, reaction force, etc) forces acting on the aircraft model, which is later subtracted from the data recorded during the wind experiment to get the aerodynamic forces acting on the model.