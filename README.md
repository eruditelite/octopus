# Overview #

A slightly more involved octopus (curve tracer) just to learn a
bit. Instead of using a small transformer for the input, use a
buffered signal generator. The idea is to have similiar functionality
to the Huntron Tracker. Something like

2800/2800S

   Voltage: 200mV, 3V, 5V, 10V, 15V, 20V
Resistance: 10Ω, 50Ω, 100Ω, 500Ω, 1kΩ, 5kΩ, 10kΩ, 50kΩ and 100kΩ
 Frequency: 20Hz, 50Hz, 60Hz, 200Hz, 500Hz and 2kHz

3200S

   Voltage: 200mV, 400mV, 600mV, 800mV, 1V to 20V in 1V steps
	        including 10V (Low), 15V (Med 1), 20V (Med 2)
Resistance: 10Ω, 20Ω, 50Ω, 100Ω, 200Ω, 500Ω, 1kΩ, 2kΩ, 5kΩ, 10kΩ, 20kΩ,
	        50kΩ, 100kΩ, 54Ω (Low)*, 1.2kΩ (Med 1)*, 26.7kΩ (Med 2)*
 Frequency: 20Hz to 190Hz in 10Hz steps; 200Hz to 1.9kHz in 100Hz steps;
            2kHz to 5kHz in 1kHz steps

For this project, a scope in XY mode will be the display.

A function generator, with a buffer, will supply the AC. This would
mean that the frequency would be continuously adjustable, limited only
by the function generator and the characteristics of the buffer. As
the highest frequency Huntron used is 5 KHz, the buffer will be
designed to handle frequencies from 20 Hz to 5 KHz.

Voltage would be provided by a supply, but there seems no need to go
beyond 20V as this is the most Huntron ever allowed.  So, 200 mV to 20
V.
