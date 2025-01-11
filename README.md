# Sudoku Solver

This is a Python-based Sudoku Solver with a graphical user interface (GUI) built using `Tkinter`. It allows users to solve Sudoku puzzles using two algorithms: **AC-3** and **Backtracking**.

## Features
- Select from multiple difficulty levels: **Easy**, **Medium**, **Hard**.
- Choose from predefined Sudoku puzzles.
- Solve the puzzle using **AC-3** or **Backtracking** algorithms.
- Display the time taken to solve the puzzle.
- Provides a GUI for interactive use.

## Algorithms
- **AC-3 (Arc-Consistency Algorithm)**: A constraint satisfaction algorithm used to prune values that are inconsistent with the puzzle's constraints.
- **Backtracking**: A brute-force method of solving the puzzle by trying different numbers in empty cells and backtracking when an invalid configuration is found.

## Installation

1. Clone this repository:
    ```bash
    git clone https://github.com/yourusername/sudoku-solver.git
    cd sudoku-solver
    ```

2. Install required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the Sudoku Solver application:
    ```bash
    python sudoku_solver.py
    ```

## Usage

1. Select an algorithm from the dropdown (`AC-3` or `Backtracking`).
2. Choose the difficulty level (`Easy`, `Medium`, `Hard`).
3. Select the Sudoku puzzle you want to solve.
4. Click **Solve** to solve the puzzle. The solution and the time taken will be displayed.

## Example Puzzles
- **Easy Difficulty**:
    - Puzzle 1
    - Puzzle 2
    - Puzzle 3
    - Puzzle 4

- **Medium Difficulty**:
    - Puzzle 1
    - Puzzle 2
    - Puzzle 3
    - Puzzle 4

- **Hard Difficulty**:
    - Puzzle 1
    - Puzzle 2
    - Puzzle 3
    - Puzzle 4

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- The Tkinter library for the GUI interface.
- The AC-3 and Backtracking algorithms for solving the Sudoku puzzle.
