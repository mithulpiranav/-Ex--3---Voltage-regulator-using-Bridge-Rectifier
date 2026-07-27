# -Ex--3---Voltage-regulator-using-Bridge-Rectifier

**Aim **

To design, simulate, and analyze a regulated DC power supply using a bridge rectifier and voltage regulator IC in Proteus software, and to study the conversion of AC voltage into a stable DC output.

**Apparatus Required**

S.No	Components/Software	Specification

1	Proteus Design Suite	Version 8.0 or above
2	AC Voltage Source	230 V AC, 50 Hz
3	Step-down Transformer	230 V / 12 V AC
4	Bridge Rectifier	4 × 1N4007 Diodes
5	Filter Capacitor	1000 µF, 25 V
6	Ceramic Capacitor	0.1 µF
7	Voltage Regulator IC	7805 (5 V) / 7812 (12 V)
8	LED	Power Indicator
9	Current Limiting Resistor	330 Ω or 1 kΩ
10	Load Resistor	220 Ω – 1 kΩ
11	DC Voltmeter	Virtual Instrument
12	Oscilloscope	Virtual Instrument
13	Ground Terminal	-

**Circuit Diagram**

<img width="1341" height="963" alt="image" src="https://github.com/user-attachments/assets/06dee450-05e2-43aa-b15d-0fa926955c0d" />

**Theory**

A voltage regulator using a bridge rectifier is a regulated power supply circuit that converts Alternating Current (AC) into a stable Direct Current (DC) voltage. Such regulated power supplies are widely used in electronic devices, embedded systems, communication equipment, and microcontroller-based circuits.

The circuit consists of four major stages:

1. Step-down Transformer

The transformer reduces the mains supply voltage from 230 V AC to a safer and lower voltage, typically 12 V AC, suitable for electronic applications. It also provides electrical isolation between the mains supply and the load.

2. Bridge Rectifier

A bridge rectifier consists of four diodes (1N4007) connected in a bridge configuration. It converts both the positive and negative half-cycles of the AC input into pulsating DC, resulting in full-wave rectification.

During the positive half-cycle, two diodes conduct, while during the negative half-cycle, the other two diodes conduct. Hence, current flows through the load in the same direction throughout both cycles.

3. Filter Circuit

The output of the bridge rectifier contains ripple voltage. An electrolytic capacitor connected across the rectifier output acts as a filter, charging during voltage peaks and discharging during voltage drops. This reduces ripple and produces a smoother DC voltage.

4. Voltage Regulator

The 7805 (5 V) or 7812 (12 V) voltage regulator IC maintains a constant output voltage even when the input voltage or load current varies within specified limits. The regulator provides:

Constant output voltage

Ripple reduction

Improved load regulation

Overload and thermal protection

The regulated DC output is suitable for powering digital circuits, microcontrollers, sensors, and embedded systems.

Proteus software enables virtual implementation and testing of the entire regulated power supply circuit. Using virtual oscilloscopes and voltmeters, the user can observe AC input, rectified waveform, filtered output, and regulated DC output without requiring physical hardware.

**Procedure**

Open Proteus Design Suite and create a new project.

Select the required components:

AC Source

Step-down Transformer

Four 1N4007 diodes

Electrolytic Capacitor

7805 (or 7812) Voltage Regulator

LED and resistor

Voltmeter and Oscilloscope

Place the components on the workspace.

Connect the components according to the circuit diagram.

Set the transformer output to 12 V AC.

Connect the bridge rectifier to the transformer secondary.

Connect the filter capacitor across the rectifier output.

Connect the regulator IC and LED load circuit.

Attach the oscilloscope and voltmeter to observe waveforms and output voltage.

Run the simulation.

Observe the waveform after:

Transformer

Bridge Rectifier

Filter Capacitor

Voltage Regulator

Record the regulated output voltage and compare it with the expected value.

**Output**

<img width="808" height="840" alt="image" src="https://github.com/user-attachments/assets/3b8281d4-569e-4971-91cd-6efcd8d2a591" />

**Result**

The Voltage Regulator using Bridge Rectifier circuit was successfully designed and simulated using Proteus software. The bridge rectifier converted the AC input into pulsating DC, the filter capacitor reduced the ripple voltage, and the 7805/7812 voltage regulator IC provided a stable regulated DC output. The simulation results confirmed the successful operation of the regulated power supply circuit, making it suitable for powering low-voltage electronic and embedded systems.
