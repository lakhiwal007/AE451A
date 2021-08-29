<h2 align ="center">Indian Institute of Technology Kanpur</h2>







<h2 align ="center">AE451A</h2>

<h2 align = "center">Experiments in Aerospace Engineering - III</h2>









<h1 align = "center">Experiment No. 4</h1>

<h2 align = "center">Vibration characteristics of a slender beam</h2>









### Submitted By:

Ankit Lakhiwal (180102)

[ankitl@iitk.ac.in](To:ankitl@iitk.ac.in)

Aerospace Engineering Department, IIT Kanpur

August 23, 2021



















## 1. Objective

- Observe a beam vibrating under resonance, and retrieve its fundamental frequencies.

- Record acceleration and strain histories in a vibrating cantilever beam and evaluate its vibration characteristics by employing Fast Fourier Transform. 

## 2. Introduction And Theory

Free vibration occurs when a mechanical system is set in motion with an initial input and allowed to  vibrate freely. The mechanical system vibrates with a combination of frequencies, out of which one or  more may be dominated. If left unperturbed, the vibration damps down to motionlessness. Some of the  examples of free vibration are, pulling a child back on a swing and letting it go, or hitting a tuning fork  and letting it ring.

Forced vibration is observed when a time-varying disturbance (load, displacement or velocity) is  applied to a mechanical system. The disturbance can be periodic with steady-state, transient or  random input. The periodic input can further be divided into harmonic and non-harmonic  disturbance. The importance of this mode rises in the engineering field. Machines, motors and  other industrial applications, exhibits this mode of vibrations, which may cause a serious damage  of the equipment. Washing machine shaking due to an imbalance, transportation vibration caused by an engine or uneven road, or the vibration of a building during an earthquake are some of the examples of forced vibration.

A straight, horizontal cantilever beam under a vertical load will deform into a curve. When this force is removed, the beam will return to its original shape, however it's inertia will keep the beam in motion.

<img src="C:\Users\lakhi\Documents\AE451A\Vibration analysis\Free cantilever beam.png" alt="cantilever beam" style="zoom:75%;" />

If there are no external driving forces and the beam is vibrating under the influence of gravitational forces, we get: 
$$
EI\frac{\partial^4w}{\partial x^4} \space = \space -\mu \frac{\partial^2w}{\partial t^2}
$$
The above equation can be solved by variable separation to obtain: 
$$
y(x) = (c_1cos\beta x + c_2sin\beta x + c_3cosh\beta x + c_4sinh\beta x)(Asin\omega t + Bcos\omega t)\space .......(1)\\
where\space\space \space \omega \space = \beta^2 \sqrt\frac{EI}{\rho A}\space ........(2)
$$
Where, µ is mass per unit length

E is the modulus of rigidity

I is moment of inertia

w is the displacement

x is the distance from fixed end

C1,C2,C3,C4 are constants of integration (to be determined by boundary conditions)

For a cantilever beam, the boundary conditions are following :
$$
BC\space 1\space &:&\space y(x) = 0, \space at \space x =0\space;\\
BC\space 2\space &:&\space \frac{dy}{dx} = 0, \space at \space x =0\space;\\
BC\space 3\space &:&\space \frac{d^2y}{dx^2} = 0, \space at \space x =l\space;\\
BC\space 4\space &:&\space \frac{d^3y}{dx^3} = 0, \space at \space x =l\space;\\
$$
solving for boundary condition, we get 
$$
\bold{\beta l \space = \space 1.8751,\space 4.6941,\space 7.8548, \space 10.995} \space ....(3)
$$

## 3. Equipments'

<div style="columns:100px 2; text-align:center;">
    <figure style= "border: 1px solid grey;border-radius:5px;">
    	1.Electrodynamic shaker<hr>
    <img src="C:\Users\lakhi\Documents\AE451A\Vibration analysis\electromagnatic shaker.png" alt="Electrodynamic shaker" style="zoom:40%;" /><br>
        <figcaption style="font-style:italic">Image 3.(a)</figcaption>
    </figure>
    <figure style= "border: 1px solid grey;border-radius:5px;">
    	2.Function generator<hr>
    <img src="C:\Users\lakhi\Documents\AE451A\Vibration analysis\function generator.png" alt="Function generator" style="zoom:60%;" />
        <figcaption style="font-style:italic">Image 3.(b)</figcaption>
    </figure>
    <figure style= "border: 1px solid grey;border-radius:5px;">
    	3.Power amplifier <hr>
    <img src="C:\Users\lakhi\Documents\AE451A\Vibration analysis\power amplifier.png" alt="Power amplifier " style="zoom:75%;" />
        <figcaption style="font-style:italic">Image 3.(c)</figcaption>
    </figure>
    <figure style= "border: 1px solid grey;border-radius:5px;">
    	4.Stroboscope<hr>
    <img src="C:\Users\lakhi\Documents\AE451A\Vibration analysis\stroboscope.png" alt="Stroboscope" style="zoom:75%;" />
        <figcaption style="font-style:italic">Image 3.(d)</figcaption>
    </figure>
