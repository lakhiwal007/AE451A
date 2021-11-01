<h2 align ="center">Indian Institute of Technology Kanpur</h2>



<h1 align ="center">AE451A</h1>

<h2 align = "center">Experiments in Aerospace Engineering - III</h2>





<h2 align = "center">Experiment No. 10</h2>

<h1 align = "center">PERFORMANCE ANALYSIS OF A TURBOJET ENGINE</h1>



### Submitted By:

Ankit Lakhiwal (180102)

[ankitl@iitk.ac.in](To:ankitl@iitk.ac.in)

Aerospace Engineering Department, IIT Kanpur

November 1, 2021



## 1. Objective

The objective is to understand the operation and evaluate the performance of a turbojet engine, at different operating conditions.

## 2. Introduction and theory

<img src="C:\Users\lakhi\Documents\AE451A\Performance analysis of a Turbojet\Screenshot_1.png" alt="turbojet" style="zoom:50%;" />

<img src="http://cdn.arstechnica.net/wp-content/uploads/2015/02/2000px-Jet_engine.svg_.png" style="zoom:35%;" />

The ambient air is drawn in, and is first brought to a higher pressure in the single-stage radial compressor. In the downstream combustion chamber, fuel is added to the compressed air and the resulting mixture is combusted. The temperature and flow velocity of the gas increases. The gas flows out of the combustion chamber into the single-stage axial turbine and discharges a portion of its energy to the turbine. This turbine drives the compressor. In the propelling nozzle, the partially expanded and cooled gas expands to ambient atmospheric pressure and the gas accelerates to high speeds.
The high-speed gas outflow generates the thrust. In order to reduce the outlet temperature, the exhaust gas stream is mixed with the ambient air in a mixing pipe. The gas turbine is started fully automatically with the aid of an electric starter. Between the compressor and the turbine is the annular combustion chamber. The movable platform, with a force sensor, enables measurement of the thrust.
The speed, temperatures, static pressures and mass flow rates of the air and fuel are recorded using appropriate sensors. The measured values can be read on digital displays.

## 3. Equipment's

<div style = "columns:2;">
    <ul>
        <li>turbojet engine</li>
        <li>thermocouples</li>
        <li>ressure sensor</li>
        <li>spark plug</li>
        <li>load cell</li>
        <li>fuel</li>
        <li>control panel</li>
    </ul>
</div>

## 4. Checklist Before Starting

1. Check fuel lines for air bubbles or blockages.
2. Check that fuel tank vent is unobstructed
3. Make sure there is sufficient fuel for a complete test run.
4. Set throttle trim and turbine (Aux channel) mode switch to OFF
5. Lift the turbine desk at the front end to enable residual fuel on turbine to come out.

## 5. Procedure

1. Set the throttle trim switch to ON and set throttle lever to IDLE (minimum).
2. Switch on the ET796 at the master switch and set turbine (Aux channel) to RUN.
3. The 3 LED lights will light up in sequence. Start the automatic starting process by fully opening the throttle lever.
4. The starter motor brings the turbine to starting speed. The glow plug is activated and auxiliary fuel is given for ignition. Ignition is identified by a rise in temperatures seen on the display panel.
5. After a short time, bring the throttle to IDLE position and being the experiment.
6. Slowly vary the rpm of the engine from 40,000 to 100,000, in steps of 10,000 rpm.
7. At each step, record all the parameters displayed in the digital display panel. After reaching 100,000 rpm and recording all the required data the experiment is complete.
8. After completing the experiment, turn off the turbine (Aux channel) mode switch to AUTO OFF. To cool the turbine, the starter motor continues running until a temperature of below 100 oC is reached. Once the turbine has cooled down, switch the turbine (Aux channel) mode switch to OFF.

## 6. Calculation

>  **Units Conversion and other assumptions:**

1. <u>**Mass flow rate**</u>

$$
m_a(\frac{kg}{s})=\frac{m_a(\frac{Ltr}{s})×ρ_{ambient}}{1000}
$$

$$
m_f(\frac{kg}{s})=\frac{m_f(\frac{Ltr}{hr})×ρ_{fuel}}{3600*1000}
$$




​						Where, 	$𝜌_{𝑎𝑖𝑟}=1.2\space 𝑘𝑔/𝑚3$  and  $𝜌_{𝑓𝑢𝑒𝑙}=840\space 𝑘𝑔/𝑚3$

2. <u>**Temprature **</u>
   $$
   T (K) = T (\degree{C}) + 273
   $$
   
3. <u>**Pressure**</u>
   $$
   Pressure (kPa) = Pressure (bar) × 100
   $$
   ​	$\gamma_{𝑐𝑜𝑙𝑑} = 1.4$  and  $\gamma_{hot} = 1.33$
   ​	$𝐶_{𝑃_{𝑐𝑜𝑙𝑑}} = 1005 \space \frac{𝐽}{𝑘𝑔.𝐾}$ and  $𝐶_{𝑃_{hot}} = 1150\space \frac{𝐽}{𝑘𝑔.𝐾}$
   
   
   
   <img src="C:\Users\lakhi\Documents\AE451A\Performance analysis of a Turbojet\schematic turbojet.png" style="zoom:60%;" />

