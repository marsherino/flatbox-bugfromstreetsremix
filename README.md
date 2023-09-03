# Flatbox, Bug from Streets™ Remix: a low profile, low cost leverless arcade controller with right thumb action button and simplified fourth column.

This repository contains 3D-printable models and the PCB design files needed to make an arcade controller that looks like this:

![Flatbox BFS Remix](hardware-rev5-UNDER-CONSTRUCTION/images/20230903_flatbox-bfs-image.jpg)

There are two versions of this controller on this Flatbox fork: one based on the architecture of the Flatbox rev4 (embedded RP2040 chip), and the other based on the Flatbox rev5 (Waveshare RP2040-Zero), both originally by jfedor2. The rev5 version of this remix is complete and available; the rev4 version is still in development.

Please see the READMEs for each version for instructions on component purchasing and assembly.

Both controllers run on [GP2040-CE firmware](https://gp2040-ce.info/) developed by the Open Stick Community and use Kailh low profile Choc v1 keyboard switches for both movement and action buttons.

Both controllers have five input modes: XInput, Nintendo Switch, PS3, PS4, and keyboard.

The table below lists each version's specifications.

version | [rev4] | [rev5]
------- | --------------------- | ---------------------
case dimensions | 218x130x10mm | 218x126x10mm
chipset | embedded RP2040 | [RP2040-Zero](https://www.waveshare.com/rp2040-zero.htm)
port | USB-C | USB-C
SMT assembly required | yes | no
