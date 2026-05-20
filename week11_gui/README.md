# Lab: Recursion and GUI Programming

**Course:** IST1012 — Python Programming II
**Lab Duration:** ~40 minutes
**Lab Format:** Hands-on Jupyter Notebook

---

## 1. Objective of the Lab

The goal of this lab is to give you practical experience with two important Python topics: **recursion** and **GUI programming with `tkinter`**. You will write small recursive functions, build a simple graphical interface, and combine the two to create a mini security-themed tool.

---

## 2. Prerequisites

Before starting, you should be comfortable with:

- Basic Python syntax (variables, `if`/`else`, functions)
- Defining and calling functions
- Working with strings and basic arithmetic
- Running a Jupyter Notebook

**Software needed:**
- Python 3.5 or higher
- Jupyter Notebook or JupyterLab
- `tkinter` (included with standard Python on Windows/macOS; on Linux you may need `sudo apt install python3-tk`)

---

## 3. What Students Will Learn

By the end of this lab you will be able to:

1. Explain what recursion is and identify the base case and recursive case in a function.
2. Write recursive functions for counting, summing, and string manipulation.
3. Create basic GUI windows using `tkinter` (labels, entry fields, buttons).
4. Connect button clicks to Python functions.
5. Combine recursion and a GUI to build a small interactive security-flavored tool.

---

## 4. Lab Structure

The notebook is organized into four sections:

| Section | Topic | Time |
|---|---|---|
| 1 | Warm-up — conceptual questions and Python recall | 5 min |
| 2 | Core Concepts — recursion + `tkinter` basics with examples | 10 min |
| 3 | Guided Exercises — 4 progressively harder tasks | 20 min |
| 4 | Challenge — Recursive Password Length Checker GUI | 5 min |

All code is **Python 3.5 compatible** — no f-strings allowed.

---

## 5. How to Run the Notebook

1. Clone or download this repository.
2. Open a terminal in the lab folder.
3. Launch Jupyter:
   ```
   jupyter notebook
   ```
4. Open `Lab_Recursion_GUI_Student.ipynb`.
5. Run each cell from top to bottom using **Shift + Enter**.

> **Important:** When you run a `tkinter` cell, a new GUI window will open. **Close that window** before running the next `tkinter` cell, or Jupyter will appear to freeze.

---

## 6. Submission Guidelines

- Submit a single file: `Lab_Recursion_GUI_Student.ipynb`.
- Rename the file with your student ID, e.g. `Lab_Recursion_GUI_2025001.ipynb`.
- Make sure all cells have been **executed at least once** before submitting (your outputs should be visible).
- Submit through the course portal (GitHub Classroom / Moodle / as instructed).
- **Deadline:** as announced in class.

---

## 7. Grading Criteria (100 points)

| Section | Points |
|---|---|
| Warm-up answers (3 conceptual questions) | 10 |
| Task 1 — `sum_to` (recursive sum) | 15 |
| Task 2 — `count_chars` (recursive length) | 15 |
| Task 3 — `reverse_str` (recursive reverse) | 15 |
| Task 4 — Login Window GUI | 20 |
| Challenge — Password Length Checker GUI | 20 |
| Code quality (readable, runs without errors) | 5 |

**Deductions:**
- −5 points for using f-strings (must be Python 3.5 compatible).
- −5 points per recursive task that uses a loop or built-in shortcut (`len()`, `sum()`, `[::-1]`) instead of recursion.
- −3 points if a GUI is missing `window.mainloop()`.

---

## 8. Estimated Time Breakdown

| Activity | Time |
|---|---|
| Reading objectives and warm-up | 5 min |
| Following core concept examples | 10 min |
| Task 1 — recursive sum | 4 min |
| Task 2 — count characters | 4 min |
| Task 3 — reverse string | 4 min |
| Task 4 — login GUI | 8 min |
| Challenge | 5 min |

**Total: ~40 minutes**

---

## 9. Tips for Students

- **Start with the base case.** Always ask: "What is the simplest input, and what should I return for it?" Then write the recursive call.
- **Trace by hand.** For each recursive task, trace the calls for a small input (e.g. `count_chars("ab")`) on paper.
- **Close GUI windows** before running the next `tkinter` cell.
- **No f-strings.** Use `"Hello, " + name` or `"Hello, {}".format(name)`.
- **Read the error.** `RecursionError: maximum recursion depth exceeded` almost always means your base case is missing or wrong.
- **Don't cheat the recursion exercises.** Using `len()`, `sum()`, or `text[::-1]` defeats the point of the lab and loses points.

---

## 10. Files in This Repository

- `Lab_Recursion_GUI_Student.ipynb` — the lab notebook to complete and submit
- `README.md` — this file
- *(Instructor-only)* `Lab_Recursion_GUI_Teacher.ipynb` — full solutions and grading notes

---

*If you get stuck, ask your instructor or a lab assistant. Don't spend more than 5 minutes blocked on one task — move on and come back to it.*
