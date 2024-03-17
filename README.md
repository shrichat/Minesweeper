Fully working Minesweeper code:

The program prompts the user for a command. Each command is three characters in the form of “aij”:

● “a” can be “f” for flag, “r” for reveal, or “u” for undo, and
● “i” and “j” determine the row and column indices, respectively. The row and
column numbers begin at 0.
For example, user input of “f12” means that they would like to flag the cell in the second row and third column.
● The flag command is similar to right-clicking on the web-based version, which puts the flag sign on a cell.
● The undo command removes the flag from the cell specified, assuming you incorrectly assigned the flag and you have figured out your mistake and want to undo it.
● The reveal command opens the specified cell (left-click in the web-based version), displaying the number of mines in the surrounding cells as the value of the selected cell. If you reveal a cell that is a mine, the field explodes!

