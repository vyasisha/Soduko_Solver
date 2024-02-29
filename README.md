# Soduko_Solver
This is a simple Sudoku Solver implemented in Python.

## Description

The Sudoku Solver is a program that solves Sudoku puzzles using backtracking algorithm. It takes an unsolved Sudoku board as input and returns the solved board.

## How to Use

1. Define your unsolved Sudoku board in the `board` variable within the script `sudoku_solver.py`.
2. Run the Python script `sudoku_solver.py`.
3. The script will solve the Sudoku puzzle and print the solved board to the console.

## Features

- Solves Sudoku puzzles using backtracking algorithm.
- Supports 9x9 Sudoku boards.
- Prints the solved Sudoku board to the console.

## Example

```python
board = [
    [7,8,0,4,0,0,1,2,0],
    [6,0,0,0,7,5,0,0,9],
    [0,0,0,6,0,1,0,7,8],
    [0,0,7,0,4,0,2,6,0],
    [0,0,1,0,5,0,9,3,0],
    [9,0,4,0,6,0,0,0,5],
    [0,7,0,3,0,0,0,1,2],
    [1,2,0,0,0,7,4,0,0],
    [0,4,9,2,0,6,0,0,7]
]

print("Unsolved Sudoku Board:")
print_board(board)
solve(board)
print("\nSolved Sudoku Board:")
print_board(board)
```

## Requirements
Python 3.x

## How to Run
Clone the repository to your local machine:
bash
Copy code
git clone https://github.com/your-username/sudoku-solver.git
Navigate to the project directory:
bash
Copy code
cd sudoku-solver
Run the Python script:
bash
Copy code
python sudoku_solver.py

## Contribution
Contributions are welcome! If you'd like to contribute to this project, please create a pull request with your proposed changes.

## License
This project is licensed under the MIT License. See the LICENSE file for details.