</div>



## 4. Measurements

<div style="display:inline-flex;text-align:center;">
    <figure>
    	<img src="C:\Users\lakhi\Documents\AE451A\Vibration analysis\AlBeam.png" alt="Aluminium Beam" style="zoom:75%;" />
        <figcaption style="font-style:italic">Image 4(a). Aluminium specimen</figcaption>
    </figure>
    <figure>
    	<img src="C:\Users\lakhi\Documents\AE451A\Vibration analysis\Composite Beam.png" alt="Composite Beam" style="zoom:85%;" />
        <figcaption style="font-style:italic">Image 4(b). Composite Specimen</figcaption>
    </figure>
</div>
1. **Forced vibration Aluminium specimen data**

| S.N. | Specimen Specification | Dimension  |
| ---- | ---------------------- | ---------- |
| 1.   | Length of the beam (L) | 1m         |
| 2.   | Width of the beam (b)  | 2.5 cm     |
| 3.   | Height of the beam(h)  | 0.35 cm    |
| 4.   | Modulus of rigidity(E) | 69 GPa     |
| 5.   | Density                | 2700 kg/m3 |

​								*Table 4(a). Forced vibration Aluminium specimen table*

2. **Free vibration Aluminium specimen data**

| S.N. | Specimen Specification | Dimension |
| ---- | ---------------------- | --------- |
| 1.   | Length of the beam (L) | 200 mm    |
| 2.   | Width of the beam (b)  | 10 mm     |
| 3.   | Height of the beam(h)  | 2 mm      |
| 4.   | Modulus of rigidity(E) | 69 GPa    |
| 5.   | Mass(M)                | 11.27 gms |

​								*Table 4(b). Free vibration Aluminium specimen data*

3. **Free vibration Composite specimen data**

| S.N. | Specimen Specification | Dimension |
| ---- | ---------------------- | --------- |
| 1.   | Length of the beam (L) | 200 mm    |
| 2.   | Width of the beam (b)  | 10 mm     |
| 3.   | Height of the beam(h)  | 5.7 mm    |
| 4.   | Modulus of rigidity(E) | 47.4 GPa  |
| 5.   | Mass(M)                | 27.75 gms |

​								*Table 4(c). Free vibration Composite specimen data*

## 5. Exeperimental Setup

The schematics of the experimental setup used for the demonstration of forced vibrations and  natural vibrations are shown in Image 5(a), Image 5(b) respectively.

<div style = "text-align:center;display: inline-flex;">
    <figure style = 'text-align:center'>
    	<img src="C:\Users\lakhi\Documents\AE451A\Vibration analysis\Forced vibration setup.png" style="zoom:100%;" />
        <figcaption style = "font-size:15px;font-style:italic">Image 5(a). Forced vibration</figcaption>
    </figure>
    <figure style = 'text-align:center'>
    	<img src="C:\Users\lakhi\Documents\AE451A\Vibration analysis\Free vibration setup.png" style="zoom:90%;" />
    <figcaption style = "font-size:15px;font-style:italic">Image 5(b). Natural vibration</figcaption>
    </figure>
</div>
## 6. Procedure

1. **Part (A): Forced vibrations in the free-free beam – Demonstration experiment**

   - Mount the beam on electrodynamic shaker.

   - Define force amplitude by turning the knob. Make sure not to give very large amplitude which would overheat the device. 

   - Gradually increase forcing frequency and observe the change in the amplitude of vibrations. 

   - When the forcing frequency matches with one of the natural frequencies, resonance will be  visually apparent (as shown in Figure 6(a)).

     <img src="C:\Users\lakhi\Documents\AE451A\Vibration analysis\Fig3.3.png" alt="Fig3.3" style="zoom:80%;" />

     ​					*Figure 6(a) : High amplitude of vibrations at fundamental frequency*

   - Switch off the lights and start stroboscope. Adjust the flickering light frequency such that the  beam appears stationary.

   - Perform minor adjustments on the Stroboscope and forcing frequencies to attain maximum amplitude. Note down this fundamental frequency. 

   - Repeat the process for the first three fundamental frequencies and record the mode shapes for  characterization. Representative second mode shape is shown in Figure 6(b). 

     <img src="C:\Users\lakhi\Documents\AE451A\Vibration analysis\Fig3.4.png" alt="Fig3.4" style="zoom:80%;" />
     
     ​												*Figure 6(b): Second mode shape*

