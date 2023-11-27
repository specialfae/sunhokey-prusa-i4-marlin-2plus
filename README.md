# Sunhokey Prusa I4 Custom Marlin 2.1.1.1 - Polished Turd Edition

Souped-up Marlin 2.1.1.1 for the Sunhokey Prusa I4 (Old Prusa MK3 mutant clone.)

This project is very much a case of getting back into an old hobby and using what you've got.

This current configuration's optimised for eSUN PLA+ filament on stock hardware with the optional (at the time) nozzle blowerfan.

## Features

- **Quality**: The print quality difference from factory Marlin 1.1 firmware is staggering.
- **UI/X**: Working with the printer is so much easier.
- **Safety**: Modern safety features including thermal protection.
- **Bed Leveling**: Mesh leveling is enabled and works great.
- **PID Tuning**: Tuned hotend temperature control.
- **Extruder Calibration**: Extruder steps corrected so flow compensation isn't needed.
- **Z-Axis Calibration**: Better layer adhesion and dimensions.
- **Custom End G-code**: Implemented from aeinc.ru/i4 end g-code.

## Contents

- `/Marlin`: Customised Marlin 2.1.1.1 firmware, ready to flash.
- `/PrusaSlicer`: Boilerplate slicer settings for PLA (work in progress, with upcoming speed improvements).

## Upcoming

- Currently working on 3D touch support.
- Better speed settings in slicer boilerplate.

## Acknowledgements

Thanks to the following projects

[aeinc.ru/i4](http://aeinc.ru/i4/)

[Marlin Firmware](https://github.com/MarlinFirmware/Marlin)

[Prusa Slicer](https://github.com/prusa3d/PrusaSlicer).

## License

This project is licensed under the GNU General Public License v3.0, in line with Marlin Firmware.

## Installation & Usage

For installation instructions, refer to the [Marlin Firmware documentation](https://github.com/MarlinFirmware/Marlin).
