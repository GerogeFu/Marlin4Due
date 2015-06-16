# Marlin4Due 3D Printer Firmware
<img align="right" src="Documentation/Logo/Marlin%20Logo%20GitHub.png" />

### Story about Marlin 32bit
Some time ago bobc started with this port. After some time sadly he stopped with the development. So I started to take his work and try to make some small modifications. After a couple of weeks I found the most importent things which speed up my new fork. Thanks to bobc for this great work! I'm not a professional programmer and without bobc I couldn't do that.

Also a big thanks to all Marlin8bit-developers. Keep on working.

A big thanks to Repetier! We've talked a lot in the last weeks.

*Wurstnase*

### This is an experimental repository! You should never leave your printer alone.

### New features are:
* Stepping-algorithm optmized now for DRV8825 and A4988 (no need for double or quadstepping; no delays)
* High speed stepping of approx. 295,000 steps/s, if needed (maybe more with less DOUBLE_STEP_FREQUENCY?)
* watchdog implemented (you need to modify one Arduino-file for it; comment out WDT_Disable(WDT) in your variant.cpp)
 
### known issues:
* advanced extruder not implemented

---
# Marlin 3D Printer Firmware
  * [Configuration & Compilation](/Documentation/Compilation.md)
  * Supported
    * [Features](/Documentation/Features.md)
    * [Hardware](/Documentation/Hardware.md)
    * [GCodes](/Documentation/GCodes.md)
  * Notes
    * [Auto Bed Leveling](/Documentation/BedLeveling.md)
    * [Filament Sensor](/Documentation/FilamentSensor.md)
    * [Ramps Servo Power](/Documentation/RampsServoPower.md)
    * [LCD Language - Font - System](Documentation/LCDLanguageFont.md)
    * [Mesh Bed Leveling](/Documentation/MeshBedLeveling.md)

##### [RepRap.org Wiki Page](http://reprap.org/wiki/Marlin)

## Quick Information

This is a firmware for reprap single-processor electronics setups.
It also works on the Ultimaker PCB. It supports printing from SD card+Folders and look-ahead trajectory planning.
This firmware is a mashup between [Sprinter](https://github.com/kliment/Sprinter), [grbl](https://github.com/simen/grbl), and many original parts.

## Current Status: Bug Fixing


## Credits

The current Marlin4Due dev team consists of:

 - Nico [@wurstnase]
 - 

## Donation

If you find our work usefull please consider donating. Donations will be used to pay for our website http://www.marlinfirmware.org/ and to pay some food or rent money for the very active Collaborators

More features have been added by:
  - Lampmaker,
  - Bradley Feldman,
  - and others...

## License

Marlin is published under the [GPL license](/Documentation/COPYING.md) because We believe in open development.
Do not use this code in products (3D printers, CNC etc) that are closed source or are crippled by a patent.

Marlin4Due [![Flattr Marlin4Due](http://api.flattr.com/button/flattr-badge-large.png)](https://flattr.com/submit/auto?user_id=Wurstnase&url=https%3A%2F%2Fgithub.com%2FWurstnase%2FMarlin4Due) MarlinFirmware [![Flattr MarlinFirmware](http://api.flattr.com/button/flattr-badge-large.png)](https://flattr.com/submit/auto?user_id=ErikZalm&url=https://github.com/MarlinFirmware/Marlin&title=Marlin&language=&tags=github&category=software)
