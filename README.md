# Amplifier-design
The purpose of the project is to design (schematic and layout) amplifier with bandwidth controlled by DAC current.

It is made in 180nm technology in Cadence Virtuoso 6.1.8

Amplifier works as a voltage follower loaded with 1pF capacitor.

There are few design requirements:

-Bandwidth controlled by DAC current in range about 20MHz - 60MHz

-Amplifier has to be stable - Phase Margin >60 degree throughout the whole bandwidht

-Power consumption no more than 250uW

The amplifier is design on differential pair with active load as a first stage and second is common source stage with active load.

In brief it is a Miller CMOS OTA configuration.

Current from DAC is passed through current mirror.

Power supply is in range 0V - 1.8V.