> **Ambient Conditions:**

Pressure ($P_{01}$) = measured from barometer in lab or assume **101.325 kPa**

Temperature ($T_{01}$) (K) = measured from thermometer in lab = **287 K**

> **Compressor Pressure Ratio (P02/P01):**

Compressor Exit Pressure (P02) (kPa) = P01 + [P02 (bar)× 100]

Since the measured value is gauge pressure, we add ambient pressure to get absolute pressure. Also, convert from bar to kPa by

multiplying 100.

Knowing P02 and P01 (P01 is the same as Pambient), we can now estimate the compressor pressure ratio, P02/P01.

Combustor Exit Pressure (P03) (kPa) = P02 × 0.95

Assuming that there is a 5% pressure loss in the combustor, we can estimate combustor exit pressure from the compressor exit

pressure.

> **Compressor Efficiency ($\eta_c$):**

$$
\eta_c = \frac{(\frac{P_{02}}{P_{01}})^{(\frac{\gamma -1 }{\gamma})}-1}{\frac{T_{02}}{T_{01}}-1}
$$

> **Global Equivalence ratio ($\phi_g$):**

$$
Global\space Equivalence\space Ratio = \frac{𝐴𝑐𝑡𝑢𝑎𝑙 (\frac{𝐹𝑢𝑒𝑙}{𝐴𝑖𝑟})}{𝑆𝑡𝑜𝑖𝑐ℎ𝑖𝑜𝑚𝑒𝑡𝑟𝑖𝑐 (\frac{𝐹𝑢𝑒𝑙}{𝐴𝑖𝑟})}
$$

$Actual (\frac{𝐹𝑢𝑒𝑙}{𝐴𝑖𝑟})=\space \frac{𝑚_𝑓}{𝑚_𝑎} $ and $Stoichiometric (\frac{air}{fuel})= \space 15$ for ATF. 

It can be calculated using the stoichiometric equation for the combustion of ATF (use C12H26 to simulate ATF composition).

> **Specific Thrust:**

$$
𝑆𝑝𝑒𝑐𝑖𝑓𝑖𝑐 𝑇ℎ𝑟𝑢𝑠𝑡=\space \frac{𝑇ℎ𝑟𝑢𝑠𝑡 (𝑁𝑒𝑤𝑡𝑜𝑛𝑠)}{𝑇𝑜𝑡𝑎𝑙\space 𝐼𝑛𝑡𝑎𝑘𝑒\space 𝐴𝑖𝑟\space 𝐹𝑙𝑜𝑤 (\frac{𝑘𝑔}{𝑠})}
$$

> **Thrust Specific Fuel Consumption (TSFC):**

$$
𝑇𝑆𝐹𝐶 =\space \frac{𝐹𝑢𝑒𝑙\space 𝐶𝑜𝑛𝑠𝑢𝑚𝑝𝑡𝑖𝑜𝑛 (\frac{𝑘𝑔}{𝑠})}{𝑇ℎ𝑟𝑢𝑠𝑡 (𝑁𝑒𝑤𝑡𝑜𝑛𝑠)}
$$

> **Mach Number**

$$
exit\space velocity (U_e)  = \frac{Thrust}{\dot{m_a} + \dot{m_f}}\\
speed\space of\space sound (a) = \sqrt{\gamma_{hot}*R*T_{04}}\\
M = U_e/a
$$

## 7. Data analysis

> **Data Table (Converted Units )**

<img src="C:\Users\lakhi\Documents\AE451A\Performance analysis of a Turbojet\cnvrtd unit table.png" alt="table" style="zoom:90%;" />

> **Parameters Table**

<img src="C:\Users\lakhi\Documents\AE451A\Performance analysis of a Turbojet\res_df.png" alt="results table" style="zoom:90%;" />

## 8. Results and discussion

> **Parameters Plots**

<img src="C:\Users\lakhi\Documents\AE451A\Performance analysis of a Turbojet\parameters_plots.png" alt="parametrs plots" style="zoom:100%;border:1px solid;" />

> **Temprature trends with RPM**

<img src="C:\Users\lakhi\Documents\AE451A\Performance analysis of a Turbojet\temp_trends.png" alt="Temprature trends with RPM" style="zoom:100%;border:1px solid;" />

## 9.Precautions

1. Do not operate unless a lab technician or teaching assistant is present.
2. NEVER exceed the maximum RPM limit of 110,000 RPM.
3. While increasing RPM, do so slowly, in the stipulated increments only.
4. During the experiment, the gas turbine components will get very hot. Do not touch any part of the gas turbine during the experiment.
5. Stay well away from the exhaust of the gas turbine during operation.

## 10. References

- [Jupyter Notebook of data analysis](https://github.com/lakhiwal007/AE451A/blob/main/Performance%20analysis%20of%20a%20Turbojet/lab10.ipynb)
