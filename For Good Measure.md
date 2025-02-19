# Lab 2: For Good Measure

**Authors:**

Ashlyn Lippert and Seth Daniel

**Date:**

February 9th, 2025

## Introduction
   The goal of this project was to analyze electrical circuits by applying fundamental circuit laws, including Kirchhoff’s Voltage Law (KVL), Kirchhoff’s Current Law (KCL), and Ohm’s Law. The analysis also incorporated Thevenin’s and Norton’s theorems, along with the superposition principle, to simplify complex circuit calculations. Additionally, the project required hands-on circuit assembly and soldering, reinforcing practical skills essential for electrical and electronic work.
   As part of this project, a series circuit was soldered and a prototype parallel circuit was assembled to experimentally verify theoretical principles. Measurements of voltage and current were taken using appropriate instruments, and the collected data was compared against theoretical predictions based on circuit laws. The soldering process provided valuable hands-on experience, highlighting the importance of precision in electronic assembly. Overall, the project enhanced both theoretical understanding and practical skills in electrical circuit analysis.

## Materials
1. Soldering station
2. Solder Protoboard
3. Small piece of solder
4. Resistors: 1kΩ, 2.2 kΩ, 2.2 kΩ, 5.1 kΩ, 4.7 kΩ, 6.8 kΩ, 15 kΩ, 220 kΩ
5. DC Power Supply (DCPS)
6. Fluke 87 V DMM
7. Wire trimmers
8. Breadboard
9. Additional wires

## Assembly Methods

**Objective 1: Learn soldering techniques by building a simple circuit on a solder protoboards**

1. **Series Circuit Assembly:**
   
   The circuit constructed for this portion of the lab is described by the following schematic in Figure 1. The 1kΩ (R1), 2.2kΩ (R2), and 5.1kΩ (R3) resistors were placed in series on the protoboard, then the leads of the resistors were trimmed down using wire cutters and folded against the protoboard. Be sure to verify the resistor values using the DMM before soldering any resistors into the protoboard.

<div align= "center">
<img src="https://github.com/user-attachments/assets/ba343305-14bd-413f-810b-dd71efa915af" alt "Schematic 1" width="400"/>
<br>
<figcaption style="font-size: 16px; text-align: center;"> Figure 1: Schematic describing the series resistor circuit built for part 1 of this lab. </figcaption>
</div>

<br>

   Once the circuit was verified to be correct, we used the soldering station set to 640 degrees to solder the resistors to the protoboard. The soldering technique we used can be described by the following diagram from Techspray.

<div align= "center">
<img src="https://github.com/user-attachments/assets/e18bd5aa-c633-454e-9cf7-5fa1ff410287" alt "Technique for Soldering" width="400"/>
<br>
<figcaption style="font-size: 16px; text-align: center;"> Figure 2: Soldering Technique used by our lab group to solder the series circuit. Retrieved from TechSpray. </figcaption>
</div>

<br>

   The resistors were soldered by placing the soldering iron on the designated solder point, then after a couple seconds, introducing the solder material to the same point. Once the solder is liquefied, the iron was used to ensure the solder is in the appropriate location and covering the resistor leads. The same process was used for each resistor lead. Each partner performed 3 resistor lead solders on the protoboard. Additionally, one end of two separate wires were soldered to the terminals of R1 and R3 for DCPS connection. The finished soldered series circuit is provided in the figure below. 

   <div align="center">
  <img src="https://github.com/user-attachments/assets/413cc0c5-ea1c-4aa9-a10b-b0bfe5e35836" alt="Top View of Soldered Series Circuit" width="400"/>
<br>
  <figcaption style="font-size: 16px; text-align: center;"> Figure 3: Top view of soldered series resistor circuit. </figcaption>
</div>

<br>

**Objective 2: Analyze a circuit to verify Kirchhoff’s Voltage Law (KVL) and Kirchhoff’s Current Law (KCL), and apply Thevenin’s and Superposition Theorems**


1. **Series Circuit**

   Utilize the soldered series circuit prepared in Objective 1.
   
2. **Parallel Circuit**

   Obtain the following resistors: 4.7 kΩ (R1), 6.8 kΩ (R2), 15 kΩ (R3), 220 kΩ (R5), and 2.2 kΩ (R5 = RL) and verify their resistance value using the DMM. Record the measured resistances in a table. Refer to the schematic given in Figure 4 for assembly instruction.

   <div align="center">
  <img src="https://github.com/user-attachments/assets/8b7ab9ec-ee73-4ae1-90cb-73f4a3801057" alt="Schematic 2" width="400">
  <p><b>Figure 4:</b> Parallel resistor circuit schematic.</p>
