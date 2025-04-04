# 🧩 Sudoku Solver - C++ Solution

A C++ based Sudoku Solver that leverages the power of Depth First Search (DFS) to efficiently solve any 9x9 Sudoku puzzle. This project demonstrates the use of backtracking to fill in the puzzle's empty cells (denoted by 0) and find a valid solution.

![sudoku-icon](https://img.icons8.com/external-flat-juicy-fish/64/000000/external-sudoku-puzzle-game-external-flat-flat-juicy-fish.png)

---

## 🚀 Features

- Solves 9x9 Sudoku puzzles using the DFS algorithm.
- Prints the solved board to the console.
- Works with any valid Sudoku input (empty cells are represented by 0).

---

## 🛠️ How to Use

### 1. Clone the Repository

To get started, first clone this repository to your local machine:

`bash
git clone https://github.com/yourusername/sudoku-solver.git

## 💡 How It Works

The algorithm uses a backtracking approach to try different possibilities for each empty cell in the puzzle. Here's how the process works:

- Step 1: For each empty cell (0), try placing numbers 1–9.
- Step 2: Check if the number is safe (i.e., doesn't violate Sudoku rules).
- Step 3: If valid, continue with the next cell.
- Step 4: If a conflict is found, backtrack and try the next number.
- Step 5: Repeat until the entire board is filled or no solution exists.

## 📋 Code Explanation

- **solveSudoku()**: The main function that solves the puzzle using DFS and backtracking.
- **isSafe()**: A helper function to check if a number can be placed in a specific cell without violating Sudoku rules (no duplicates in row, column, or subgrid).
- **printBoard()**: Prints the solved Sudoku board to the terminal.

## 🧑‍💻 Contributing

We welcome contributions to this project! If you'd like to improve or extend the functionality, feel free to fork the repo and submit a pull request.

How to contribute:
1. Fork the repository.
2. Create a new branch (git checkout -b feature-branch).
3. Make your changes and commit (git commit -m "Add feature").
4. Push your changes to your fork (git push origin feature-branch).
5. Open a Pull Request.