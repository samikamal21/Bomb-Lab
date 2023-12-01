# Bomb-Lab

A binary bomb is a program that consists of a sequence of phases. Each phase expects you to type a
particular string on stdin. If you type the correct string, then the phase is defused and the bomb
proceeds to the next phase. Otherwise, the bomb explodes by printing "BOOM!!!" and then
terminating. The bomb is defused when every phase has been defused.

## bomb.c
The bomb program that is to be run. It is programmed in a way such that you can't see what it's actually doing without looking at its x86 assembly

## bomb-assembly
The compiled assembly text file of bomb.c

## bomb-strings
The compiled file of all possible strings that bomb.c stores.

## gdb-methods-and-phase-notes
A text file with useful gdb methods to go through the bomb and my thought process and trials for defusing each phase.

## mysolutions.txt
The text file of all the solutions for the bomb.

## phase.txt files
Individual text files that only show the phases of the bomb.
