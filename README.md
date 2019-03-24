RetroText Viewdata/Teletext Font
================================

(C) 2019 Simon Waite
Licensed under the MIT License. See LICENSE for more details.

This is a retro-font inspired by the venerable ZX-Spectrum 8x8 font, and the Mode 7 BBC/SAA 5050 chip.

Format:
-------

Char Header
Line 0
...
Line 9
(Repeated per char 0x20...0x7F)

The character header
--------------------
* A Hex Number in 0xNN format of the character definition following
* A space, 0x20
* An optional Ascii char, if it's not printable a question mark is preferred



Enjoy!
