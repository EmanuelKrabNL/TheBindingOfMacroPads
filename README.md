# TheBindingOfMacropads

A 6-key macropad with a rotary encoder and a 0.91" OLED display, built around a Seeed XIAO RP2040. Made as part of the [Hack Club Hackpad](https://hackpad.hackclub.com), for the Stardance YSWS program.

## Features:
- 6 macro keys, arrow-key style layout
- EC11-style rotary encoder — volume control, click to mute, etc.
- 0.91" 128x32 OLED display (I2C)
- QMK firmware
- VIAL Support
- OLED support
- Different presets (Discord, The binding of isaac, spotify, OBS, snake, timer and flappy bird.
- Konami code (up up down down left right left right), long press rotary encoder to see credits.
- Small tboi themed icons, isaac will sleep after a minute of inactivity.

## Why did i make this?
I have a 60% keyboard, so i cant use WASD and arrows together, so i made this board so i could play the binding of isaac! 

## CAD Model:

<img src=Assets/cad.png alt="Case" width="300"/>

## PCB
Made in kicad.

Schematic
<img src=Assets/Schematic.png alt="Schematic" width="300"/>

PCB
<img src=Assets/pcb.png alt="PCB" width="300"/>

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
