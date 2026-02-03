# CodeAlpha_Sudoku-Solver
solve any sudoku puzzle easily and gets hint also to solve it

# Sudoku Solver (C++)

A **Sudoku Solver** implemented in **C++** using the **Backtracking algorithm**.  
The program takes a partially filled 9×9 Sudoku grid and finds a valid solution if one exists.

---

## 🧩 Features

- Solves standard **9×9 Sudoku**
- Uses **Backtracking**
- Checks:
  - Row constraints
  - Column constraints
  - 3×3 subgrid constraints
- Simple console-based input/output

---

## 🛠️ Technologies Used

- C++
- Recursion
- Backtracking Algorithm
- Standard Library (`<iostream>`)

---

## 📂 File Structure

sudoku-solver-cpp/
│
├── Sudoku_Solver.cpp
└── README.md


---

## 📥 Input Format

- Enter the Sudoku puzzle row-wise
- Use **0** to represent empty cells

### Example Input:

3 0 6 5 0 8 4 0 0

5 2 0 0 0 0 0 0 0

0 8 7 0 0 0 0 3 1

0 0 3 0 1 0 0 8 0

9 0 0 8 6 3 0 0 5

0 5 0 0 9 0 6 0 0

1 3 0 0 0 0 2 5 0

0 0 0 0 0 0 0 7 4

0 0 5 2 0 6 3 0 0


---

## 📤 Output

Solved Sudoku:
3 1 6 5 7 8 4 9 2

5 2 9 1 3 4 7 6 8

4 8 7 6 2 9 5 3 1

2 6 3 4 1 5 9 8 7

9 7 4 8 6 3 1 2 5

8 5 1 7 9 2 6 4 3

1 3 8 9 4 7 2 5 6

6 9 2 3 5 1 8 7 4

7 4 5 2 8 6 3 1 9


---

## 🧠 Algorithm Used

Backtracking

Try numbers 1–9 in empty cells

Check validity

Recursively continue

Backtrack if no valid number fits

---

## 🎯 Learning Outcomes

Understanding recursion

Implementing backtracking

Grid-based problem solving

Constraint checking logic


## ▶️ How to Compile and Run

### Step 1: Compile
```bash
g++ Sudoku_Solver.cpp -o sudoku

---

### Step 1: Run
./sudoku

---


## 👨‍💻 Author

Ujjwal Pandit


