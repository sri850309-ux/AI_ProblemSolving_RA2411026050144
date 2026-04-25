Sudoku Solver using CSP
Problem Description

Sudoku is a 9x9 grid-based puzzle where the objective is to fill the grid such that:

* Each row contains numbers from 1 to 9 without repetition
* Each column contains numbers from 1 to 9 without repetition
* Each 3x3 subgrid contains numbers from 1 to 9 without repetition

This project implements a Sudoku Solver using Artificial Intelligence techniques.

 Algorithm Used

Constraint Satisfaction Problem (CSP)

We model Sudoku as a CSP where:

* Variables → Empty cells
* Domain → Numbers (1–9)
* Constraints:

  * No repetition in row
  * No repetition in column
  * No repetition in 3×3 grid

Technique Used:

* Backtracking Search

Steps:

1. Find empty cell
2. Try numbers (1–9)
3. Check constraints
4. Recursively solve
5. Backtrack if invalid

 Execution Steps

1. Clone the repository:


git clone https://github.com/your-username/AI_ProblemSolving_<RegNo>


2. Navigate to sudoku folder:


cd sudoku


3. Run the program:


python app.py



Sample Input


5 3 0 | 0 7 0 | 0 0 0
6 0 0 | 1 9 5 | 0 0 0
0 9 8 | 0 0 0 | 0 6 0

Sample Output

5 3 4 | 6 7 8 | 9 1 2
6 7 2 | 1 9 5 | 3 4 8
1 9 8 | 3 4 2 | 5 6 7

 Features

* Solves Sudoku using AI
* Ensures all constraints are satisfied
* Backtracking-based efficient solution
* Extendable to GUI/Web

Website Link

https://github.com/sri850309-ux/AI_ProblemSolving_RA2411026050144/edit/main/README.md

Contributors

* SRI KRISHNAN
