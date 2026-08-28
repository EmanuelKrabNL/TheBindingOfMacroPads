# thebindingofmacropads

![thebindingofmacropads](https://i.imgur.com/PLACEHOLDER.png)

A 6-key macropad with a rotary encoder (push-click) and a 0.91" I2C OLED display, built on a Seeed XIAO RP2040. Made as part of Hack Club's Stardance program following the Hackpad tutorial.

* Keyboard Maintainer: [Emanuel](https://github.com/EmanuelKrabNL)
* Hardware Supported: Custom PCB, Seeed XIAO RP2040
* Hardware Availability: [EmanuelKrabNL/TheBindingOfMacroPads](https://github.com/EmanuelKrabNL/TheBindingOfMacroPads)

Make example for this keyboard (after setting up your build environment):

    make thebindingofmacropads:default

Flashing example for this keyboard:

    make thebindingofmacropads:default:flash

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Bootloader

Enter the bootloader in 3 ways:

* **Bootmagic reset**: Hold down the key at (0,0) in the matrix (SW1) and plug in the keyboard
* **Physical reset button**: Hold the **B** (boot) button on the XIAO RP2040 while tapping the **R** (reset) button — the board shows up as a `RPI-RP2` USB drive
* **Keycode in layout**: Press the key mapped to `QK_BOOT` if it is available