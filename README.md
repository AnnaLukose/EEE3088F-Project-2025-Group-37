# EEE3088F-Project-2025
Welcome to the repo for group 37's micromouse project!

The final design kicad files are available in the KICAD FILES folder.
Previous versions are also available in the draft 1 and draft 2 zip folders.

To view the schematic for our final design, view the Schematic pdf above.

This project required us to design a single PCB to fulfill the following power module requirements for a micromouse:

* Operate up to 4 motors bidirectionally with the pins available to you (listed in the power pinout
table). You will need to control 2x brushed DC motors which could each draw 200mA at the
highest voltage of a 1S1P battery (the battery is further specified in the battery section).
The other 2x motors are for the auxiliary connection and need to operate 500mA each.
* Place an INA219 for monitoring the battery on the I2C Bus and configure it correctly with
respect to the hardware (cannot have BOTH A0 AND A1 on GND)
* Charge the battery from the 9V input pin (listed in the power pinout table).
* Have two charging modes for a higher and lower charging current for the battery (200mA, and
approximately 600mA ±100mA from the battery perspective.
* Integrate USB C and get 9V out of the USB Host
* Provide 2x External Load Switching at 1A each (High Side connected to your 5V)
* Provide a 3V3 5% accuracy (300mA max) and 5V Out 5% accuracy (1.5A max)
* Provide an ON/OFF switch. OFF state: battery draw <30uA. ON state: can provide your robot
peak current of 2A. The switch needs to shut down 5V and 3V3
<p align="center">
  <img src="https://github.com/user-attachments/assets/f5e079a2-980d-4940-beda-e9e7ffc1cc1f" height="500">
</p>

The requirements were split between us, each members files can be found under their corresponding name.
