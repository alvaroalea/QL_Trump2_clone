# GAL Equations and JEDEC files

## Chip 2

This chip manage the Dinamic RAM access, and I can't decypher its operation, provide a PDF and JED from tetroid, and my own try in a PLD file (for compiling with GALASM)

## Chip 1

### TC2_1V4
This JED/Equations are a barely working files, to be used only with a Minerva ROM, not incorporate the mechanism of ROM  pagging need with JS ROMs

This files are for compiling with WinCulp

### TC2_1V5
This PLD files are for compile with GALASM

They incorporate the mechanism to pagged ROM in 0xC0000 on boot to allow JS ROM to start.

There are 4 combinations, and depend on the installed memory, but only 0Kb has been tested as working.
