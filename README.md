#PID-Controlled VCO
Overview

Designed a Voltage-Controlled Oscillator (VCO) generating triangular waveforms (20 Hz–2 kHz) with frequency proportional to input DC voltage, stabilized using a closed-loop control system.

Working
VCO: Op-amp integrator + comparator with MOSFET discharge for oscillation
F→V Converter: NE555 (monostable) generates fixed-width pulses, RC-averaged to obtain frequency-proportional voltage
Control: PID loop minimizes error between reference input and feedback

Implementation
Simulated using LTSpice
Tested on breadboard hardware

Components
Op-amps, NE555, MOSFET, RC networks, diodes
