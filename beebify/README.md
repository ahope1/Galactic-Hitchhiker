# Conversion to the BBC Micro

I edited [my reconstructed assembly code](https://github.com/ahope1/Galactic-Hitchhiker/tree/main/disassembly) for the Compukit UK101 version of the game Galactic Hitchhiker and adapted it into a version ([*beebify assembly.txt*](https://github.com/ahope1/Galactic-Hitchhiker/blob/main/beebify/beebify%20assembly.txt)) that would run on the BBC Micro, once reassembled by *beebasm*. Large chunks of the assembly code are unchanged because they can run unaltered on both the UK101 and the BBC Micro. 

Click [this link](https://github.com/ahope1/Galactic-Hitchhiker/commit/5652229d51ea682a2fcbd538a720b9c07396810b) to see the main differences between the UK101 code and the BBC Micro code. (I may  have made further changes, subsequent to those revealed by that link. See this repo's full commit history for details.) 

The "bin..." files that are referred to in [*beebify assembly.txt*](https://github.com/ahope1/Galactic-Hitchhiker/blob/main/beebify/beebify%20assembly.txt) can be found in the [*disassembly*](https://github.com/ahope1/Galactic-Hitchhiker/tree/main/disassembly) folder.

The file [*ght.ssd*](https://github.com/ahope1/Galactic-Hitchhiker/blob/main/beebify/ght.ssd) is a BBC Micro disc-image that serves as a template for the final disc-image onto which *beebasm* will store the assembled game code.

The *beebasm* command that I used to create the final disc-image (gh.ssd) was *beebasm -v -i beebify\ assembly.txt -di ght.ssd -do gh.ssd -o gh*
