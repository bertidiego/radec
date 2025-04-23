
[![Stand With Ukraine](https://raw.githubusercontent.com/vshymanskyy/StandWithUkraine/main/banner2-direct.svg)](https://stand-with-ukraine.pp.ua)

# RADEC
![Static Badge](https://img.shields.io/badge/REV-1-9834FF?style=for-the-badge)
![Static Badge](https://img.shields.io/badge/BASED_ON-ATMEGA328P--AU-FF9FFF?style=for-the-badge)
[![Issues](https://img.shields.io/github/issues/bertidiego/radec.svg?logo=GitHub&style=for-the-badge&color=lightblue)](https://github.com/bertidiego/radec/issues)
[![Licence](https://img.shields.io/github/license/bertidiego/radec.svg?style=for-the-badge)](LICENSE.adoc)

**RADEC** is a compact, open-source control board designed to drive stepper motors for telescope GoTo systems.



## About The Project
RADEC is an **open-source controller for telescopes**. It's based on the **MEADE LX200** communication protocol which is easy to understand and simple to code.
It communicates with the computer through a **serial port** and reacts in almost **real time**!


## Features

- Compact design (**you can contribute** - go to section)
- **USB-UART** communication
- **I2C LCD** support
- On-board **power management**
- Controlled by every software that support **MEADE LX200** communication protocol
- ~~**WIP** - [**Skynapse**](https://github.com/bertidiego/skynapse), the **open-source** software that controls RADEC to life with precise slewing, object tracking, and PC-based UI (go to section)~~ **Skynapse is being discontinued**, please use **[Stellarium](https://github.com/Stellarium/stellarium)** which is a free software that does the same things, except 100 times better :)


## Hardware Components

The main components of RADEC **REV1** are, but not limited to:

- **1x** ATMEGA328P-AU microcontroller
- **1x** LM2596S for the step-down regulator
- **1x** C99652 for USB communication
- **1x** USB Type-B port (**To be upgraded to an USB Type-C**)
- **OPTIONAL** - **1x** LCD I2C **16x4** to display current data
- You can take a look to the BOM down below!
## Schematics

The schematics for the REV1 of RADEC could be found [**here**](https://github.com/bertidiego/radec/tree/main/schem).
## BOM

The BOM (Bill Of Materials) could be found [**here**](https://github.com/bertidiego/radec/tree/main/bom).
## License


This project is licensed under the **[MIT](https://choosealicense.com/licenses/mit/) License**.  
You are free to use, modify, and redistribute the code and hardware files — just include attribution.

## Support

Do you need assistance? Check our Discord (**WIP**) server!

