Sudoku Solver in Java

This project implements a Sudoku puzzle solver using recursive backtracking. It reads a Sudoku puzzle configuration from a text file, solves the puzzle, and prints the solution or reports if no solution exists.

## Features

- Reads puzzle input from a file with 9 lines of 9 integers (0 indicates empty cells).
- Efficiently checks validity of moves with row, column, and 3x3 subgrid bookkeeping.
- Recursive backtracking algorithm for solving Sudoku puzzles.
- Prints the initial puzzle and the solved puzzle in a clear grid format.
- ## Usage

1. Compile the program:
2. Run the program:
3. When prompted, enter the filename of the puzzle input file.

## Input File Format

- 9 lines, each with 9 integers separated by spaces.
- Each integer is between 0 and 9.
- 0 indicates an empty cell.

Example:5 3 0 0 7 0 0 0 0
6 0 0 1 9 5 0 0 0
0 9 8 0 0 0 0 6 0
8 0 0 0 6 0 0 0 3
4 0 0 8 0 3 0 0 1
7 0 0 0 2 0 0 0 6
0 6 0 0 0 0 2 8 0
0 0 0 4 1 9 0 0 5
0 0 0 0 8 0 0 7 9
## How It Works

- Uses boolean arrays to track values already present in each row, column, and 3x3 subgrid.
- Recursively tries all valid numbers for each empty cell until the puzzle is solved or no valid moves remain.

## Author

Your Name

---

Feel free to customize the author section or add any other info you want!

If you want, I can also help you create a sample input file or a test suite.