2. **Part (B): Analyze natural vibrations in a cantilever beam by using accelerometer data**

   - Mount accelerometer at the end of the cantilever beam and connect it to data  acquisition system.

   - Provide initial end deflection to the beam and release the beam 
   - Once the vibration stabilizes (after a short initial interval) then begin recording the  accelerometer and strain gauge data. 
   - Stop recording the data before the amplitudes diminish.
   - Perform FFT on the recorded data and get the free vibration characteristics. 

## 7. Calculation

Equation for fundamental natural first, second and third frequency is,(using equation 3)
$$
w_1 = (\frac{1.875}{l})^2\sqrt{\frac{EI}{\rho A}}\\
w_2 = (\frac{4.694}{l})^2\sqrt{\frac{EI}{\rho A}}\\
w_3 = (\frac{7.85}{l})^2\sqrt{\frac{EI}{\rho A}}\\
$$

1. **For forced vibration**
   $$
   I = \frac{bh^3}{12} = \frac{0.025*0.0035^3}{12} = \space 8.9323*10^{-11}\space m^4\\
   A =\space b*h = 0.025*0.0035 = 8.75*10^{-5}\space m^2\\
   E = \space 69*10^{9}\space Pa\\
   \rho = \space 2700\space \frac{Kg}{m^3}\\
   l = 1m\\
   from\space table\space 4(a)
   $$
   First Fundamental frequency 
   $$
   w_1 = (\frac{1.875}{1})^2\sqrt{\frac{(8.9323*10^{-11})(69*10^{9})}{(2700)(8.75*10^{-5})}}\space s^{-1} = 17.9565\space Hz\\
   $$
   Second Fundamental frequency
   $$
   w_2 = (\frac{4.694}{1})^2\sqrt{\frac{(8.9323*10^{-11})(69*10^{9})}{(2700)(8.75*10^{-5})}}\space s^{-1} = 112.5398\space Hz\\
   $$
   similiarly we can solve for rest of the frequencies

   | Theoritical Frequency        | Value (in Hz) |
   | ---------------------------- | ------------- |
   | First Fundamental frequency  | 17.9565       |
   | Second Fundamental frequency | 112.5398      |
   
   2. **Free vibration**

      1. **For aluminium specimen**

         
         $$
         I = \frac{bh^3}{12} = \frac{0.01*0.002^3}{12} = \space 6.667*10^{-12}\space m^4\\
         A =\space b*h = 0.01*0.002 = 2*10^{-5}\space m^2\\
         E = \space 69*10^{9}\space Pa\\
         l = 0.2m\\
         \rho = \space \frac{M}{V} = \frac{M}{A*l} = \frac{11.27*10^{-3}}{(2*10^{-5})*0.2} =2817.5 \space \frac{Kg}{m^3}\\
         from\space table\space 4(b)
         $$
         First Fundamental frequency
         $$
         w_1 = (\frac{1.875}{1})^2\sqrt{\frac{(6.667*10^{-12})(69*10^{9})}{(2817.5)(8.75*10^{-5})}}\space s^{-1} = 251.1160\space Hz\\
         $$
         similiarly we can solve for rest of the frequencies
         
         | Theoritical  Frequency      | Value (in Hz) |
         | --------------------------- | ------------- |
         | First Fundamental frequency | 251.1160      |
   
         
         
      2. **For composite specimen**
         $$
         I = \frac{bh^3}{12} = \frac{0.01*0.0057^3}{12} = \space 1.5432*10^{-10}\space m^4\\
         A =\space b*h = 0.01*0.0057 = 5.7*10^{-5}\space m^2\\
         E = \space 47.4*10^{9}\space Pa\\
         l = 0.2m\\
         \rho = \space \frac{M}{V} = \frac{M}{A*l} = \frac{27.75*10^{-3}}{(5.7*10^{-5})*0.2} =2434.21 \space \frac{Kg}{m^3}\\
         from\space table\space 4(c)
         $$
         First Fundamental frequency 
         $$
         w_1 = (\frac{1.875}{1})^2\sqrt{\frac{(1.5432*10^{-10})(47.4*10^{9})}{(2434.21)(5.7*10^{-5})}}\space s^{-1} = 638.1707\space Hz\\
         $$
         similiarly we can solve for rest of the frequencies
         
         | Theoritical  Frequency      | Value (in Hz) |
         | --------------------------- | ------------- |
         | First Fundamental frequency | 638.17074     |
      