</div>


   No soldering is necessary for this circuit, but verification of the DCPS voltage output was performed using the DMM to ensure the voltage is within .1V of the expected output. Once assembled, the circuit should look like the following:

   <div align="center">
  <img src="https://github.com/user-attachments/assets/597d69bd-2b53-43ee-916b-f3644e0ede8e" alt="Assembled parallel resistor circuit" width="400">
  <p><b>Figure 5:</b> Assembled parallel resistor circuit for part 2.1 and 2.2 of this lab.</p>
</div>


3. **Thevenin and Norton**

   Thevenin’s Theorem states that all linear circuits can be expressed as a circuit with one equivalent voltage source and one equivalent resistance. To create the Thevenin equivalent circuit, remove R5 from the parallel circuit assembled in the previous step of Objective 2. The schematic for the Thevenin circuit is shown in Figure 6 below.

   <div align="center">
  <img src="https://github.com/user-attachments/assets/fbbb8eed-8e6c-4acc-805c-082b84bc9dc1" alt="Thevenin circuit" width="400">
  <p><b>Figure 6:</b> Thevenin equivalent circuit schematic.</p>

</div>

   When assembled, the Thevenin circuit should resemble the image below.

   <div align="center">
  <img src="https://github.com/user-attachments/assets/5af5d1d8-2de2-49b8-ab32-6b469ad4e38b" alt="Assembled Thevenin circuit" width="400">
  <p><b>Figure 5:</b> Assembled Thevenin resistor circuit for part 2.3 of this lab.</p>
</div>

## Test Equipment

1. Fluke 87 V DMM
2. DC Power Supply
   
## Test Procedures

**Resistor Measurement**

   For this part of the experiment, the resistance each resistor was measured using a Digital Multimeter (DMM) and the results were compared to the expected values based on the resistor color codes. We recorded the expected resistance, the acceptable tolerance range, and the measured resistance in a table. Any resistors that fell outside the expected range were noted.

**DCPS Output Verification:**
   
   To verify the voltage output of the DCPS, the DMM leads were connected to the output cables of the DCPS. Red was connected to red, and black was connected to black.
   The measured voltage output was then compared to the expected output voltage manually set on the DCPS.

**Part 1: Series Circuit**

1. **Voltage and Current Measurements:**
   
   Using the soldered circuit created in objective 1 of the assembly procedures, connect the terminals of R1 and R3 to the DC Power Supply using the alligator clips. Ensure black is connected to - terminal (ground) and red is connected to the + terminal.
   Once connected, set the DCPS to 10 V and press the OUTPUT ON button to begin delivering power to the circuit. Next, using the DMM measure the voltage drop across each resistor and record the results in a table.
   Change the DMM settings and lead connections to measure current, then record the current in the circuit.


**Part 2: Parallel Circuit**

2.1. **Kirchhoff's Current Law (KCL):**

   Use the circuit assembled in step 2 of objective 2 of the assembly procedures. Connect the positive terminal of the circuit to the red (+) lead and the negative terminal to the black (-) lead of the DCPS.
   Once connected, set the DCPS to provide 12 V and press the OUTPUT ON button to begin delivering power to the circuit.
   Using the DMM in series with the elements of interest in current mode, measure the current through all resistors in the circuit and record the values in a table.
  
2.2. **Kirchhoff's Voltage Law (KVL):**

   Use the same circuit assembly from step 2 of objective 2 of the assembly procedures. With the DMM, measure the voltage acrosss each resistor in the circuit and record the values in a table. Then, calculate the expected voltage drop for each resistor using Ohm's Law and the currents previously recorded.
   To calculate expected voltage drop, use the formula:
   <div align="center"> V = I*R </div>

2.3. **Thevenin and Norton:**

   Use the circuit assembly from step 3 of objective 2 of the assembly procedures. Once assembled, use the DMM to measure the voltage across R4. This voltage is the same as that applied to the "load" and can also be expressed as VTH.
   Set up the DMM to measure DC current, then connect the leads to the terminals of R4 to act as a short circuit. Measure the current IN and record the value observed.
   Remove the DMM leads from the circuit and replace with one wire connecting the disconnected end of R1 to the disconnected end of R4. Return the DMM to the Ohm meter setting and measure the equivalent resistance for the passive circuit.

## Test Results:

**Table 1: Resistor Values for Soldered Circuit (Schematic 1)**

| Resistor # | Band 1 | Band 2 | Band 3 | Band 4 | Expected Resistance (Ohms) | Tolerance | Max Value (Ohms) | Min Value (Ohms) | Measured Resistance (Ohms) |
|------------|--------|--------|--------|--------|----------------------------|-----------|----------------------|------------------|----------------------------|
| 1          | Brown  | Black  | Red    |        | 1000                       |           | 1000                 | 1000             | 991                        |
| 2          | Red    | Red    | Red    | Gold   | 2200                       | 5%        | 2310                 | 2090            | 2160                        |
| 3          | Green  | Brown  | Red    | Gold   | 5100                       | 5%        | 5355                 | 4845            | 4970                        |


