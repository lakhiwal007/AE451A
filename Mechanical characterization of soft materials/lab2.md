








<h2 align ="center">Indian Institute of Technology Kanpur</h2>







<h2 align ="center">AE451A</h2>

<h2 align = "center">Experiments in Aerospace Engineering - III</h2>











<h1 align = "center">Experiment No. 2</h1>

<h2 align = "center">Mechanical characterization of soft materials</h2>











### Submitted By:

Ankit Lakhiwal (180102)

[ankitl@iitk.ac.in](To:ankitl@iitk.ac.in)

Aerospace Engineering Department, IIT Kanpur













## 1. Objective

Subjecting filled rubber material to cyclic loading and quantifying energy dissipation in the
material  



## 2. Introduction and Theory

1. <u>Viscoelastic Material</u>

   Viscoelastic materials, as their name suggests, combine two different properties. The term “viscous” implies that they deform slowly when exposed to an external force. The term “elastic” implies that once a deforming force has been removed the material will return to its original configuration.

   The mechanical properties of materials are usually examined by means of stress–strain (or load–deformation) behavior. For purely elastic materials, loading and unloading “stress versus strain” curves (lines) are superimposed. For viscoelastic ones, they form a “hysteresis” loop. The area within the loop represents the energy lost which dissipates as heat. This energy absorption behavior in part explains why viscoelastic materials are good shock absorbers.

   A further important property of viscoelastic materials is that their mechanical properties depend on the rate at which they are deformed. The stiffness of the material increases with the loading rate. Therefore not one stress–strain curve but a whole family of curves represent the deformation behavior at different deformation rates.

