# 🧩 Sudoku Solver & Generator using CSP  
### 🎯 AC-3 + Backtracking | 🖥️ Interactive GUI

✨ This project implements a complete **Sudoku Solver & Generator** using **Constraint Satisfaction Problems (CSP)**.  
It combines **🧠 Arc Consistency (AC-3)** with **🔁 Backtracking Search** to efficiently solve Sudoku puzzles and generate **valid, solvable boards** with different difficulty levels.  
A clean **🎮 Tkinter GUI** is included for playing, validating, and solving puzzles interactively.

---

## 🧠 Concept & Idea
Sudoku is modeled as a **CSP problem** where:
- 🧩 Each cell is a **variable**
- 🔢 Domain = `{1..9}`
- 🚫 Constraints apply to **rows, columns, and 3×3 subgrids**

The solver first applies **⚡ AC-3** to reduce domains and detect conflicts early, then uses **🔁 Backtracking** to complete the solution.

---

## ✨ Features
✅ **Sudoku Generator**
- 🎯 Three difficulty levels: 🟢 Easy | 🟡 Medium | 🔴 Hard  
- 🔐 Guarantees solvable puzzles

🧠 **Sudoku Solver**
- ⚡ AC-3 for domain reduction  
- 🔁 Backtracking for completeness  
- ❌ Detects invalid or unsolvable boards

🎮 **Graphical User Interface**
- 🎨 Clean and simple design  
- 🔢 Real-time input validation (1–9 only)  
- 🚨 Highlights rule violations  
- 🧩 Buttons: New Game | Check Board | Solve Automatically

---

## 🧪 Algorithms Used
🧠 **Arc Consistency (AC-3)**
- Removes inconsistent values from domains  
- Detects conflicts early  
- Improves backtracking performance

🔁 **Backtracking Search**
- Recursive depth-first search  
- Ensures all Sudoku constraints are satisfied  
- Used for both solving and generation

---

## 🚀 How to Run
🛠️ **Requirements**
- Python **3.8+**

▶️ **Steps**

git clone https:(https://github.com/Ziad-Bahaa2006/Assignment-3---CSP-to-Solve-Sudoku)  

cd Sudoku-CSP  

python gui.py

---

## 🎓 Educational Value
📚 Perfect for:
- Artificial Intelligence courses  
- Constraint Satisfaction Problems (CSP)  
- Understanding AC-3 & Backtracking practically  
- Academic projects & demonstrations

---

## 👥 Team Members
🤝 This project was developed as a **team effort** by:

- 👤 **Mohamed Ahmed Elmesarea** – CSP Modeling & Arc Consistency  
- 👤 **Ziad Bahaa Elsayed** – Backtracking Solver & Puzzle Generator  
- 👤 **Mohamed Islam Ibrahim** – GUI Development & Integration  

---

## 🚧 Future Improvements
🚀 Solution uniqueness detection   
🎞️ Animated solving visualization   
📊 Performance & time analysis    
📁 Export puzzles & solutions  

---

## 📜 License
🆓 Open-source project for **educational use**
