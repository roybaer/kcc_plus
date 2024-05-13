# KCC plus - a new, enhanced, CPC6128 compatible home computer

**WORK IN PROGRESS**

The _KCC plus_ is a retroactively designed hypothetical early 1990s successor to the KC compact.
The KC compact was a largely compatible clone of the Amstrad CPC 6128, built without custom silicon.

Once completed, it can be considered a cousin of, but not a clone of the Amstrad 6128 Plus.

## Planned feature set

The following hardware features are currently planned

- Between 256 KiB and 1024 KiB of RAM, ideally as a pair of SRAM chips
- Two AY-2-8910 PSGs for additional polyphony and additional control lines, on-board Digiblaster
- 16 bit data path for pixel generation and duplication of the relevant logic for twice the color depth
- Bypassable EGA-like latch in the second RAM chip's data path to keep block fill/copy operations fast
- At least one attribute mode, e.g. for colorful high-res pseudo text modes
- Possibility to optionally double the CPU clock and/or FDC clock, if feasible
- Floppy disk and tape interface
- Internal IDE and Serial ports, if feasible
- The CPC 6128's form factor: System board should fit inside a German CPC 6128 case
- High quality keyboard with n-key rollover
- 50-pin micro ribbon expansion port
- Bi-directional 8-bit printer port (DB25)
- DIN and SCART video output and 3.5 mm audio line-out
- Two digital joystick ports
- Light pen connector
- Laser-cut case, e.g. painted plywood

## Hardware components

These hardware components have been completed

- [Keyboard assembly](kcc_plus_keyboard/README.md) using the CPC 6128 form factor

These hardware components are planned

- Feature evaluation module for CPC
  - Clock generation and audio board
  - RAM and video board
  - Mass storage board
- System board
- Laser-cut case

## License

All design files contained herein may be redistributed and/or modified under the terms of the CERN-OHL-P license.
