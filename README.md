# 12V DC to 220V AC Inverter Using NE555 and IRFZ44 MOSFETs

This is a simple electronics project I built to convert a 12V DC supply into 220V AC using an NE555 timer, MOSFETs, and a transformer. The project includes the block diagram/schematic and the completed PCB board photo.

## Project Overview

The circuit uses an NE555 timer to generate switching pulses, a small transistor stage for driving, and two IRFZ44 MOSFETs to switch the transformer primary. The transformer steps the voltage up to 220V AC at the output.

## Materials Required

- NE555 timer IC
- IRFZ44 MOSFET x 2
- S8050 transistor
- Transformer for 12V to 220V step-up
- Resistors: 4.7K, 100K, 50K potentiometer, 470R, 10K
- Capacitors: 0.1uF, 0.01uF
- Perfboard or PCB
- Connecting wires
- 12V DC power source

## Block Diagram / Schematic

![Block diagram](diagram.png)

## PCB Board

![PCB board](Pasted%20image%20(2).png)

## Notes

- This is a basic homemade inverter project.
- The output voltage can be dangerous, so handle the circuit carefully.
- The final output depends on the transformer and component values used.
