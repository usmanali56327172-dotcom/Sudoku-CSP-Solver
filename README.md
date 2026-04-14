Sudoku CSP Solver 
Course
AI 2002 – Artificial Intelligence
Description

This project implements a **Constraint Satisfaction Problem (CSP)** based Sudoku solver using:

* Backtracking Search
* Forward Checking (via constraint validation)

The solver can handle Sudoku puzzles of varying difficulty levels:


* Easy
* Medium
* Hard
* Very Hard

Features

* Solves 9x9 Sudoku boards
* Uses recursive backtracking
* Tracks:

  * Number of backtrack calls
  * Number of failures
* User selects difficulty at runtime

How to Run

1. Make sure Python is installed
2. Run the program:

```bash
python solver.py
```

3. Choose difficulty:

```
1 → Easy  
2 → Medium  
3 → Hard  
4 → Very Hard  
```
Output Example

```
Solved Sudoku:

[7, 8, 4, 9, 3, 2, 1, 5, 6]
...

Backtrack calls: 229
Failures: 179
```

Observations

* **Easy:** Minimum backtracking due to strong constraints
* **Medium:** Moderate backtracking
* **Hard:** Increased search effort
* **Very Hard:** Maximum backtracking due to fewer initial clues

 Author

Muhammad Usman
