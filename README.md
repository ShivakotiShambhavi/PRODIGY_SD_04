# 🔢 Sudoku Solver (Backtracking Algorithm)

This Python program solves a standard 9x9 Sudoku puzzle using the **backtracking** algorithm. It takes a partially filled grid and attempts to solve it by placing valid numbers in empty cells, following Sudoku rules.

---

## 📌 Features

- Solves standard 9x9 Sudoku puzzles
- Implements efficient **recursive backtracking**
- Displays both the **unsolved** and **solved** puzzle in a clean format
- Easy to customize input puzzle

---

## 🧠 How It Works

The program follows these steps:

1. **Find Empty Cell**: Locates the first cell with a `0` (represents an empty spot).
2. **Try Numbers 1-9**: For each number, it checks:
   - If it's not in the same **row**
   - If it's not in the same **column**
   - If it's not in the same **3x3 box**
3. **Recursive Solve**: If a number is valid, it places the number and recursively attempts to solve the next cell.
4. **Backtracking**: If a dead-end is reached, it removes the number and tries the next possibility.

---

## 🧪 Example

### Input Puzzle

```
5 3 . . 7 . . . .
6 . . 1 9 5 . . .
. 9 8 . . . . 6 .
8 . . . 6 . . . 3
4 . . 8 . 3 . . 1
7 . . . 2 . . . 6
. 6 . . . . 2 8 .
. . . 4 1 9 . . 5
. . . . 8 . . 7 9
```

### Output Puzzle (Solved)

```
5 3 4 6 7 8 9 1 2
6 7 2 1 9 5 3 4 8
1 9 8 3 4 2 5 6 7
8 5 9 7 6 1 4 2 3
4 2 6 8 5 3 7 9 1
7 1 3 9 2 4 8 5 6
9 6 1 5 3 7 2 8 4
2 8 7 4 1 9 6 3 5
3 4 5 2 8 6 1 7 9
```

---

## 🛠️ Usage

### 1. Clone the repository or copy the script:
```bash
git clone https://github.com/yourusername/sudoku-solver.git
cd sudoku-solver
```

### 2. Run the Script
```bash
python sudoku_solver.py
```

### 3. Customize the Puzzle
Edit the `sudoku_grid` variable inside the script to insert a different puzzle. Replace `0` with empty cells.

---

## 📁 File Structure

```
sudoku_solver.py      # Main script with grid input, solver logic, and display
README.md             # Project documentation
```

---

## 👤 Author

**Shivakoti Shambhavi**  
© 2025 All Rights Reserved.

---

## 📜 License

This project is licensed under the MIT License. See `LICENSE` file for more details.

---

## 🤝 Contributing

Pull requests and suggestions are welcome!  
Feel free to open an issue for bugs or feature requests.