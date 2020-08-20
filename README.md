# Over Voltage and Under Voltage Protection System for Electrical Appliances
This is an under/over-voltage protection circuit that protects refrigerators as well as other appliances from under &amp; over-voltage. Operational amplifier IC LM324 (IC2) is used here as a comparator. IC LM324 consists of four operational amplifiers, of which only two operational amplifiers (N1 and N2) are used in the circuit.

#Circuit Operation:
The unregulated power supply is connected to the series combination of resistors R1 and R2 and potmeter VR1. The same supply is also connected to a 6.8V zener diode (ZD1) through resistor R3. Preset VR1 is adjusted such that for the normal supply of 180V to 240V, the voltage at the non-inverting terminal (pin 3) of operational amplifier N1 is less than 6.8V. Hence the output of the operational amplifier is zero and transistor T1 remains off. The relay, which is connected to the collector of transistor T1, also remains de energized. As the AC supply to the electrical appliances is given through the normally closed (N/C) terminal of the relay, the supply is not disconnected during normal operation.

#Over-voltage protection
#Under-voltage protection

