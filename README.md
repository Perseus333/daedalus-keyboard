# Daedalus Keyboard

Daedalus is a compact open-source, split, wireless ergonomic keyboard with trackpad and encoder.

![Image](/assets/main-img.jpg)

## Daedalus Keyboard

It's a 36 key low-profile, split, wireless, ergonomic keyboard that includes a trackpad and a rotary encoder powered with ZMK on 2 Nice!Nano microcontrollers running on 2 110mAh batteries. It features a key splay inspired from the TOTEM, and a key layout modelled after my hand and inspired by the Corne. It's meant to be portable, silent and unobstrusive thanks to the Ambient Twighlight silent switches and the wireless connectivity.

## Mission

The Daedalus Keyboard has been a hobby project that I worked on during the last year. It has been my first real hardware project that I've done, and I learned a lot throughout the way. Therefore, I aim for this project to be the most open and educational keyboard project possible for everyone.

Therefore, here you will find everything needed to get started or to satiate your curiosity: all of the code, the schematics, the CAD files and even my notes during research.

If you're interested in building your own keyboard, then the [report](/docs/report.pdf) might interest you. It is a compreheensive document that describes the whole process of creation of the keyboard step by step, whilst giving some useful tips throughout and some valuable lessons learned at the end.

## Repository Navigation

The repository is split in the following directories:

- **Chassis**: Everything related to the chassis and components that are not hardware - CAD files, drawings and files ready for 3D printing or laser cutting right away
- **Hardware**: Related to the PCB and electronic components - KiCAD schematic and PCB, and even gerber files to submit to a PCB manufacturer
- **Firmware**: The code necessary to run the keyboard - Keybinds, ZMK config, etc.
- **Docs**: The documentation to help you get started building this keyboard or any other - Build log, BOM, research, etc.

## Current development

Currently I'm working on adding to this repository the following, in order:

- Porting the CATIA files into an open source file format
- A standalone step by step build guide (& BOM)
- A contributing/editing guide
- Publishing the Drawings

## Contributing

You're welcome to contribute to this project in any way shape or form that is constructive.

## Licence

This project is licenced differently for each domain, with the intention of promoting open source hardware and software:

- Firmware and code: [GNU Affero General Public License v3 (AGPLv3)](./LICENSE-FIRMWARE)
- Hardware: [CERN Open Hardware License v2 - Strongly Reciprocal](./LICENSE-HARDWARE)
- Documentation and Media: [Creative Commons Attribution-ShareAlike 4.0](https://creativecommons.org/licenses/by-sa/4.0/)