2. <u>Mullins Effect</u>

   The **Mullins effect** is a particular aspect of the mechanical response in filled rubbers in which the stress–strain curve depends on the maximum loading previously encountered. The phenomenon, named for rubber scientist [Leonard Mullins](https://en.wikipedia.org/wiki/Leonard_Mullins), can be idealized for many purposes as an instantaneous and irreversible softening of the stress–strain curve that occurs whenever the load increases beyond its prior all-time maximum value. At times, when the load is less than a prior maximum, nonlinear elastic behavior prevails.

   **Material Behaviour**

   The real behaviour of filled rubber elastomers under cyclic loading conditions is quite complex. Certain idealizations have been made for modeling purposes. In essence, these idealizations result in two main components to the material behavior: the first component describes the response of a material point (from an undeformed state) under monotonic straining, and the second component is associated with damage and describes the unloading-reloading behaviour. 

   **Idealized material behaviour**

   When a test specimen is subjected to simple tension from its virgin state, unloaded, and then reloaded, the stress required on reloading is less than that on the initial loading for stretches up to the maximum stretch achieved during the initial loading. This stress softening phenomenon is known as the Mullins effect and reflects damage incurred during previous loading. 

   The following figure illustrate the Idealized response of the Mullins effect model.

   ![Mullin effect](C:\Users\lakhi\Documents\AE451A\Lab2\220px-Mullins_Effect.png)

   ​													*Figure 1. Idealized response of the Mullins effect model*

   

## 3. Experimental Setup

<u>**10kN Tinius Olsen Universal Testing Machine (UTM)**</u> 

<img src="C:\Users\lakhi\Documents\AE451A\Lab2\UTM.PNG" alt="UTM" style="zoom: 100%;" />

​							*Figure 2. Tinius Olsen UTM with 10kN load cell and pressurized grips*

The crosshead is the part of the machine which moves at a 0.25 mm/s displacement rate. Since this is a screw-driven machine, the movement of the crosshead is controlled by the rotation of the screws. The load cell is the component which measures the reaction force provided by the deformed specimen. Since filled rubber samples are quite compliant, therefore, a 250 N load cell is used. Grips of a UTM can be mechanical or pressure controlled. Since filled rubber is a soft material, it is important to provide equal tightening force in upper and lower grips. So, a pressurized grip set is used along with a grip pressure controller.
Two different experiments are conducted in this Lab.

1. **Monotonous loading**: The specimen is stretched at a 0.25 mm/s displacement rate This provides stress-stretch behaviour and failure stress and stretch values. 
2. **Cyclic tensile loading**: The specimen is stretched to a 80% stretch value and then unstretched to zero load level. The loading unloading cycle is carried out 5 times.



## 4. Material and Specimen description

<u>**Dog-Bone shape specimen (ASTM D638 type IV standards )**</u>

<img src="C:\Users\lakhi\Documents\AE451A\Lab2\rubberSpecimen.PNG" alt="Specimen" style="zoom:75%;" />

​															*Figure 3. ASTM D638 Type IV Standard specimen*

The material of specimen is vulcanized rubber which contains natural rubber, recycled and reclaim rubber, sulphur and carbon black(5-10%).

Specimen are cut out as per ASTM D638  standard.

The following figure illustrate the ASTM D638 type IV specimen dimension :

![dogBoneSpecimen](C:\Users\lakhi\Documents\AE451A\Lab2\dogboneSpecimen.png)

​																				*Figure 4.*

The following table describe the dimension of dog-bone shape specimen : 

​																*Table 1. specimen dimension*

| S.N. | Specimen section            | Dimension |
| ---- | --------------------------- | --------- |
| 1.   | Thickness (T)               | 2.50 mm   |
| 2.   | Width of narrow section (W) | 6 mm      |
| 3.   | Lengthof narrow section (L) | 33 mm     |
| 4.   | Distance between grips (D)  | 65 mm     |
| 5.   | Gauge Length (G)            | 25 mm     |

## 5. Experimental Procedure

Following experimental procedure is followed to conduct the experiments.

1.  A 250 N load cell with pneumatic pressure-controlled grips are mounted on the machine.

2. The sample is loaded with the distance between grips 65 mm.

3.  Specimen is subjected to 0.25 mm/s displacement rate under quasi-static loading condition, until the failure is observed in the material. The force vs. stretch data, recorded by the equipment, is analysed.
   
4.  For subjecting the specimen to cyclic loading, a displacement/stretch, less than the one associated to failure, is defined. The sample is loaded to this prescribed displacement and then unloaded until zero-load is attained. The loading-unloading cycle is repeated 5 times.  
   
   

## 6.  Calculation and Post-Processing of Data

$$
\bold{Nominal\space Stress\space (\sigma_n)} = \frac{Force}{Initial\space Area} = \frac{F}{A_0}
$$


$$
\bold{Stretch\space (\lambda)} = \frac{Extended\space Guage\space Length}{Initial\space Guage\space Length} = \frac{G + \Delta G}{G}\\
\\
G :\space Initial\space Guage\space Length\space = 25mm
$$

$$
\bold{Dissipated\space Energy}\space = \int_{loading}(\sigma.d\epsilon)\space - \space \int_{unloading}(\sigma.d\epsilon)
$$

$$
\begin{align}
A_0 &= Thickness\space(T) * \space Width\space of\space narrow\space section(W)\space\\ 
	&=(2.5*6)\space mm^2 = 15\space mm^2
\end{align}
$$

1. **Mono Loading Data Table**

   

   ![Monoloading data](C:\Users\lakhi\Documents\AE451A\Lab2\MLDF.PNG)

   ​													*Table 2. MonoLoading data table*

   

   

   * <u>Nominal-Stress Vs Stretch Graph</u>

     

     ![](C:\Users\lakhi\Documents\AE451A\Lab2\ML_NominalStressVsStretch.png)

     ​							*Graph 1. Nominal-Stress Vs Stretch Graph for mono loading data*
     
     

2. **Cyclic Loading Data Table**

   

   ![](C:\Users\lakhi\Documents\AE451A\Lab2\CLDF.PNG)

   ​													*Table 3. Cyclic loading data table*

   

   * <u>Nominal-Stress vs Stretch Graph</u>

     

     ![](C:\Users\lakhi\Documents\AE451A\Lab2\CL_NominalStressVsStretch.png)

     ​							*Graph 2. Nominal-Stress vs Stretch Graph for cyclic loading data*

   * <u>Position vs Time Graph</u> 

     

     ![position vs time](C:\Users\lakhi\Documents\AE451A\Lab2\positionVsTime.png)

     ​									*Graph 3. Position vs Time graph for cyclic loading data*

   * <u>Nominal-Stress vs Stretch Grapg for Different Cycle</u>

     

     ![Cycles](C:\Users\lakhi\Documents\AE451A\Lab2\Cycles.png)
     
     ​									*Graph 4. graph of stress vs stretch for different cycles*

3. **Nominal-Stress Vs Stretch Graph** 

   * <u>For Mono and Cyclic Loading data</u>

     

     ![ML_and_CL](C:\Users\lakhi\Documents\AE451A\Lab2\MLandCL.png)
     
     ​						*Graph 5. stress vs stretch graph for mono loading and cyclic loading*

4. **Dissipated Energy at Every Cycles**

   

   ![Energy Dissipation table](C:\Users\lakhi\Documents\AE451A\Lab2\EnergyDissp.PNG)

   ​										*Table 4. Dissipated energy table at different cycles*

   

   * <u>Graph of Energy Dissipation at every cycle</u>

     

     ![graph of energy dissipation at differnt cycles](C:\Users\lakhi\Documents\AE451A\Lab2\EnergyVsCycle.png)
     
     ​										*Graph 6. graph of dissipated energy at different cycles*



## 7. Conclusion

* In Mono Loading :

  *  specimen broke at 2.9 stretch ratio.
  *  maximum applied Nominal-Stress was 2.86 MPa. [see Graph 1.]()

* In Cyclic Loading :

  * In every successive cycle the area between loading and unloading was reduced. [see Graph 4.]()
* Maximum energy dissipated during cycle 1. [see Table 4.]()
  * Energy dissipation reduced at every cycle. [see Graph 6.]()
* After cycle 5, stress-stretch curve follow the cycle 1 graph when Force applied again on specimen. [see Graph 5.]()

## 8. Precautions and Sources of Error

1. <u>Precautions</u> :

   * Take measurements as precisely as you can.
   * Calibrate and check for any fault in load cell and software.
   * Keep a safe distance from UTM and don't try to touch specimen during applying load to specimen.

2. <u>Source of Error</u> :

   * Human error during measurement of specimen.

   * Calibration error in load cell or software using for calculation.

   * Specimen dimension error due to temprature.

     

## 9. References

For a detailed code click on the link  <a style ="font-size:1.5em; color:rgb(0,0,0);background-color:rgb(255,255,0)" href="https://jovian.ai/lakhiwalankit0002/lab2">Lab-2 Jupyter NoteBook</a>

1. [Viscoelastic Material - an overview | ScienceDirect Topics](https://www.sciencedirect.com/topics/materials-science/viscoelastic-material)
2. [ABAQUS Analysis User's Manual (v6.5-1) (wustl.edu)](https://classes.engineering.wustl.edu/2009/spring/mase5513/abaqus/docs/v6.5/books/usb/default.htm?startat=pt04ch10s06abm09.html)
3. [Mullins effect - Wikipedia](https://en.wikipedia.org/wiki/Mullins_effect)

