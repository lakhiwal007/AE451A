<h2 align ="center">Indian Institute of Technology Kanpur</h2>

<h1 align ="center">AE451A</h1>

<h2 align = "center">Experiments in Aerospace Engineering - III</h2>



<h2 align = "center">Experiment No. 11</h2>

<h1 align = "center">Performance Analysis of a Two Stage Axial Fan</h1>



### Submitted By:

Ankit Lakhiwal (180102)

[ankitl@iitk.ac.in](To:ankitl@iitk.ac.in)

Aerospace Engineering Department, IIT Kanpur

November 8, 2021



## 1. Objective

1. To obtain and understand the characteristics of an axial fan.
2. To plot and understand the pressure profiles at different points across an axial fan.

## 2. Introduction and theory

![image-20211106132014620](C:\Users\lakhi\AppData\Roaming\Typora\typora-user-images\image-20211106132014620.png)

The axial flow fan test facility consists of two stage axial fan, along with a switch cabinet that will display all relevant operating data, see Figure 1. Each axial rotor has its own motor and speed of each motor can be regulated independently from the switch cabinet using potentiometers. Experiments can be conducted with single rotor also. A movable pipe section component is located directly after the intake pipe in the experimental setup which contains rotor 1. If experiments are to be carried out with only one stage, the movable pipe section can be pushed to the side so that the intake pipe can be screwed directly onto the pipe section containing rotor 2.
A throttle valve is fitted in the pipe section with rotor 2. It can be used to regulate the mass flow and discharge pressure through the compressor. The throttle valve is operated using a lever, which is secured with a wing bolt to prevent unintentional adjustment. See Figure 1 for more details. Pressure measuring connections are fitted at the key points for pressure measurements in the intake pipe, which the user can connect to differential pressure displays in the system (see Figure 2). The holes feed into annular pipes, which are designed to rule out falsification of the measured pressures. The flow rate through the pipe is measured using the static pressure measurement at the inlet. Finally, there are sensors for measuring the air temperature at various locations.

![image-20211106132045308](C:\Users\lakhi\AppData\Roaming\Typora\typora-user-images\image-20211106132045308.png)

The switch cabinet for the system is divided into two sections. Left-hand section contains digital displays for differential pressures, temperatures, air flow rate, nulling yaw probe (position and angle). It also contains the connection for PC data acquisition. The sensor connections are located on the side of the control cabinet. Right hand side of the cabinet contains emergency stop switch and an ON/OFF button for the fan. The torque and speed of the fan are also shown on the digital display. On the right hand side of the cabinet are two sockets, which can be used to connect additional devices (e.g. a PC).

## 3. Experimental Procedure

To obtain the compressor characteristics of an axial compressor

1. Set the throttle valve to minimum resistance position, by rotating the lever.
2. Rotate the RPM control switch of both the rotors till the desired RPM is reached.
3. Torques and pressures are measured using various sensors and the readings are displayed in the displays located in the switch cabinet. This corresponds to the first set of readings, note down these readings.
4. Slowly rotate the lever to certain extent to increase the flow resistance (and reduce the mass flow rate), keeping the RPM constant.
5. Note down the torque and pressure readings for this setting as well. Keep repeating this process so that you get 5-8 readings.
6. Then repeat the same experiment at different RPM (at least three different RPMs). The RPMs for each group will be defined by the instructor.
  Following readings should be noted:
  1. Pressure at various points (P1 – P7).
  2. Air flow rate (m3/s) and RPM from the switch cabinet.
  3. Temperatures at various points (T1 – T3).
  4. Torque in N-m from the switch cabinet.

## 4. Calculation

Pa = 101325 Pascal

$\rho$ = 1.225 kg/m3

Area = $\frac{\pi*D^2}{4}\space (m^2)$

$\dot{m} = \dot{Q}*\rho \space (Kg/s)$

Velocity = $\frac{\dot{Q}}{Area} \space (\frac{m}{s})$

P0 = Pa - $\frac{1}{2}*\rho*V^2 \space (Pa)$

N : RPM, T : Torque (N.m)

Power = $\frac{N1*T1 + N2*T2}{60} \space {Watt}$

## 5. Data analysis

> **Experimental Data Table**

![table](https://github.com/lakhiwal007/AE451A/blob/main/Performance%20Analysis%20of%20a%20Two%20Stage%20Axial/table_data.png)

> **Calculated Data Table**

![result table](https://github.com/lakhiwal007/AE451A/blob/main/Performance%20Analysis%20of%20a%20Two%20Stage%20Axial/result_table.png)

## 6. Results

> 1. **overall pressure ratio (P7/P0) vs. mass flow rate (𝑚̇) for the three different RPM (N) settings**

![](https://github.com/lakhiwal007/AE451A/blob/main/Performance%20Analysis%20of%20a%20Two%20Stage%20Axial/p7byp0vsmdot.png)

> 2. **Pressure profile across different points at 1104 RPM and $\dot{Q} = 0.89$**

![](https://github.com/lakhiwal007/AE451A/blob/main/Performance%20Analysis%20of%20a%20Two%20Stage%20Axial/pressureatDifferntPorts.png)

> 3. **At 1104 RPM, $\frac{Q*\delta P}{Power}$ vs Volume flow rate ($\dot{Q})$**

![](https://github.com/lakhiwal007/AE451A/blob/main/Performance%20Analysis%20of%20a%20Two%20Stage%20Axial/ratiovsqdot.png)

## 7. Discussion

1. Ratio of P7 and P0 are nearly 1 and decrease with mass flow rate is increasing 
2. Across the flow, pressure increase from inlet to exit of the chamber.
3. Ratio Q*dP/Power increases with Volume flow rate increase.

## 8. Precautions

1. Prior to measurement, all the pressure sensors must be set to “0”. To do this, press the RST button on the display (only for pressure not for temperature).
2. Vary RPM in a controlled manner. Never exceed 2100 RPM (75% of the rated RPM, i.e. 2800 RPM).
3. In case of an emergency, stop the setup by pressing emergency stop switch located on the right side of the switch cabinet.
4. Ensure that all wires are properly insulted. If there is any open length of wire, wrap insulation tape around it or replace the wire.
5. If both fans are to be operated at the same time, they must be switched ON at the same time. Once one fan is already being operated at a higher speed, second fan cannot subsequently be switched ON.
6. Do not take measurements continuously. Give a minimum time gap of 60 seconds between measurements after changing the throttle valve position or RPM.

## 9. References

[Lab 11 Data anlysis Jupyter Notebook](https://colab.research.google.com/drive/1WUG3-UUe5ZVfd7slNJWMXFhAJ8voB6En#scrollTo=RfGKjFPSfaUD)
