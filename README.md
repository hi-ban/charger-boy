# CHARGER BOY
A custom Li-Po battery charger/regulator PCB for the Nintendo Game Boy DMG-01.

Features:
- Single cell Li-Po battery charger using a TP4056 IC.
- Uses the Gameboy's DC connector as power input, so you don't have to cut any holes for microUSB ports.
- Overcharge (4.25v), Overdischarge (2.9v), Overcurrent and Short-Circuit protection using a FS312F IC and a FS8205 dual mosfet.
- Power path control: Disconnects the battery from the load while charging, so you can simultaneously play and charge without damaging the battery.
- Power regulator, using a MT3608 step-up converter to output 5v into the system.
- (Optional) "TMP" pad connected to the TEMP pin of the TP4056, for battery temperature protection. Must be shorted to GND if not in use.


Since this PCB only outputs 5v, it's only suitable for being used with IPS-Screen modded units. The shape of the PCB is the same as the original regulator PCB, so it fits in the place of the old regulator.

This PCB requires to be connected to different points than the original regulator, and it also requires minimal modding to the DMG mainboard (removing a diode, connecting two solder points together and removing the battery contacts).

Using a 125054 battery is recommended, as it fits perfectly in the DMG battery compartment with no additional modding required.

More info coming soon.
