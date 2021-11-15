<h1 align ="center">Indian Institute of Technology Kanpur</h1>





<h1 align ="center">AE451A</h1>

<h3 align = "center">Experiments in Aerospace Engineering - III</h3>





<h3 align = "center">Experiment No. 6</h3>

<h1 align = "center">Flow over a Circular Cylinder</h1>





### Submitted By:

Ankit Lakhiwal (180102)

[ankitl@iitk.ac.in](To:ankitl@iitk.ac.in)

Aerospace Engineering Department, IIT Kanpur

September 27, 2021

<hr>

## 1. Objective 
-  Measure velocity proﬁle, both mean and ﬂuctuating component, in the turbulent wake behind a circular cylinder using hot-wire anemometer.
- Study the dependence of shedding frequency in the Karman vortex street of the circular cylinder wake 0n Reynolds number.
## 2. Introduction and theory

> #### **Flow Seperation**

Consider a fluid flow in which the static pressure increases instead of decreasing. This will lead to deceleration of the fluid. The effect of this is an abrupt increase in the pressure gradient in the opposite direction. This is known as the adverse pressure gradient.

This figure illustrates a boundary layer in which the flow has decelerated and completely reversed the direction of flow due to adverse pressure gradient.

![flow seperation](https://miro.medium.com/max/700/1*es9vMruppWsPHfaj2nI_RQ.png)

Flow separation is also known as boundary layer separation and as the name suggests it is the detachment of the boundary layer from a surface. The detachment of boundary layers is mainly caused due to the adverse pressure gradient. In adverse pressure gradient the fluid in continuously decelerated and at one point it becomes zero and reverses its direction. This reversal leads to flow separation. The reversed flows causes recirculation in the low-pressure region. The point where the velocity of the fluid layer becomes zero is the point of separation, this is where the adverse pressure gradient and the boundary layer detachment.

> #### **Karman Vortex Street**

<img src="https://upload.wikimedia.org/wikipedia/commons/f/fb/Karmansche_Wirbelstr_kleine_Re.JPG" alt="karman voretx" style="zoom:100%;" />



![karman vortex begining](https://miro.medium.com/max/700/1*6jQTQK0lb1hC_dl_0L4XIQ.png)

we can see that there is boundary layer detachment i.e., flow separation due to adverse pressure gradient. The decrease in the momentum of the flow is the primary cause of the adverse pressure gradient. Since the bluff body is sym-metric in nature, the flow separation is almost identical on the top half of the sphere and bottom half of the sphere. The adverse pressure gradient is observed in the downstream or the wake region of the sphere. The pressure variations along the boundary layer are generated predominately due to the curved surface of the sphere. Vortices are also generated alongside recirculation in the region of reversed flow. These vortices start to swirl in a repeating manner. These low-pressure alternating vortices tend to repeat at a certain frequency, this is called the frequency of vortex shedding.

## 3. Equipment's

<div style="columns:2;">
    <ol>
        <li> Wind tunnel </li>
        <li>Digital diffrential manometer</li>
        <li>Hot wire probe</li>
		<li>Circular cylinder (dia. 6 mm and 1.6 mm)</li>
        <li>Height gauge</li>
        <li>NI aquisition card</li>
        <li>computer</li>
    </ol>
</div>

## 4. Procedure and measurements

> ### **Part A**

1. Study the experimental set-up including each and every component with speciﬁcation.
2. Study the circuit diagram for a constant temperature hot wire circuit.
3. Mount the hot-wire probe in the traversing mechanism and make the necessary signal connection.
4. Make a block diagram of the experimental set up.
5. Calibrate hot wire probe in the free stream without any model in the tunnel.
6. Use a rough cylinder model to generate turbulent wake
7. At one free stream wind speed at a stream-wise station, x, measure velocity proﬁles, both mean and ﬂuctuating component, in the turbulent wake. The origin of x coordinate is at the center of the cylinder and it is increasing in the stream-wise direction.
8. Plot velocity proﬁles, both mean and rms, in normalized forms.

​	**Cylinder Diameter : 6 mm**

<hr>

> ### **Part B**

1. You are provided with four circular cylinders of different diameters. Measure the diameters with the help of a digital Vernier.
2. Mount the hot wire in the near wake (about 3 diameters) of the circular cylinder. Turn the wind tunnel on. At an appropriate wind speed the hot wire signal will show a sine wave. Note the frequency of the sine wave. This corresponds to the frequency of the vortex shedding.
3. Increase the Reynolds number and note the variation in the shedding frequency.
4. Calculate Strouhal number, $S = \frac{fd}{u}$, and Reynolds number. Plot results as S = f (Re).

**cylinder diameter : 1.6 mm**

## 5. Data analysis

> ### **Part A**

1. **Calibration Data and Graph**

<div style="display:flex;justify-content:center;">
    <img src="https://github.com/lakhiwal007/AE451A/blob/main/Flow%20over%20a%20Circular%20Cylinder/caliTable.png" alt="caliTable" style="zoom:100%; margin-right:10px;" />
    <img src="https://github.com/lakhiwal007/AE451A/blob/main/Flow%20over%20a%20Circular%20Cylinder/coeffcurve.png" alt="coeff curve" style="zoom:100%;border:2px solid black;" />
</div>

$$
log(E^2-E_0^2)\space =\space nlog(U) + log(B)
$$

$$ {align*}
E_0^2 = A &=& 4.4521\\
B &=& 1.04233\\
n &=& 0.727256
$$ {align*}



2. **Y/d vs U_mean/U and U_rms/U Graph**

<img src="https://github.com/lakhiwal007/AE451A/blob/main/Flow%20over%20a%20Circular%20Cylinder/uandyNormalize.png" style="zoom:100%;border:1px solid;" />

<hr>

> ### **Part B**

1. **FFT Graph**

<img src="https://github.com/lakhiwal007/AE451A/blob/main/Flow%20over%20a%20Circular%20Cylinder/fftt.png" alt="fft image" style="zoom:100%;" />

2. **Strouhal no. vs Reynolds no. Table and Graph**


$$
Strouhal\space No. \space (S) = \space \frac{fd}{u}\\
$$

$$
& Reynols\space No.\space (Re) = \frac{ud}{\nu}\\
& \nu = kinematic\space viscocity\space at\space sea \space level\space of\space air\\
&= 1.48*10^{-5}\space \frac{m^2}{s}
$$



> | S.No. | Frequency | Diameter(mm) | Velocity(m/s) | Strouhal No. (St) | Reynolds No. (Re) |
> | ----- | --------- | ------------ | ------------- | ----------------- | ----------------- |
> | 1.    | 346.092   | 1.6          | 1.334         | 0.4150755         | 540.81081081      |
> | 2.    | 486.0972  | 1.6          | 1.728         | 0.45009           | 700.54054054      |
> | 3.    | 906.1812  | 1.6          | 2.931         | 0.49467415        | 1188.24324324     |

<img src="https://github.com/lakhiwal007/AE451A/blob/main/Flow%20over%20a%20Circular%20Cylinder/StvsRe.png" alt="St vs Re" style="zoom:100%;border:1px solid;" />



## 6. Questions

> ### Part A

1. How does constant temperature hot-wire anemometer work?

   **Ans.** A hot-wire anemometer is a thermal transducer which has been widely used to measure instantaneous flow velocity. The use of the hot-wire anemometer permits instantaneous flow velocity to be calculated from electric voltage measurements. The advantage of hot-wire anemometry is associated with its very high spatial resolution and excellent frequency response characteristics. In most cases, the probe-stem is perpendicularly aligned with the mainstream direction of flow. First the anemometer is calibrated using King’s law and then we use the coefficients to get velocity data.

   <img src="https://ars.els-cdn.com/content/image/3-s2.0-B9780128097311000046-f04-03-9780128097311.jpg" alt="hot wire" style="zoom:80%;" />

2. How do you calculate mean and rms velocity components from hot wire signal?

   **Ans.** Mean velocity is the average of the velocity data obtained after converting voltage data from hot wire anemometer into velocities using King’s law. To calculate rms velocity first we have to compute the fluctuating part of the velocities. Fluctuating component can be obtained by subtracting U by Umean. The square root of squared average of the fluctuating components of velocity gives the rms velocity.

3. What is the nature of the hot-wire signal in the free stream?

   **Ans.** In free stream since there is no disturbances present in front of the flow. The fluctuating components of the velocity will be negligible and the velocity will remain constant at a point.

4. What do you understand by the intermittency in a turbulent wake?

   **Ans.**  Intermittency is the flow regime which lies in between laminar and turbulent region or it can be defined as a scale to measure the transfer of flow from laminar to turbulent. For a fully laminar flow the value of intermittency is 0, while for turbulentit is 1.

> ### Part B

1. What do you observe when the hot wire probe is moved across the cylinder wake? Explain the reason.

   **Ans.** We see there is more loss of momentum in wake region close to cylinder vertically.

2. Can you use this method to measure low wind speed? Explain.

   **Ans.** Yes, we can use this for measuring low velocity because hot wire anemometer is very sensitive to rate of heat loss since its resistance changes.

3. Sketch the ﬂow ﬁeld on a circular cylinder as a function of Reynolds number. Start with the inviscid ﬂow. Comment on drag and other characteristics.

   **Ans.** <img src="https://github.com/lakhiwal007/AE451A/blob/main/Flow%20over%20a%20Circular%20Cylinder/flow.jpg" alt="flow" style="zoom:15%;display:flex;" />

4. What happens to the shedding frequency when the hot wire probe is moved across the cylinder near wake? Explain.

   **Ans.** When a probe is moved across the cylinder wake then we observe some fluctuations in the signal. As it is moved further downwards in the wake the fluctuations will decrease and then it will again increase as it now showsfluctuations in downward part.
