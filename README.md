# WSPR-beacon

![WSPR-beacon](./Resources/WSPR-beacon-logo.png)

A small hardware device for transmitting WSPR messages based on the SI5351 IC. The device has a built-in TCXO to eliminate SI5351 frequency drift, a built-in GPS module for operation with active GPS antennas, transmission time synchronization and automatic QTH locator calculation, and a simple amplifier based on a single BS170 transistor. PCB is made on based on SMD components and adapted for installation in an aluminum enclosure with dimensions 80 x 50 x 20 mm.

## Current development progress:
[![Progress](https://img.shields.io/badge/wspr--beacon%20EasyEDA-not%20tested-red.svg?longCache=true&style=for-the-badge)](https://oshwlab.com/igrikxd/wspr-beacon)&nbsp;[![Progress](https://img.shields.io/badge/firmware%20version-1.0-blue.svg?longCache=true&style=for-the-badge)](./Firmware)&nbsp;[![Progress](https://img.shields.io/badge/pcb%20version-1.0-blue.svg?longCache=true&style=for-the-badge)](./Gerbers)   

Correctness of encoding of the transmitted WSPR message was verified by decoding the transmission using a locally located Airspy R2 SDR receiver and the [WSJT-X](https://wsjt.sourceforge.io/wsjtx.html) application.

## Basic characteristics of the WSPR-beacon:
**RF connectors:** SMA  
**Feed line:** 50 Ohm coaxial cable  
**GPS antenna type:** active, external  
**Maximum output power:** ~23 dBm  
**Supply voltage:** 5V, USB-B  
**Used PCB Material:** FR-4  
**PCB thickness:** 1.6 mm  
**PCB copper weight:** 1 oz  

## How to use this repository?
The [Firmware](./Firmware/) folder contains software required for the device operation and firmware instructions. The [Schematics](./Schematics/) directory contains the device schematic file in _.pdf_ format. The [Gerbers](./Gerbers/) directory contains files necessary for ordering PCB [fabrication at the factory](https://pcbway.com).

Additionally, you can find information about the [list of required components](./BOMs), [assembly guide](./Assembly-guide.md), and [operating instructions](./Usage-guide.md).

## Resources:
[A Little WSPR Beacon (Aren’t They All Little?) – Dave Richards AA7EE](https://aa7ee.wordpress.com/2023/02/26/a-little-wspr-beacon-arent-they-all-little/)  
[ESP WSPR – Simple and Inexpensive WSPR Transmitter - Ankara Telsiz ve Radyo Amatörleri Kulübü Derneği](https://antrak.org.tr/blog/esp-wspr-simple-and-inexpensive-wspr-transmitter/)  
[K1FM-WSPR-TX - GitHub](https://github.com/adecarolis/K1FM-WSPR-TX)  
[QRP Labs QRSS/WSPR TX Kit](https://qrp-labs.com/images/ultimate3s/assembly_u3s_r3_lt.pdf)
[WSPR beacon – Projets radio](https://hamprojects.wordpress.com/2019/06/02/wspr-beacon/)

## Who helped me with the development of the project?
Great thanks to [PCBWay] for manufacturing PCBs for the project implementation.
![PCBWay-Logo](./Resources/PCBWay-logo.png)

## How to contact me?
- E-mail: igor.nikolaevich.96@gmail.com
- Telegram: https://t.me/igrikxd
- LinkedIn: https://www.linkedin.com/in/igor-yatsevich/

[PCBWay]: <https://pcbway.com>