# wyse-mod
This project is supposed to make converting Wyse keyboards with 4P4C connector easier to test and eventually turn into a standalone converter. It is designed to work with [Soarer's Wyse conversion software](https://geekhack.org/index.php?topic=52597.0) but I'll be trying to create something similar soon (at least compatible with Wyse PCE Keyboard).

Also thanks to [ErkHal](https://github.com/ErkHal) and his [Pohola Work's project](https://github.com/pohjolaworks/wyse-converter) for sparking an idea for this project.

# Parts List
- the PCB
- Pro Micro like board (with ATmega32U4) 
- Hotswap sockets for the Pro Micro
- 4P4C connector
- RJ9/RJ10/RJ22 cable
- 6x6 button (optional, but makes flashing software easier)
- 4xM3 screws (TODO after designing a case)

# Overview
The PCB has additional pads to solder wires straight from the keyboards connector pins just to test it out. A Pro Micro microcontroller should be mounted on the bottom of the board, with the USB connector facing the PCB. Also using a socket for an MCU is highly recommended. After ensuring that your Wyse keyboard works with the software, solder a 4P4C connector and plug in an old RJ9/RJ10/RJ22 (afaik they are all the same) roll-over (crossed).

# TODO
- [x] Design a PCB [Rev 1.0 is being tested]
- [ ] Design a case
- [ ] Try to write own conversion software
