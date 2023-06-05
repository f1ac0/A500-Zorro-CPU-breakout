# A500-Zorro-CPU-breakout
This is a breakout PCB with a DIP64 68000 CPU socket that plugs into the Amiga 500 expansion port. It has no active part and is designed to just move the original 68000 outside the system, host a 68000 CPU replacement, or an expansion designed to seat under the CPU. It should be helpful for design and test purposes, and may use a ZIF-64 socket.

It is designed as a 2 layers board and to fit in the dimensions for cheap PCB manufacturing ; because of this it requires an additional small board for the power pins of the expansion connector (or two additional wires).

Beware that the 68000 is rotated 180° from how it is on the A500 motherboard : its pin 1 is on the top left instead of bottom right. This made the PCB routing a bit more complicated but should allow to install the boards that normally expand over the ROM or Denise chips.

If your CPU replacement does not use bus arbitration to take over the 68k bus, then the CPU on the A500 motherboard must be removed.

Depending on your A500 motherboard revision, you may have to close its JP6 jumper to feed the 7MHz clock to the expansion connector.

# Disclaimer
This is a hobbyist project, it comes with no warranty and no support. Also remember that the Amiga machines are about 30 years old and may fail because of such hardware expansions.

I publish my work under the CC-BY-NC-SA license.

If you find it useful and want to reward my hard work : I am always looking for Amiga/Amstrad CPC/Commodore hardware to repair and hack, please contact me.

