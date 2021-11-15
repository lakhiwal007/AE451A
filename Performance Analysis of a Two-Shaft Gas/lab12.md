<h2 align ="center">Indian Institute of Technology Kanpur</h2>

<h1 align ="center">AE451A</h1>

<h2 align = "center">Experiments in Aerospace Engineering - III</h2>



<h2 align = "center">Experiment No. 12</h2>

<h1 align = "center">Performance Analysis of a Two-Shaft Gas Turbine Engine</h1>



### Submitted By:

Ankit Lakhiwal (180102)

[ankitl@iitk.ac.in](To:ankitl@iitk.ac.in)

Aerospace Engineering Department, IIT Kanpur

November 15, 2021



## 1. Objective

The objective is to understand the operation and evaluate the performance of a power generating gas turbine engine, and obtain the component efficiencies.

## 2. Introduction and theory

<img src="https://github.com/lakhiwal007/AE451A/blob/main/Performance%20Analysis%20of%20a%20Two-Shaft%20Gas/controlPanel.png" alt="control panel" style="zoom:50%;" />

​													*Figure 1. . Two shaft gas turbine engine set-up.*

To investigate the performance of a gas turbine, a two-shaft turbocharger based gas turbine engine set-up, GT85-2, Gilbert, Gike & Gordan Ltd. England is used, see Fig. 1. The engine includes three processes, namely, compression, combustion and expansion. 

The compression is carried out by a single stage centrifugal compressor operating at speeds upto 90,000 rpm with pressure ratio upto 2.2. The compressor is driven by a single stage turbine whose only function is to provide power to the compressor. 

The discharge from the compressor is fed to the combustion chamber where it is used to burn aviation turbine fuel (ATF) with stoichiometric air/fuel ratio of approximately 15:1. 

The combustion products at the combustor exit, at temperatures upto 700 C are fed to the single stage turbine powering the compressor and then to the single stage power turbine (to generate mechanical power which is absorbed by the load dynamometer). The net power output of the gas turbine set-up goes upto 7 kW. 

The discharge from the power turbine is then exhausted to the atmosphere.

## 3. Checklist Before Starting 

1. Check that the water supply is ON for cooling purpose. 
2. Check that the oil supply pressure and temperature is appropriate. 
3. Make sure there is sufficient fuel for a complete test run

## 4. Procedure

1. Before starting the experiment, familiarize yourself with various components of the test set-up as well as the instrument panel.
2. Learn the starting procedure and operation of the test set with the help of “Technical Handbook” provided by the manufacturer and the Laboratory staff. Do not operate the test set-up in the absence of a lab staff member. 
3. Turn ON the main switch and after that Turn ON the water supply and oil supply switch.
4. Start only one electric fan. When fan has started, inject alcohol into the combustion chamber and turn ON the spark plug. Hold the alcohol injection and spark plug switch in ON position until combustion chamber temperature reaches above 100˚C. Once the combustion chamber temperature reachees above 100˚C release the switch (Turn OFF). 
5. When the 1st turbine speed is approximately equal to 50,000 rpm, turn OFF the electric fan and start the experiment. 
6. Note down the readings at different rpms. 
7. The operational speed range of the gas turbine set-up is given below and must not be exceeded.

> Gas Generator speed: 50,000 < N1 < 90,000 rpm. 
>
> Power turbine speed: 5,000 < N2 < 40,000 rpm.

## 5. Calculation

<img src="https://github.com/lakhiwal007/AE451A/blob/main/Performance%20Analysis%20of%20a%20Two-Shaft%20Gas/schematic.png" alt="schematic" style="zoom:75%;" />

<div style = "columns:2">
   	<li>Station a - Ambient conditions and fan inlet</li>
    <li>Station 1 - Fan exit and compressor inlet</li>
    <li>Station 2 - Compressor exit and combustor inlet </li>
    <li>Station 3 - Combustor exit and turbine inlet </li>
    <li>Station 3C - Turbine exit </li>
    <li>Station 4 - Power turbine inlet </li>
    <li>Station 5 - Power turbine exit</li>
</div>

1. **Units Conversion and other assumptions:**
$$
𝑚𝑎(𝑘𝑔𝑠)=\frac{0.9597×√Δ𝑃×√𝑃1}{√𝑇1}\\
  𝑚𝑓(𝑘𝑔𝑠)=\frac{𝑚𝑓(𝐿𝑃𝐻)×𝜌𝑓𝑢𝑒𝑙}{3600×1000}
