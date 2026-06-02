# IST1012 Lab — Advanced Recursion + GUIs in Python

## 1. Lab Title

**Advanced Recursion + GUIs: From Tree Traversal to a Working Security Tool**

## 2. Objective of the Lab

This lab extends your earlier recursion work. You will move past linear recursion into
**nested-tree traversal** and **recursive backtracking**, then connect a recursive function to
a small **Tkinter GUI** so a non-programmer could run it. The running theme is practical
security tooling: searching a file tree, brute-forcing a fixed-length PIN, and auditing
file permissions.

## 3. Prerequisites

- Completion of the introductory recursion lab (base case / recursive case)
- Comfort with functions, loops, lists, dictionaries, and tuples
- A **local** Python 3 install with Tkinter (ships with standard CPython) for Exercise 3
- Jupyter Notebook installed locally

> Exercise 3 opens a real desktop window and will **not** render in Colab. Do Exercise 3 on a
> local machine.

## 4. What Students Will Learn

| Outcome | Where |
|---|---|
| Recurse over nested/tree data structures | Warm-Up, Core, Exercise 1 |
| Implement recursive backtracking with early return | Exercise 2 |
| Wire a recursive function to a Tkinter GUI | Exercise 3 |
| Build result paths while descending a tree | Challenge |

## 5. Lab Structure

| Part | Section | Duration | Description |
|---|---|---|---|
| 1 | Warm-Up | 5 min | Recall + trace a nested-list counter |
| 2 | Core Concepts | 8 min | Tree recursion, backtracking, GUI glue |
| 3 | Guided Exercises (×3) | 25 min | find_file → PIN cracker → GUI cracker |
| 4 | Challenge | 7 min | Recursive permission audit (optional) |

**Total: ~45 minutes**

## 6. How to Run the Notebook

### Local (recommended — required for Exercise 3)
```bash
pip install notebook
cd path/to/lab/
jupyter notebook IST1012_Recursion_GUI_Lab_Student.ipynb
```

### Google Colab (Exercises 1, 2, and Challenge only)
1. Open [colab.research.google.com](https://colab.research.google.com)
2. **File → Upload notebook** → choose the student `.ipynb`
3. For Exercise 3, write the handler logic in comments instead of running the window.

### GitHub Classroom
1. Accept the assignment link from your instructor.
2. Clone or open the repo, complete the notebook, and push before the deadline.

## 7. Submission Guidelines

1. Replace every `pass` / `# TODO` with your own code.
2. Keep your test `print` statements so output is visible.
3. For Exercise 3, include a screenshot of the running window (or commented logic if on Colab).
4. Submit `IST1012_Recursion_GUI_Lab_Student.ipynb` with all cells run, named
   `lastname_firstname_recursion_gui.ipynb`.

## 8. Grading Criteria (100 points)

| Criterion | Points |
|---|---|
| Exercise 1 — `find_file` (correct recursion + early return) | 25 |
| Exercise 2 — `crack` (backtracking, returns on first success) | 30 |
| Exercise 3 — GUI wired correctly, reuses `crack` | 30 |
| Warm-Up answers + correct prediction | 15 |
| Challenge — correct risky-file paths | +15 (bonus) |

## 9. Estimated Time Breakdown

| Activity | Time |
|---|---|
| Warm-Up | 5 min |
| Core Concepts | 8 min |
| Exercise 1 | 7 min |
| Exercise 2 | 9 min |
| Exercise 3 | 9 min |
| Challenge | 7 min |

## 10. Tips for Students

- **Draw the tree.** Before coding Exercise 1, sketch the folders and files on paper.
- **Return the recursive call.** The #1 bug is calling the function recursively but forgetting
  to `return` its result.
- **Backtracking = return only on success.** In Exercise 2, a failed branch returns `None`;
  only a real hit should propagate up.
- **Keep recursion out of the button.** In Exercise 3, the GUI handler should *call* `crack`,
  not contain the recursion itself.
- **Python 3.5 only.** No f-strings — use `"text " + variable` or `.format()`.
