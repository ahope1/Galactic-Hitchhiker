# Galactic Hitchhiker

[**>>> Play my BBC Micro version online <<<**](http://bbcmicro.co.uk//jsbeeb/play.php?autoboot&disc=https://raw.githubusercontent.com/ahope1/Galactic-Hitchhiker/main/beebify/gh.ssd)

This repository documents my "bare bones" conversion of the 1980 text adventure game [Galactic Hitchhiker](https://bluerenga.blog/2021/11/04/galactic-hitchhiker-1980/) from the original version for the Compukit 101 computer to a minimally altered version that will run on the BBC Micro computer. 

Both the Compukit 101 and the BBC Micro are built around the [6502 CPU](https://en.wikipedia.org/wiki/MOS_Technology_6502): therefore, the game, which has been distributed as 6502 machine code for the UK101, only needed fairly minor changes to make it run on a BBC Micro. All of the game logic and the game data (messages, room descriptions, etc.) are unchanged.  But because I'd only ever dabbled in 6502 machine code previously (never mind disassembling and reassembling it), the conversion process was still quite a challenge for me personally.

## Code

The [***original-hex***](https://github.com/ahope1/Galactic-Hitchhiker/tree/main/original-hex) folder contains a plain-text representation of the 6502 machine code for the original UK101 version of Galactic Hitchhiker.

The [***disassembly***](https://github.com/ahope1/Galactic-Hitchhiker/tree/main/disassembly) folder contains an edited disassembly of the original UK101 6502 code for Galactic Hitchhiker. It can be reassembled using [*beebasm*](https://github.com/stardot/beebasm).

The [***beebify***](https://github.com/ahope1/Galactic-Hitchhiker/tree/main/beebify) folder contains the assembly code for my BBC Micro conversion of Galactic Hitchhiker. The assembly code is very similar to that for the UK101 version. It can be assembled using [*beebasm*](https://github.com/stardot/beebasm).