$$
  Where, 𝜌𝑓𝑢𝑒𝑙=840 𝑘𝑔/𝑚3 𝑎𝑛𝑑
  ΔP is pressure difference across the fan.

  T1 is in Kelvin.
  P1 is in bar and Δ𝑃 is in mbar. 

  𝛾𝑐𝑜𝑙𝑑=1.4 and 𝛾ℎ𝑜𝑡 = 1.33
  𝐶𝑃(𝑐𝑜𝑙𝑑) = 1005 (𝐽/𝑘𝑔.𝐾) 𝑎𝑛𝑑 𝐶𝑃(ℎ𝑜𝑡) = 1150 (𝐽/𝑘𝑔.𝐾)

2. **Ambient Conditions:**
    Pressure (Pamb) = measured from barometer in lab or assume 1.01 bar
    Temperature (Tamb) = measured from thermometer in lab

3. **Compressor Inlet Pressure:**
    P1 = Pamb + ΔP

4. **Compressor Pressure Ratio (P2/P1):**
    Since the measured value is gauge pressure, we add ambient pressure to get the absolute pressure.

5. **Compressor Efficiency:**
   $$
   \eta_c = (\frac{(\frac{P_2}{P_1})^{\frac{\gamma_{cold} - 1}{\gamma_{cold}}}{-1}}{\frac{T_2}{T_1} - 1})
   $$

6. **Turbine Efficiency :**
   $$
   \eta_c = (\frac{1- \frac{T_{3C}}{T_3}}{1 - (\frac{P_{3C}}{P_3})^{\frac{\gamma_{hot} - 1}{\gamma_{hot}}}})
   $$
   
   
   
   
7. **Power Turbine Exit Pressure:**
   $$
   P5 = P4\space – \space\Delta P45
   $$
   ΔP45 is pressure drop in the power turbine (entry – exit)

8. **Global Equivalence Ratio:**
   $$
   \phi = \frac{(\frac{A}{F})_{stoich}}{(\frac{A}{F})}
   $$
   Air/Fuel ratio is ($\frac{A}{F} =\frac{m_a}{m_f}$) and Stoichiometric Air to Fuel ratio can be calculated using the stoichiometric equation for the combustion of ATF (use C12H26 to simulate ATF composition)

9. **Power:**
   $$
   Net\space Power = (m_a + m_f)*C_{p}(hot)*(T_4 - T_5)
   $$
   
10. **Overall Efficiency:**
    $$
    \eta_0 = \frac{(m_a + m_f)*C_{p}(hot)*(T_4 - T_5)}{m_f*Q(LCV)}
    $$
    Assume lower calorific value for ATF [Q(LCV)] is 44.5 MJ/kg.

## 6. Data Analysis

> **Data table**

![data table](https://github.com/lakhiwal007/AE451A/blob/main/Performance%20Analysis%20of%20a%20Two-Shaft%20Gas/data_table.png)

> **Unit Converted Data Table**

![unit cnvrtd data table](https://github.com/lakhiwal007/AE451A/blob/main/Performance%20Analysis%20of%20a%20Two-Shaft%20Gas/unitConverted_data_table.png)

## 7. Results and Discussion

![results table](https://github.com/lakhiwal007/AE451A/blob/main/Performance%20Analysis%20of%20a%20Two-Shaft%20Gas/results_table.png)

<img src="https://github.com/lakhiwal007/AE451A/blob/main/Performance%20Analysis%20of%20a%20Two-Shaft%20Gas/effPlot.png" alt="efficiency plot"  />

![](https://github.com/lakhiwal007/AE451A/blob/main/Performance%20Analysis%20of%20a%20Two-Shaft%20Gas/phiAndPowerPlot.png)

> The following trends we can see as the fuel flow rate increases :
>
> - compressor efficiency increases
> - turbine efficiency decreases
> - overall efficiency decreases
> - Power increrase

## 8. Precautions

1. Do not operate unless a lab technician or teaching assistant is present. 
2.  NEVER exceed the maximum fuel flow rate limit of 12 LPH. 
3. While increasing the fuel supply, do so slowly, in the stipulated increments only. 
4. Keep in mind the maximum power turbine speed is 40,000 rpm, if it exceeds 40,000 rpm give the load by using load dynamometer. 
5. During the experiment, the gas turbine components will get very hot. Do not touch any part of the gas turbine during the experiment.
6. Stay well away from the exhaust of the gas turbine during operation.

## 9. References

[Lab 12 Data Anaylsis Jupyter Notebook](https://colab.research.google.com/drive/1aRUKFnkyDTHUFXw_w2kp9qHcCdeKMQzQ#scrollTo=8D7zhf0slGRt)
