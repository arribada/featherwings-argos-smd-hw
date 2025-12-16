![N|Solid](https://arribada.org/wp-content/uploads/2022/01/arribada_web_logo_g.svg)
# Feather Wings argos SMD breakout
## Description 

**Feather Wing for the ARGOS-SMD module. **

This breakout board can be used with a Feather board (from Adafruit) to connect the ARGOS-SMD module. 
It exposes the ARGOS-SMD module pins to the Feather board and includes a specific LDO to power the RF amplifier.

[Details of SMD argos repository.](https://github.com/arribada/argos-smd-hw)

This repository is an altium project with the production files. Please download the [hardware-lib](https://github.com/arribada/hardware-lib ) if you want full sources files (device sheet + library). 

## Components:

The RSPB tracker include the following components:
 - argos-smd
 - TPS63901 => power for RF amplifier
    

## Quick start

 - Connect Adafruit Feather nRF52840 (the Feather will provide 3V3 for SMD and VBAT or VBUS for Power Amplifier SMD)
 - Upload [Arduino sample](https://github.com/arribada/argos-smd-test-arduino) code or [Zephyr driver](https://github.com/arribada/argos-smd-driver-zephyr)
 - Communicate with KimGUI or Serial link with J6 connector
   or
 - Communicate to the SMD via the Adafruit Feather.

## Pin out 

Check Wiki page.
