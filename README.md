# TheBindingOfMacropads

A 6-key macropad with a rotary encoder and a 0.91" OLED display, built around a Seeed XIAO RP2040. Made as part of the [Hack Club Hackpad](https://hackpad.hackclub.com), for the Stardance YSWS program.

## Features:
- 6 macro keys, arrow-key style layout
- EC11-style rotary encoder — volume control, click to mute --I will add other presets that you can see on the oled screen in the future--
- 0.91" 128x32 OLED display (I2C)
- QMK firmware
- VIA Support is in the works
- OLED support is also in the making

## CAD Model:

<img src=assets/cad.png alt="Case" width="300"/>

## PCB
Made in kicad.

Schematic
<img src=assets/schematic.png alt="Schematic" width="300"/>

PCB
<img src=assets/pcb.png alt="PCB" width="300"/>

## Firmware Overview
This hackpad uses [QMK](https://qmk.fm/) firmware.

- The rotary encoder controls volume. Click to mute.
- The 6 keys are mapped to arrow keys, space and E by default.

## BOM:
- 1x Seeed XIAO RP2040
- 1x 0.91" 128x32 OLED display (I2C, SSD1306-compatible)
- 6x Cherry MX Switches
- 6x DSA Keycaps
- 1x EC11 rotary encoder
- 1x Case (2 printed parts)
