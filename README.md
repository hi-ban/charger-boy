# CHARGER BOY
A custom Li-Po battery charger/regulator PCB for the Nintendo Game Boy DMG-01.

Features:
- Single cell Li-Po battery charger using a TP4056 IC.
- Uses the Gameboy's DC connector as power input, so you don't have to cut any holes for microUSB ports.
- Overcharge (4.25v), Overdischarge (2.9v), Overcurrent and Short-Circuit protection using a FS312F IC and a FS8205 dual mosfet.
- Power path control: Disconnects the battery from the load while charging, so you can simultaneously play and charge without damaging the battery.
- Voltage regulator, using a MT3608 step-up converter to output 5v into the system.


This PCB only outputs 5v, so it's only suitable for being used with IPS-Screen modded units. It is intended to replace the original regulator PCB.
As such, it also requires to be connected in a different way than the original regulator.

More info coming soon.
