# 555-Timer-Project
# Project Overview
During my studies at Gazi University, I developed an Analog Project. This project involves setting up a DC motor fan using the 555 timer IC. The circuit includes components such as a temperature sensor, potentiometers, resistors, capacitors, a transistor, and the 555 timer IC to achieve two-stage speed control activated by temperature changes.

# Contributors
Hasan Ağaçayak - 181110001
Mesut Arıkan - 181110012
# Components Used
1 x 3.3k NTC temperature sensor (LM35 used for simulation)
2 x Potentiometers (50k and 100k)
2 x 10k Resistors
2 x Capacitors (100nF and 10nF)
1 x BC237 Transistor
1 x Fan
1 x 555 Timer IC
# Circuit Description
The circuit aims to establish a DC fan with 2-stage speed control activated by the temperature sensor. Here's a step-by-step breakdown of the circuit setup:

Power Supply Connection: Connect the 12V VCC source to the temperature sensor and subsequently to other components in the circuit.
Resistor Addition: Add a 10k resistor before the potentiometers to prevent short-circuiting when resetting the pots.
Potentiometer Setup:
Connect the 50k potentiometer with the threshold, trigger, and 100nF capacitor.
Connect the 100k potentiometer's middle pin to the discharge end, leaving the last pin exposed.
Capacitor Connections:
The 100nF capacitor is connected to ground, ensuring it charges and discharges correctly to control the trigger and threshold inputs of the 555 Timer.
The 10nF capacitor is connected between the control voltage and ground, protecting the 555 Timer from external influences.
Transistor and Diode Setup:
The transistor is connected to the motor to create a voltage difference between VCC and output Q.
A diode is placed in parallel with the motor to prevent excess voltage and protect the motor.
# Circuit Functionality
The 555 Timer generates DC signals at the output when the temperature sensor detects heat.
Speed adjustments of the motor are made by changing the resistance using the potentiometers.
The circuit allows for precise speed control and gradual switching, ensuring smooth operation of the fan.
# Result
The circuit successfully controls the DC motor's speed in response to temperature changes, demonstrating the effective use of the 555 Timer IC and associated components.
