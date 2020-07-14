<p align="center">
  <img align="middle" src="https://github.com/EvvL/Alchemy49/raw/master/Graphics/Logo.png"  width="419"> 
  <br>
  <a href="https://certification.oshwa.org/us000215.html"><img align="middle" src="https://github.com/EvvL/Alchemy49/raw/master/Graphics/OSHWA-US000215.png"  width="100"></a>
</p>

**Status:** Ordering final prototype

## Introduction

The Alchemy49 is a replacement pcb for the Magicforce 49 supporting south facing Switches, LEDs, PCB mounted stabilizers
and QMK. It's built around the SparkFun Pro Micro and designed to be easy to put together and solder using only one
surface mount component.

## BOM (Bill of Materials)

- 1x Promicro (or Compatible)
- 1x Micro USB Cable
- 1x XM7D-0512 MiniB (LCSC: C46398)
- 1x 6mm THT SPST Button
- 49x 1N4148 (LCSC: C14538)

If using LEDs:

- 49x 330 1/6w (LCSC: C119858)
- 49x 1.8mm LED (LCSC: C268275)
- 1x AO3402 (LCSC: C351406)
- 1x 100 1/6w (LCSC: C119846)
- 1x 10k 1/6w (LCSC: C119894)

## Layout

![KLE Layout Render](https://github.com/EvvL/Alchemy49/raw/master/Graphics/KLE.png)

Layout Render by [KLE-Render](http://kle-render.herokuapp.com/)

Click [this link](http://www.keyboard-layout-editor.com/#/gists/9abd5a1e1122fe68672f75864f8e92a3) for the KLE layout

## Firmware

For now QMK is currently supported via [KBFirmware.com](https://kbfirmware.com/). Just upload the included
[Configuration/kbfirmware.json](https://github.com/EvvL/Alchemy49/raw/master/Configuration/kbfirmware.json) into
the site, tweak the layout to your liking and compile. The resulting hex file should be flashable using
[AVRDUDESS](https://github.com/zkemble/AVRDUDESS) or [AVRDUDE](http://www.nongnu.org/avrdude/).

If you don't want to adjust anything you can use the [included prebuilt hex file](https://github.com/EvvL/Alchemy49/raw/master/Configuration/alchemy49.hex)
with all the same configuration as the stock MagicForce49 layout.

![AVRDUDESS Settings](https://github.com/EvvL/Alchemy49/raw/master/Graphics/AVRDUDESS.PNG)

## Renders

![Tracespace Render (Bottom)](https://github.com/EvvL/Alchemy49/raw/master/Graphics/Tracespace-Bottom.png)

![Tracespace Render (Top)](https://github.com/EvvL/Alchemy49/raw/master/Graphics/Tracespace-Top.png)

PCB Renders by [Tracespace](https://tracespace.io/view/)

## Copyright and Licensing

This project is licensed under the [Acheron Open-Source Hardware License V1.2](https://github.com/EvvL/Alchemy49/blob/master/LICENSE.md)

OSHWA Certification: [US000215](https://certification.oshwa.org/us000215.html)
