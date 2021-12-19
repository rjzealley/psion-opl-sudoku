# psion-opl-sudoku
Sudoku solver for Psion PDAs written in OPL
Author: unkown
Date: 1990s

A while back I bought of set of development software and books on eBay. Incuded with this was a box of floppies containing some OPL code, including this sudoku solver. 

I take no credit for the code and unfortunately there's no clue as to the original author. If it's you, I'd love to hear from you.

There are two files: SUDOKU1.OPL and SUDOKU2.OPL. On your Psion PDA, compile both and run SUDOKU1.OPO.

The simple menu has 4 choices which require upper case responses:
L : Load a puzzle
S : Save a puzzle (see below)
E : End program
Esc : start solving

When saving, enter a 3 digit puzzle number, e.g. 123, and the file will saved in /OPD/ as SUD123.DAT. On completion of the puzzle a file named SUD123F.DAT is created containing the solved puzzle.

