# Custom-Devboard-RP2040-
Custom development board using the RP2040 microcontroller with 20 GPIO pins, 4 ADC pins, 2 user-controlled LED, 1 user button, etc.

## Why this?
I started this project, because I wanted to learn more about KiCAD. Also, I wanted a DevBoard that i could easily prototype with. As, most of the DevBoards online had some quirks like random GPIO arrangement or doesnt have any means of displaying a output on the board itself. So, I built this and it really helped in many ways.


## Features
- RP2040 microcontroller at 133MHz
- USB Type-C connector
- max 600mA power draw
- Boot and reset buttons
- Power & 2 User LED
- GPIO header pins
- Debug connector
- Bootsel, Reset & User Buttons

## Hardware Design
The hardware design will include:
- Power by AP2112K-3.3 linear LDO regulator
- 16mB External QSPI flash from W25Q16JVZPIQ TR
- USB-C interface for programming and power
- Clock source: 12MHz Crystal

## Pictures


## Future Improvements
- Add Li-ion compatibility
- On-Board tiny OLED display
- Improved portability for prototyping
