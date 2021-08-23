<h2 align ="center">Indian Institute of Technology Kanpur</h2>







<h2 align ="center">AE451A</h2>

<h2 align = "center">Experiments in Aerospace Engineering - III</h2>



****





<h1 align = "center">Experiment No. 3</h1>

<h1 align = "center">Full-field stress analysis using photo-elasticity method</h1>









### Submitted By:

Ankit Lakhiwal (180102)

[ankitl@iitk.ac.in](To:ankitl@iitk.ac.in)

Aerospace Engineering Department, IIT Kanpur

August 16, 2021

















## 1. Objective

* To perform experimental stress measurements on an epoxy beam subjected to four-point bending using photoelasticity. 

* To measure the normal stress variation across the cross-sectional area of a beam, and compare the obtained data to the results predicted by beam theory.  

## 2. Introduction and Theory

**PhotoElasticity**
$$
Index \space of \space refrection\space = \space \frac{Speed\space of\space light\space in\space vaccum}{Speed\space of\space light\space in\space material}
$$
Many transparent non-crystallize material that are optically isotropic when free of stress becomes optically an isotropic (temporary double refrective) when they are subjected to stress. The birefringent (changing refractive index upon loading) material characterstic is used in the method of photoelasticty.

![](C:\Users\lakhi\Documents\AE451A\Full-field stress analysis using photoelasticity method\photo.PNG)

​																			*Image 1.*

When a polarized light passes through a stressed material the light wave gets resolved into two mutually perpendicular components in the direction of the material principle stress.

