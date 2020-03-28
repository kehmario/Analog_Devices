# Analog_Devices
ADI Projects using Cross Core Embedded Studios
Release 27 March 2020

Files were created by example build for Keil uVision.
Does not require major revision, this is being used to read a direct Analog-Digital-Conversion.
Intended device is an ElectroCardioGram, 3-lead, right leg driven system.
Signal is amplified by 8+138.8 times.

Implementation of a IIR filter may be required because of the unintended radiation coupling

First step
Test the ADC is working by using a known source

Second step
Implement the UART or use another source of communication to pass data for graphing

Third step
Implement IIR butterworth filter to remove the signals above 10 Hz,
excessive difficult will end up using an active low pass filter, single pole
