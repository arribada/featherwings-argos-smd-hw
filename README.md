![N|Solid](https://arribada.org/wp-content/uploads/2022/01/arribada_web_logo_g.svg)
# Feather Wings argos SMD breakout
## Description 

TFeather wing for the ARGOS-SMD module. This breakout board can be used with a Feather board (from Adafruit) to connect the ARGOS-SMD module. 
It exposes the ARGOS-SMD module pins to the Feather board and includes a specific LDO to power the RF amplifier.

[Details of SMD argos repository.](https://github.com/arribada/argos-smd-hw)

This repository is an altium project with the production files. Please download the [hardware-lib](https://github.com/arribada/hardware-lib ) if you want full sources files (device sheet + library). 

## Components:

The RSPB tracker include the following components:
 - argos-smd
 - TPS62A01DRL => power for RF amplifier
    

## Pin out 

Look at featherwings-argos-smd_Pinout.xlsx file inside Project Outputs folder.


## Device sheet used

- DeviceSheets:
	-	TPS62A01DRL_Buck_3V3

## State
V0.1e: (2023/10/01): PCB production for test purpose (no assembly)


## Todo
- Replace TPS62A01DRL by TPS63901.
