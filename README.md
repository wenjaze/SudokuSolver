# SudokuSolver
Sudoku Solver in Python3 (console based)

# How it works?
- The program uses [a link](https://en.wikipedia.org/wiki/Backtracking)
## The process is the following:
  ### - Checks for the empty fields on the board
  ### - Gets empty field indicies and the index of the containing box.
  ### - Tries values from 1-9 to the given indices
  ### - Checking 3 positional statements if they contain the desired value:
    - BOX
    - ROW
    - COLUMN
  ### - If it fits to the given idices it places it to our board. Otherwise it replaces the last box with incremented values.
