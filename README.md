# Galactic Hitchhiker

[**>>> Play my BBC Micro version online <<<**](http://bbcmicro.co.uk//jsbeeb/play.php?autoboot&disc=https://raw.githubusercontent.com/ahope1/Galactic-Hitchhiker/main/beebify/gh.ssd)

This repo is a record of my "bare bones" conversion of A. Knight's 1980 text adventure game [Galactic Hitchhiker](https://ahopeful.wordpress.com/2022/04/09/galactic-hitchhiker-1980-inspo-a-go-go/). I took the original version, for the Compukit UK101, and modified it slightly so that it would run on the BBC Micro. 

Both the [Compukit UK101](https://en.wikipedia.org/wiki/Compukit_UK101) and the [BBC Micro](https://en.wikipedia.org/wiki/BBC_Micro) are computers that are built around the [6502 CPU](https://en.wikipedia.org/wiki/MOS_Technology_6502), and because Galactic Hitchhiker was distributed as 6502 machine code for the UK101, it only needed fairly minor changes to make it run on the Beeb. All of the game logic and the game data (messages, room descriptions, etc.) have been left unchanged.

(Still, because I'd only ever *dabbled* in 6502 machine code programming before now — never mind disassembly and reassembly — I personally found that the task of [converting](https://github.com/ahope1/Galactic-Hitchhiker/tree/main/beebify) the game was non-trivial.)

Read [my blogpost](https://ahopeful.wordpress.com/2022/04/09/galactic-hitchhiker-1980-inspo-a-go-go/) about Galactic Hitchhiker. 

## Code

The [***original-hex***](https://github.com/ahope1/Galactic-Hitchhiker/tree/main/original-hex) folder contains a plain-text representation of the 6502 machine code for the original UK101 version of Galactic Hitchhiker.

The [***disassembly***](https://github.com/ahope1/Galactic-Hitchhiker/tree/main/disassembly) folder contains an edited disassembly of the original UK101 6502 code for Galactic Hitchhiker. It can be reassembled using [*beebasm*](https://github.com/stardot/beebasm).

The [***beebify***](https://github.com/ahope1/Galactic-Hitchhiker/tree/main/beebify) folder contains the assembly code for my BBC Micro conversion of Galactic Hitchhiker. The assembly code is very similar to that for the UK101 version. It can be assembled using [*beebasm*](https://github.com/stardot/beebasm).
