<h1 align ="center">Indian Institute of Technology Kanpur</h1>





<h1 align ="center">AE451A</h1>

<h1 align = "center">Experiments in Aerospace Engineering - III</h1>





<h3 align = "center">Experiment No. 8</h3>

<h1 align = "center">Studies on Subsonic jet propagation</h1>





### Submitted By:

Ankit Lakhiwal (180102)

[ankitl@iitk.ac.in](To:ankitl@iitk.ac.in)

Aerospace Engineering Department, IIT Kanpur

October 11, 2021









## 1. Objective

To study the development of velocity profiles in an axisymmetric jet by using a single Pitot tube with traverse mechanism.

## 2. Intoduction and theory

Free turbulence: High-Reynolds-number shear flow in an open ambient  fluid, unconfined or uninfluenced by walls. A jet issuing into a still (or moving) stream is a common case of free turbulence. It has a characteristic velocity scale, $U_{max}(x)$ and a characteristic shear-layer width, b(x). Since these flows are free, or unconfined, the pressure is approximately constant throughout the flow, except for (small) turbulent fluctuations within the layer.

Figure1. shows the details of the initial formation of a jet, assuming a still ambient  fluid. The figure is valid only for similar jet and ambient  fluids, e.g., air-into-air, not water-into-air. Velocity profiles are shown as thick dark lines across the flow. Typically the jet issues as a nearly  at, fully developed turbulent velocity $U_{exit}$. Mixing layers format the lip of the exit, growing between the still ambient and the nearly inviscid potential core flowing at velocity $U_{exit}$.

<div style = "text-align:center;">
    <img src="Subsonic Jet Propagation\jet.png" alt="subsonic jet" style="zoom:100%;" />
    <figcaption style="font-style:italic;">Figure 1. Initial formation of jet</figcaption>
</div>

The region where the centre line velocity is equal to the nozzle outlet velocity is called the potential core of the jet. The potential core vanishes quickly, at a distance of about one diameter from the exit, where the velocity profile loses its mixing-layer- at-core shape. Downstream of the core, the flow begins to develop into the distinctive gaussian-type shape we call as jet




## 3. Equipment's

<div style = "columns:2;">
    <ol>
        <li>Settling chamber</li>
		<li>Compressor to compress air</li>
		<li>Storage tanks for compressed air</li>
        <li> NI data aquisition card</li>
        <li>L-shape pitote probe</li>
        <li>Digital differential manometer</li>
        <li>Computer</li>
    </ol>
</div>

## 4. Procedure

1. Draw the schematic sketch of the jet flow system.
2. Measure the centerline velocity in the jet at several $\frac{x}{D}$ locations.
3. Measure the velocity profiles of a jet at $\frac{x}{D}$ = 2, 8 and 23.
4. From the acquired data, compute jet width at the two locations.
5. Compare the theoretical incompressible jet results with experimental results.

## 5. Experimental Setup

![setup](Subsonic Jet Propagation\expSetup.png)

​										*Figure 2. Schematic diagram of open jet facility*

<div style = "columns:2;">
    <ol>
        <li>150 hp induction motor</li>
        <li>Reciprocating compressors</li>
        <li>Activated charcol filter and silica gel dryer units</li>
        <li>Water cooling units</li>
        <li>Storage tanks</li>
        <li>Gate valves</li>
        <li>Pressure regulating valve</li>
        <li>Settling chamber</li>
        <li>Traversing chamber</li>
        <li>Instumentation desk</li>
    </ol>
</div>
## 6. Calculation

Ambient pressure $P_a$ = 1atm = 29.921 in-hg = 101325.027 Pa

Ambient temprature $T_a$ = 303 K (assumed)

R = 287 J/Kg/K , 	$\gamma$ = 1.4 (for air)

Speed of sound a  = $\sqrt{\gamma*R*T_a}$ = $\sqrt{1.4*287*303}$ = 348.92033 m/s

Density $\rho = \frac{P_a}{R*T}$ = $\frac{101325.027}{287*303}$ =  1.165 kg/$m^3$

Nozzle diameter  D = 10 mm

**At  $\frac{x}{D}$ = 10.1852** 

Stagnation pressure P_0 = 2.982 in-hg + P_a = 111423.243 Pa 
$$
\frac{P_0}{P_a} = (1 + \frac{\gamma -1 }{2}M^2)^{\frac{\gamma}{\gamma -1}} => U_0 = \sqrt{[(\frac{P_0}{P_a})^{\frac{\gamma}{\gamma -1}} -1]\frac{2}{\gamma -1}} = 129.42\space \frac{m}{s}\\
$$
Pitote probe pressure P = 1.779 in-hg = 6024.3878 Pa
$$
from\space Bernoulli's\space equation \space: \frac{1}{2}\rho u^2 =\space P\\

u\space =\space \sqrt{\frac{2P}{\rho}} = 101.689\space \frac{m}{s}\\

\frac{u}{U_0} =\space 0.79757235\space  \frac{m}{s} \\
$$




## 7. Data analysis

> **Velocity profile for centerline**

<img src="Subsonic Jet Propagation\xbyD vs ubyU0.png" alt="graph" style="zoom:100%;border:1px solid;" />

​									*Graph 1. centerline velocity profile*

> **Velocity profile at different transverse locations**

<img src="Subsonic Jet Propagation\ybyD vs ubuu0.png" alt="graph" style="zoom:100%;border:1px solid;" />

​									*Graph 2. radial direction velocity profile*

## 8. Results

<u>**Jet Width**</u>

1. at 2D location = 
2. at 8D location = 
3. at 23D location = 

## 9. Questions

1. What is invariant across a jet?

   **Ans.** Static pressure and linear momentum remain same across the jet.

2. Give two practical applications for jet mixing.

   **Ans.** Water jet cutting and Noise reduction

3. What is jet width? How is it calculated from the velocity profile?

   **Ans.** Jet width at a particular x is defined as twice the distance measured from the centreline to the point on y-axis where the local velocity is half that of centre line velocity at that x. 

## 10. References

1. [https://ntrs.nasa.gov/api/citations/19720016717/downloads/19720016717.pdf](https://ntrs.nasa.gov/api/citations/19720016717/downloads/19720016717.pdf)
2. [Jupyter Notebook  of Lab 8 Data analysis]()