## 8. Data Analysis

1. **Forced Vibration Data Analysis**

   - <u>Acceleration vs Time graph</u>

     <img src="C:\Users\lakhi\Documents\AE451A\Vibration analysis\forcevibration acceleration vs time graph.png" alt="Acceleration vs Time graph" style="zoom:100%;border:1px solid gray;" />

   - <u>FFT of accelaration vs Frequency Graph</u>

     <img src="C:\Users\lakhi\Documents\AE451A\Vibration analysis\forcevibration fft vs freq graph.png" alt="FFT of accelaration vs Frequency Graph" style="zoom:100%;border:1px solid gray;"/>

     **First Fundamental frequency = 8.016 Hz**

     **Second Fundamental frequency= 53.10 Hz**

     

   - <u>Strain vs Time Graph</u>

     <img src="C:\Users\lakhi\Documents\AE451A\Vibration analysis\forcevibration strain vs time graph.png" alt="Strain vs Time Graph" style="border: 1px solid gray;" />

   

2. **Free Vibration Data Analysis**

   1. <u>Aluminium Beam</u>

      - <u>Acceleration vs Time graph</u>

        <img src="C:\Users\lakhi\Documents\AE451A\Vibration analysis\freevibration al acceleration vs time graph.png" alt="Acceleration vs Time graph" style="zoom:100%;border: 1px solid gray;" />

      - <u>FFT of accelaration vs Frequency Graph</u>

        <img src="C:\Users\lakhi\Documents\AE451A\Vibration analysis\freevibration al fft vs freq graph.png" alt="FFT of accelaration vs Frequency Graph" style="zoom:100%;border: 1px solid gray;" />

        **First Fundamental frequency = 14.02 Hz**

      - <u>Strain vs Time Graph</u>

        <img src="C:\Users\lakhi\Documents\AE451A\Vibration analysis\freevibration al strain vs time graph.png" alt="Strain vs Time Graph" style="zoom:100%;border: 1px solid gray;" />

   2. <u>Composite Beam</u>

      - <u>Acceleration vs Time graph</u>

        <img src="C:\Users\lakhi\Documents\AE451A\Vibration analysis\freevibration cm acceleration vs time graph.png" alt="Acceleration vs Time graph" style="zoom:100%;border: 1px solid gray;" />

      - <u>FFT of accelaration vs Frequency Graph</u>

        <img src="C:\Users\lakhi\Documents\AE451A\Vibration analysis\freevibration cm fft vs freq graph.png" alt="FFT of accelaration vs Frequency Graph" style="zoom:100%;border: 1px solid gray;" />

        **First Fundamental frequency = 30.06 Hz**
   
      - <u>Strain vs Time Graph</u>
      
        <img src="C:\Users\lakhi\Documents\AE451A\Vibration analysis\freevibration cm strain vs time graph.png" alt="Strain vs Time Graph" style="zoom:100%;border: 1px solid gray;" />

## 9. Error Analysis

$$
\%\space Error\space = \space \frac{|Fth - Fexp|}{Fth}*100\%
$$

1. **Forced Vibration**

| Mode                         | Theoritical Frequency | Experimental Frequency | % Error |
| ---------------------------- | --------------------- | ---------------------- | ------- |
| First Fundamental frequency  | 17.9565               | 8.016                  | 55.34   |
| Second Fundamental frequency | 112.5398              | 53.10                  | 52.81   |

2. **Free Vibration**

   - **Aluminium Beam**

   | Mode                        | Theoritical Frequency | Experimental Frequency | % Error |
   | --------------------------- | --------------------- | ---------------------- | ------- |
   | First Fundamental frequency | 251.1160              | 14.02                  | 94.41   |

   - **Composite Beam**

   | Mode                        | Theoritical Frequency | Experimental Frequency | % Error |
   | --------------------------- | --------------------- | ---------------------- | ------- |
   | First Fundamental frequency | 638.17074             | 30.06                  | 95.29   |

## 10. Results and Discussion

- Beam deflection increase at its natural frequency
- First peak in FFT graph shows specimen first overtone frequency
- We are getting error in theoritical and experimental data 

## 11. Source of Error and Precautions

1. <u>**Source of Error**</u>
   - Calibration error 
   - Specimen dimension measuring error
   - Accelerometer or Strain gauge sampling  efficiency
2. **Precautions**
   - Check equipments and calibrate properly
   - Don't touch beam during oscillation
   - Don't increase frequency rapidly in function generator, it can overheat shaker.