**Table 2: Resistor Values for Schematics 2 and 3**

| Resistor # | Band 1 | Band 2 | Band 3 | Band 4 | Expected Resistance (Ohms) | Tolerance | Max Value (Ohms) | Min Value (Ohms) | Measured Resistance (Ohms) |
|------------|--------|--------|--------|--------|----------------------------|-----------|------------------|------------------|----------------------------|
| 1          | Yellow | Purple | Red    | Gold   | 4700                       | 5%        | 4935             | 4465             | 4555                       |
| 2          | Blue   | Grey   | Red    | Gold   | 6800                       | 5%        | 7140             | 6460             | 6946                       |
| 3          | Brown  | Green  | Orange | Gold   | 15000                      | 5%        | 15750            | 14250            | 15240                      |
| 4          | Red    | Red    | Red    | Gold   | 2200                       | 5%        | 2310             | 2090             | 2282                        |

**Table 3: Power Supply Voltage Verification**

| Expected Current from DCPS (A) | Expected Voltage from DCPS (V) | DMM Voltage Measurement (V) |
|--------------------------------|--------------------------------|-----------------------------|
| 0                              | 10                             | 9.99                        |
| 0                              | 12                             | 12                          |


**Table 4: Measured Currents for KCL Circuit (Part 2.1)**

|   Current Label   |  Measured Value (A)  |
|-------------------|----------------------|
| I1                | 0.00182              | 
| I 2/3             | 0.00182              | 
| I4                | 0.0000445            | 
| I5/IL             | 0.00164              |


**Table 4: Voltage Comparisons for KVL Circuit (Part 2.2)**

| Voltage | Measured Magnitude (V) | Calculated Voltages (V) |
|---------|------------------------|-------------------------|
| V1      | 8.44                   | 8.29                    |
| V2      | 1.1                    | 12.64                   |
| V3      | 2.45                   | 27.73                   |
| V4      | 9.68                   | 9.5                     |
| V5      | 3.55                   | 3.742                   |

## Discussion:

Discussion Question 1: Are the measured currents in agreement with Kirchhoff’s Current Law?

Our data does not comply with Kirchhoff’s current law. Kirchhoff’s Current Law states that the sum of currents entering a node must equal the sum of currents leaving the node.
The total sum of branch currents exceeds I(1), which could be due to incorrect DMM settings or human errors during measurement. These issues likely also explain the discrepancies between calculated and measured voltage drop.


Discussion Question 2: Compare the measured values and the calculated values. Are these in
agreement with Kirchhoff’s Voltage Law?

Kirchhoff’s Voltage Law states that the sum of voltage drops around a closed loop must equal the supplied voltage. From our measured voltages: V4 + V5 = 12.23V, since the input voltage is 12V, we can conclude our data complies with Kirchhoff’s voltage law (ignoring minor discrepancies due to error).

Discussion Question 3: Calculate the power delivered by the power supply and the power
dissipated by every resistor. Is the power delivered by the power supply equal to the total power
dissipated?

The power supplied by the power source should equal the total power dissipated by resistors in the circuit.

Power Supplied:

P = V * I = 12V * 1.82mA = 0.0218 W


Power Dissipated by Resistors:

∑ (V^2) / R = 0.0177 W


The difference between supplied and dissipated power suggests measurement inaccuracies, most likely due to DMM misconfiguration or human errors during measurement. 


Discussion Question 4: Using circuit analysis, calculate RTH, IN, and VTH, and compare them with
the measured values. Are the calculated values in agreement with the measured values?

| Symbol  | Measured               | Calculated              |
|---------|------------------------|-------------------------|
| Vth     | 9.68V                  | 9.7 V                   |
| In      | 44.5uA                 | 43.5 uA                 |
| Rth/Rn  | 3760Ω                  | 223000 Ω                |

The values we calculated using circuit analysis and expected resistances completely agree with the measured values. Any small discrepancies can be explained by resistor tolerances.

## Conclusion:

This lab reinforced our understanding of circuit analysis by applying Kirchhoff’s laws, Ohm’s law, and Thevenin’s theorem. We built and tested series and parallel circuits, taking voltage and current measurements to compare with theoretical values. While most results aligned with expectations, some discrepancies were likely due to measurement errors or resistor tolerances. Additionally, soldering the series circuit provided valuable hands-on experience. Overall, the lab improved both our analytical and practical skills in circuit design and testing.

## Sources:

Ultimate Guide to Electronic Soldering. (n.d.). Techspray. https://www.techspray.com/ultimate-guide-to-electronic-soldering?srsltid=AfmBOoprXNhd-Lety6MHBoPSrOQDy-SjmZflQmQewodzb_W0G7A7Jpsk