The two wavelength travel at different velocities subjectively the stressed material having two different indices of refraction (n1 and n2). maxwell noted that the charges in the refrective indices are linearly proportional  to the loads.For 2-D case the stress-optics (Brewster's ) law
$$
n_1-n_0 = C_1 \sigma_1 + C_2\sigma_2  (...+ C_2\sigma_3 \space in \space 3D)\\
n_2-n_0 = C_1 \sigma_2 + C_2\sigma_1  (...+ C_2\sigma_3 \space in \space 3D)
$$

$$
Where : \\
\sigma_1,\sigma_2 &=& Principal\space stress\\
n_1,n_2 &=&\space refrective\space indices\space in\space \sigma_1\space and\space \sigma_2\space direction\\
n_0 &=& refrective\space index\space of\space unstressed\space material\\
C_1,C_2 &=& Stress-optics\space constants
$$

eliminating n0 to get 
$$
n_2-n_1 = (C_2-C_1)(\sigma_1-\sigma_2)=C(\sigma_1-\sigma_2)
$$
where C = C1 - C2 is  relative stress-optics coeeficient first expressed in terms of brewsters 
$$
1\space brewster = 10^{-12}\frac{m^2}{N}
$$

The two resolved light components travel through the medend at different velocities, therefore, they emerge from the plate at different times. In other words one components retards in time compared to the other.

The relative linear phase shift also known as retardation can be computed as
$$
\delta = h(n_2-n_1)\\
\Delta = \frac{2\pi}{\lambda}\delta = \frac{2\pi h}{\lambda}(n_2-n_1)\\
or \space \sigma_1-\sigma_2 = \frac{\delta}{hc} = \frac{\lambda}{2\pi hc}\Delta\\
where\space h\space is\space material\space thickness\space or \space relative \space angular \space phase \space shift
$$

$$
Replacing \space \frac{\Delta}{2\pi} = N \space...\space fringe\space order\\
and \space \frac{\lambda}{c} = f_{\sigma}\space...\space fringe\space constant\\
to\space get \space \sigma_1-\sigma_2 = \frac{nf_{\sigma}}{h}
$$

![](C:\Users\lakhi\Documents\AE451A\Full-field stress analysis using photoelasticity method\2.PNG)

​																				*Image 2.*

Consider a core when plane stresed model is inserted into the field of plane polariscope. Let the principal stress direction makes an angle  polarization axis.
Plane polarizer resolves an incident light wave into Components which vibrate parallel and perpendicular to the axis of the polerizer. The parallel component is transmitted and the component perpendiculor to the polarizer axis is absorbed Initial phase of the wave is not important here, therefore the plane polasized light beem emerging from the polarizer can be represented as Ep = k cos wt

![](C:\Users\lakhi\Documents\AE451A\Full-field stress analysis using photoelasticity method\3.PNG)

​																				*Image 3.*

The light wave emerging from the material(stressed) resolved into the components E1 and E2
$$
E_1 = Kcos\alpha\space cos(\omega t-\Delta_1)\\
E_2 = Ksin\alpha\space cos(\omega t-\Delta_2)
$$

$$
where \space \Delta_1 \space and \space \Delta_2 are\space developed\space phase \space shifts\\
\Delta_1 = \frac{2\pi h}{\lambda}(n_1-1)\\
\Delta_2 = \frac{2\pi h}{\lambda}(n_2-1)\\
$$

After leaving the material the light waves E1 and E2 propagate without further change and the analyzer, subjecting E1 and E2 to get resolved further into vertical and horizontal components. Vertical components absorbed and only horizontal components in the direction of analyzer axis passes through, Therefore, the emerging light from the analyzer
$$
E = E^{'}_{2}-E^{'}_{1} = E_2cos\alpha - E_1sin\alpha\\
or\space E = Ksin2\alpha\space sin(\frac{\Delta_2-\Delta_1}{2})\space sin(\omega t-\frac{\Delta_2+\Delta_1}{2} )
$$
![](C:\Users\lakhi\Documents\AE451A\Full-field stress analysis using photoelasticity method\4.PNG)

​																				*Image 4.*

Therefore, light intensity emerging from the analyzer
$$
I = [Ksin2\alpha\space sin(\frac{\Delta_2-\Delta_1}{2})]^2 = Ksin^22\alpha\space sin^2\frac{\Delta}{2}\\
\Delta = \Delta_1 - \Delta_2\\
or \space \Delta = \frac{2\pi h}{\lambda}(n_2-n_1)= \frac{2\pi h}{\lambda}(\sigma_1-\sigma_2)
$$

$$
clearly \space I = 0\space if \space sin^22\alpha = 0 \space (function\space of \space principal \space stress \space direction) \space\\ or \space when \space sin^2\frac{\Delta}{2} = 0 \space(related \space to \space principal \space stress \space difference)
$$

Effect of principal stress direction
$$
when\space 2\alpha = n\pi = 0\\
n = 0,1,2,...
$$
i.e. light intensity vanishes when one of the principal sterss direction coincides with the polarizer axis. When the entire stress field is observed in the poleriscope, a fringe pattern is observed. The fringes are loci of points where th e principal stress direction coincide with the axis of polarizer. The fringe pattern produced by 
$$
sin^22\alpha
$$
term is called **isoclinic fringes.**
Effect of Principal stress difference.

 When 
$$
\frac{\Delta}{2} = n\pi = 0\\
n = 0,1,2,...
$$
light intensity vanishes when the principal stress difference is zero or sufficient to produce an integrel number of wave lengths of retardation (n=1,2,3...). The fringes produced by 
$$
sin^2\frac{\Delta}{2}
$$
 term is called **isochoretic fringe** pattern.

Consider
$$
\Delta = \frac{2\pi hc}{\lambda}(\sigma_1-\sigma_2)
$$
light intensity extinguishes when 
$$
\frac{hc}{\lambda}(\sigma_1-\sigma_2) = n\\
n = 1,2,3,....\\
or \space n = 0 => \space \sigma_1 = \sigma_2
$$
When a model is viewed in monochromatic light the fringe pattern appears as a series of dark bands. However with á white light the isochromatic fringe pattern is a series of Colored bands. A black fringe appeors only when 
$$
\sigma_1-\sigma_2 = 0
$$
with non-zero value of 
$$
\sigma_1-\sigma_2
$$
only one wave length at c - time can get extinct, resulting in a complementary color to that have longth instead of dark band eg. when 
$$
\sigma_1-\sigma_2
$$
produces the extinction of green the complementary color red appears in the isochromatic fringe pattern. At higher levels of principal stress difference several wave length can be extinguished Simultaneously, therefore the fringes become pole and very difficult to analyze.
By using circulor poleriscope isoclinic fringes con be removed leaving behind only isochromatic fringes.

![](C:\Users\lakhi\Documents\AE451A\Full-field stress analysis using photoelasticity method\5.PNG)

​																				*Image 5.*
$$
E = Ksin\frac{\Delta}{2}\space sin(\omega t +2\alpha - \frac{\Delta}{2})\\
intensity\space of \space light\space I = K^2sin^2\frac{\Delta}{2}\\
$$
**Calibration Method**

To determine the accurate stress distribution calibraic experiment is performed to get the fringe constant.

In a circular disk subjected to diameter compresion the stress distribution along horizontal  axis (y=0) is given by 
$$
\sigma_{xx} = \sigma_1 = \frac{2P}{\pi h D}(\frac{D^2-4X^2}{D^2+4X^2})^2\\ \\
\sigma_{yy} = \sigma_2 = -\frac{2P}{\pi h D}(\frac{4D^4}{D^2+4X^2}-1)\\ \\
\tau_{xy} = 0
$$
![](C:\Users\lakhi\Documents\AE451A\Full-field stress analysis using photoelasticity method\6.PNG)

​																				*Image 6.*
$$
\sigma_1-\sigma_2 = \frac{8P}{\pi h D}[\frac{D^4-4D^2X^2}{(D^2+4X^2)^2}] = \frac{Nf_{\sigma}}{h}\\ \\
f_{\sigma} = \frac{8P}{\pi N D}[\frac{D^4-4D^2X^2}{(D^2+4X^2)^2}]
$$
Calculate fsigma for various N (fringe order) at a given load P and average out the value

or at x=0, y=0 (center point)
$$
f_{\sigma} = \frac{8P}{\pi N D}
$$
fringe order at the center of the disk can be plotted with p to get fsigma.

## 3. Equipments'

1. <u>Monochromatic light</u>

   <img src="C:\Users\lakhi\Documents\AE451A\Full-field stress analysis using photoelasticity method\monochromatic light.jpg" alt="Monochromatic light" style="zoom:50%;" />

   ​													*Image 7. monochromatic light source*

2. <u>Beam Expander/Collimator and lenses</u>

   <div style = "text-align:center;display:inline-flex;justify-content:center;align-items:center">
       <figure>
       	<img src="C:\Users\lakhi\Documents\AE451A\Full-field stress analysis using photoelasticity method\beam-expander-2x10x.webp" alt="beam expander" style="zoom:15%;" />
           <figcaption style="font-style:italic;font-size:15px;">Image 8. Beam Expander</figcaption>
       </figure>
       <figure>
           <img src="C:\Users\lakhi\Documents\AE451A\Full-field stress analysis using photoelasticity method\colimator.jpg" alt="collimator" style="zoom:15%; height:1120px" />
           <figcaption style="font-style:italic;font-size:15px;">Image 9. collimator</figcaption>
       </figure>
   </div>
   
   
   
3. <u>Polarizers</u>

   A polarizer is an element that converts randomly polarized light into plane-polarized light.

   <img src="C:\Users\lakhi\Documents\AE451A\Full-field stress analysis using photoelasticity method\polarizers.jpg" alt="polarizers" style="zoom:25%;" />

   ​																*image 10. Polarizers*

   

   

4. <u>Quarter Wave Plates</u>

   A quarter-wave plate (Fig. 12) is a permanent wave plate that induces a phase shift δ equal to λ / 4, where λ is the wavelength of the light being used.

   <img src="C:\Users\lakhi\Documents\AE451A\Full-field stress analysis using photoelasticity method\quarter order wavw plates.jpg" alt="qwp" style="zoom:20%;" />

   ​															*image 11. quarter wave plates*

5. Loading fixtures

   

6. <u>DSLR Camera/White Sheets to view the fringes</u>

   <div style = "text-align:center;display:inline-flex;justify-content:center;align-items:center">
   	<figure>    
           <img src="C:\Users\lakhi\Documents\AE451A\Full-field stress analysis using photoelasticity method\Canon_DSLR_Camera.jpg" alt="camera" style="zoom:20%;" />
           <figcaption>image 12. DSLR camera</figcaption>
       </figure>
       <figure>
           <img src="C:\Users\lakhi\Documents\AE451A\Full-field stress analysis using photoelasticity method\whitesheets.jpg" alt="whitesheets" style="zoom:50%;" />
       	<figcaption>image 13. white sheets</figcaption>
       </figure>
   </div>

   

7. Specimen made of Epoxy  (see image 14.)

## 4. Measurement

* **<u>Epoxy Beam</u>**

![epoxyBeam](C:\Users\lakhi\Documents\AE451A\Full-field stress analysis using photoelasticity method\epoxybeamedited.png)

​													*Image 14. Dog-Bone shape Epoxy Specimen*

​				**h = 19 mm**

​				**b = 5 mm**

* **<u>4 Point Beam Bending Setup</u>**

<img src="C:\Users\lakhi\Documents\AE451A\Full-field stress analysis using photoelasticity method\4pointbendingsetup.jpg" alt="4 point bending setup" style="zoom:50%;" />



<img src="C:\Users\lakhi\Documents\AE451A\Full-field stress analysis using photoelasticity method\Psetup.PNG" alt="Rod"  />

​															*Image 15 and 16.  4 Point Bending Setup*

| S.N  | Setup Parts Name                                        | Mass and Dimension |
| ---- | ------------------------------------------------------- | -----------------: |
| 1.   | **Weight distribution of the rod **                     |           1.150 Kg |
| 2.   | **Mass of the pan (Po)**                                |           0.700 Kg |
| 3.   | **Load applied to the pan (P)**                         |               2 Kg |
| 4.   | **P point load **                                       |           0.043 Kg |
| 5.   | **P 4pb **                                              |           0.523 Kg |
| 6.   | **Total length of the rod (L) **                        |             745 mm |
| 7.   | **length before the simple support point (L1) **        |             175 mm |
| 8.   | **length from simple support to pin point (L2) **       |             120 mm |
| 9.   | **length from pin point to force applied on pan (L3) ** |             450 mm |
| 10.  | **distance from the center of symmetry (d) **           |              20 mm |

​													*Table 1. 4 Point Bending Setup Specification*

## 5. Procedure

- The dimensions of the specimen needed for beam stress calculations (e.g. length of beam, cross-sectional dimensions, precise locations of supports, precise locations of applied concentrated loads, etc.) is to be measured.

- The specimen is to be placed and loaded in symmetric four point bend fixture.

- The source of monochromatic light is to be switched on and aligned in such a way that it falls on the mid-section of the specimen.

- The specimen is to be tested by applying selected loads, and photo elastic fringe patterns are captured by means of DSLR camera (or by drawing). At each fringe location, the **experimental normal stress** value is calculated by using the formula  

  

$$
\sigma_x = \frac{N{f_\sigma}}{b}
$$

- The formula
  $$
  \sigma_x(x,y) = \frac{M(x)y}{I}
  $$
  is to be used to calculate the **theoretical stress** distribution over the cross-sectional area of the
  beam , and compare the results to the photoelastic experimental measurements.  

## 6. Experimental Setup

The figure shown below is a schematic representation of the Photo Elasticity Experiment.

![experimental setup](C:\Users\lakhi\Documents\AE451A\Full-field stress analysis using photoelasticity method\expSetup.PNG)

​															*Image 17. Experimental Setup*

As shown in the figure below, each two-force member transfers a force of F/2 to the epoxy
beam. This results in a constant bending moment in the center region of the beam (between
the inner two forces) with a value of  
$$
M = \frac{Fd}{2}
$$
![loads on epoxy beam](C:\Users\lakhi\Documents\AE451A\Full-field stress analysis using photoelasticity method\4PointBeam.PNG)

​														*Image 18. Force distribution on the Beam*

The theoretical stress distribution on any cross-sectional area in the center region of the beam is
given by:  
$$
\sigma_x(y)\space = \space \frac{My}{I} \space = [\frac{Fd}{2}]y\space = \space Cy
$$
where C is a constant that can be calculated. Using the recorded photo elastic fringe pattern,
experimental values of stress can be calculated at various vertical positions (y). As part of
this experiment, a table is to be prepared such as shown below, which lists the measured and
predicted stresses at the various photo elastic fringe locations.  

## 7. Calculation 

![model](C:\Users\lakhi\Documents\AE451A\Full-field stress analysis using photoelasticity method\model.PNG)

​												*Image 12. Free body Diagram of Beam*

​	beam mass distribution throuhout the beamlength,
$$
w\space &=& \frac{Mass\space of\space the\space beam}{L}\\
&=& \frac{1.150}{745}\frac{Kg}{mm} \\
&=& 0.0015\space \frac{Kg}{mm}
$$
Conserving the moment  about the simple support,
$$
\frac{wL_1^2}{2}\space - \space \frac{w(L_2 + L_3)^2}{2}\space + (R_{F1}L_2)\space - (P_0 + P)(L_2+L_3)\space = \space 0
$$
Solving for the reaction force,
$$
R_{F1}\space = \frac{1}{L_2}[(P_0+P)(L_2+L_3)\space - \space\frac{wL_1^2}{2}\space + \space \frac{w(L_2 + L_3)^2}{2} ]\\
= \frac{1}{120}[(0.700 + 2)(120+450)\space - \space \frac{0.0015*(175)^2}{2}\space + \space \frac{0.0015*(120 + 450)^2}{2}]\space Kg\\
= 14.6624\space Kg
$$
Therefore, the resultant load acting on the sample,
$$
F = R_{F1}+P_{point\space load}\space + \space P_{4PB}
$$

$$
F &=& (14.6624 + 0.043 + 0.523) \space Kg\\
&=& 15.2303\space Kg
$$

<u>Theoritical stress value</u>
$$
\sigma_x(x,y) &=& \frac{M(x)y}{I}\\
&=& \frac{Fd}{2I_{zz}}y
$$

$$
Where:\space I_{zz} = \frac{bh^3}{12} \\
= \frac{5*19^2}{12}\space mm^4 \\
= 150.4166\space mm^4
$$

​	**From px to mm change**
$$
Neutral\space axis\space position  = 1653\space px\\
y :\space i_{th}\space fringe\space position\space in\space mm\\
h = 19\space mm : \space specimen \space height \space in \space mm\\
p_{top},p_{bottom} :\space top\space and \space bottom\space fringe\space position\space in \space px\\
p_i :\space position\space of\space i_{th}\space fringe
$$
$$
y = \space \frac{p_i*h}{|p_{top}-p_{bottom}|}
$$

​	**at p_i = 763 px**
$$
y = \frac{763*19}{|593-2439|} = \space 9.1504 \space mm\\
\sigma_{th} = \frac{15.2303*20}{2*150.4166}*9.1504\space \frac{N}{mm^2} = \space 9.265157 \space MPa
$$
<u>Experimental stress value</u>
$$
\sigma_x = \frac{N{f_\sigma}}{b}
$$

$$
Where:\space &N = \space Order\space of \space Fringes\\
&f_{\sigma}= \space Fringe\space Coefficient\\
&f_{\sigma} = 12\space \frac{N}{mm}
$$

​	**For N = 2**
$$
\sigma_x = \frac{2*12}{5}\space \frac{N}{mm^2}\space = \space 4.8\space MPa
$$

> **Fringe pattern **

![fringe image](C:\Users\lakhi\Documents\AE451A\Full-field stress analysis using photoelasticity method\(48)_2kg.JPG)


| Fringe Order | Fringe Location (in px) | Fringe Location (in mm) | Theoritical stress value (MPa) | Experimental stress value (MPa) |
| ------------ | ----------------------- | ----------------------- | ------------------------------ | ------------------------------- |
| 3            | 593                     | 10.8983                 | 11.034977                      | 7.2                             |
| 2            | 763                     | 9.1504                  | 9.265157                       | 4.8                             |
| 1            | 959                     | 7.1353                  | 7.224785                       | 2.4                             |
| 0            | 1403                    | 2.5703                  | 2.602535                       | 0                               |
| -1           | 1995                    | -3.5162                 | -3.560297                      | -2.4                            |
| -2           | 2219                    | -5.8192                 | -5.892180                      | -4.8                            |
| -3           | 2327                    | -6.9296                 | -7.016505                      | -7.2                            |
| -4           | 2439                    | -8.0811                 | -8.182446                      | -9.6                            |

​						*Table 2. Experimental and Theoritical stress values at different fringe location*



> **Graph between Stress and Locationof fringes**

<img src="C:\Users\lakhi\Documents\AE451A\Full-field stress analysis using photoelasticity method\output.svg" alt="graph" style="zoom:120%;" />

​												*Graph 1. stress values at different fringe locations*

> $$
> \bold{slope \space = \space \frac{M}{I_{zz}} = \space \frac{Fd}{2I_{zz}}}\space \frac{N}{mm^3}
> $$



- Slope of *Theoritical stress value* and Location of fringes graph = **1.0125 N/mm3**
- Slope of *Experimental stress value* and Location of fringes graph =  **0.745 N/mm3**

## 8. Error Analysis

![error table](C:\Users\lakhi\Documents\AE451A\Full-field stress analysis using photoelasticity method\error.PNG)

​																*Table 3. Error in stress values*



> **Error in stress value at different fringe location** 

![error graph](C:\Users\lakhi\Documents\AE451A\Full-field stress analysis using photoelasticity method\errorGraph.svg)

​										*Graph 2. Error in stress values at differnet fringe location*

## 9. Results

> For 2Kg mass :

- Slope of *Theoritical stress value* and Location of fringes graph = **1.0125 N/mm3**
- Slope of *Experimental stress value* and Location of fringes graph =  **0.745 N/mm3**
- % mean error = 35.745 %

## 10. Precautions and Source of Error

> **Precautions**

- Take picture only when load pan come to equllibrium after applied load.
- Be precise during measuring location from neutral axis of a fringe.
- Correct the orientation of quarter wave plates.
- Check the equipments before experiment.

> **Source of Error**

- Measuring fringe distance manually can produce error.
- Error in collimation of beam.
- Load may not vary linearly across the beam.



