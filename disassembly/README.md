# Disassembly and reassembly

I disassembled the [6502 machine code](https://github.com/ahope1/Galactic-Hitchhiker/tree/main/original-hex) for the Compukit UK101 version of the game Galactic Hitchhiker, using [a browser-based 6502 disassembly tool](https://www.masswerk.at/6502/disassembler.html).

I then edited and reformatted the disassembled code, and I saved the result in the file [*assembly.txt*](https://github.com/ahope1/Galactic-Hitchhiker/blob/main/disassembly/assembly.txt), which can be reassembled by [*beebasm*](https://github.com/stardot/beebasm) into a binary file whose contents will be identical to [the original hex](https://github.com/ahope1/Galactic-Hitchhiker/tree/main/original-hex).

The files named "bin..." in this folder are binary files that are included by [*assembly.txt*](https://github.com/ahope1/Galactic-Hitchhiker/blob/main/disassembly/assembly.txt). *beebasm* will incorporate the binary files into the final executable, which a Compukit UK101 computer (or emulator) will then be able to load and run.

Now [see the BBC Micro conversion](https://github.com/ahope1/Galactic-Hitchhiker/tree/main/beebify) of the game. 
