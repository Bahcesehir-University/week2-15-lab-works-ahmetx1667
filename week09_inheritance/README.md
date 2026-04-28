# 🔐 Lab: Object-Oriented Design in Cybersecurity Systems

**Course:** IST1012 – Computer Programming II (Python)
**Lab Number:** Lab 05  
**Estimated Duration:** 50 Minutes  
**Difficulty:** Intermediate  

---

## 📌 Objective of the Lab

This lab teaches students how to apply the four pillars of Object-Oriented Programming — **Inheritance, Polymorphism, Composition, and Abstract Base Classes (Interfaces)** — through a realistic cybersecurity scenario: building a modular **Threat Detection Framework**.

Students will move beyond reading theory and actively design, extend, and connect classes to simulate how professional security software is structured.

---

## 🧱 Prerequisites

Before starting this lab, students should be comfortable with:

- Writing Python classes with `__init__`, attributes, and methods
- Creating instances (objects) from a class
- Basic Python control flow: `for`, `if/else`, `return`
- Understanding what a method is and how `self` works

**No prior knowledge of OOP design patterns is required** — this lab introduces them from scratch.

---

## 🎯 What Students Will Learn

By the end of this lab, students will be able to:

1. Define and extend classes using **inheritance** to avoid repeating code
2. Apply **polymorphism** so that a single function works with many types
3. Use **composition** to build complex objects from smaller, focused components
4. Implement **abstract base classes** to enforce consistent interfaces across a codebase
5. Recognize when to use inheritance vs. composition in system design decisions

---

## 🗂️ Lab Structure

```
lab-oop-cybersecurity/
│
├── lab_oop_student.ipynb     ← Student version (no solutions)
├── lab_oop_teacher.ipynb     ← Instructor version (full solutions + notes)
└── README.md                 ← This file
```

### Section Breakdown

| Section | Content | Time |
|---|---|---|
| **Section 1 – Warm-Up** | 3 conceptual questions + small code recall task | ~8 min |
| **Section 2 – Core Concepts** | 4 concept blocks with runnable examples | ~10 min |
| **Section 3 – Guided Exercises** | 5 exercises (increasing difficulty) | ~25 min |
| **Section 4 – Challenge** | 2 harder problems (bonus eligible) | ~7 min |

---

## ⚙️ How to Run the Notebook

### Option 1 – Jupyter Notebook (Recommended)

```bash
# 1. Clone your GitHub Classroom repository
git clone https://github.com/your-classroom-org/lab05-YOUR_USERNAME.git
cd lab05-YOUR_USERNAME

# 2. Launch Jupyter
jupyter notebook

# 3. Open lab_oop_student.ipynb in your browser
```

### Option 2 – VS Code

1. Open VS Code and install the **Jupyter** extension (if not already installed)
2. Open the folder containing the notebook
3. Click on `lab_oop_student.ipynb`
4. Select your Python 3 interpreter when prompted

### Option 3 – Google Colab

1. Go to [https://colab.research.google.com](https://colab.research.google.com)
2. Click **File → Upload Notebook**
3. Upload `lab_oop_student.ipynb`
4. Run cells top to bottom using `Shift + Enter`

### Python Version

This lab is fully compatible with **Python 3.5+**. No external packages are required beyond the Python standard library (`abc` module is built-in).

---

## 📤 Submission Guidelines

1. Complete all exercises in `lab_oop_student.ipynb`
2. Make sure all cells have been **Run** (no empty output cells for code you wrote)
3. Answer all Markdown questions by double-clicking the cell and typing your response
4. Commit and push your completed notebook to your GitHub Classroom repository:

```bash
git add lab_oop_student.ipynb
git commit -m "Completed Lab 05 - OOP Cybersecurity"
git push origin main
```

5. Submit the repository link on the course portal by the deadline

**Do NOT submit** `lab_oop_teacher.ipynb` — that file is for instructor reference only.

---

## 📊 Grading Rubric

| Component | Points | What We're Checking |
|---|---|---|
| Warm-Up Q1–Q3 (written answers) | 6 | Conceptual accuracy, own words |
| Warm-Up Code Task | 4 | Object created, describe() called |
| Exercise 1 – Inheritance | 15 | `super()` used correctly, `describe()` overridden |
| Exercise 2 – Polymorphism | 15 | No `type()` checks, loop handles all alert types |
| Exercise 3 – Composition | 20 | `PasswordPolicy` logic correct, HAS-A pattern clear |
| Exercise 4 – Abstract Scanner | 20 | `BaseScanner` abstract, both subclasses complete |
| Exercise 5 – Framework Integration | 10 | Framework composes scanners, `full_report()` works |
| **Total** | **90** | |
| Challenge 1 (Bonus) | +5 | `dispatch()` works, `isinstance()` used appropriately |
| Challenge 2 (Bonus) | +5 | IS-A vs HAS-A reasoning is correct and well-argued |

### Grading Notes

- Partial credit is awarded for each exercise
- Code that has syntax errors but shows correct understanding may receive partial credit
- Warm-up conceptual answers are graded on clarity, not exact wording
- Challenge problems are strictly bonus — they do not affect students who do not attempt them

---

## ⏱️ Estimated Time Breakdown

| Task | Time |
|---|---|
| Setting up and running the environment | 2 min |
| Warm-up questions + code | 8 min |
| Reading and running Core Concept cells | 10 min |
| Exercise 1 (Inheritance) | 4 min |
| Exercise 2 (Polymorphism) | 4 min |
| Exercise 3 (Composition) | 6 min |
| Exercise 4 (Abstract Scanner) | 7 min |
| Exercise 5 (Framework integration) | 5 min |
| Challenge 1 & 2 (optional) | 4 min |
| **Total** | **~50 min** |

---

## 💡 Tips for Students

**Before you start:**
- Run the environment check cell first — if it fails, flag your instructor immediately
- Read each exercise description **twice** before writing code
- The Core Concepts section is your reference — keep it open in a side scroll

**While working:**
- Don't skip exercises. Each one builds on the previous.
- When you see `# YOUR CODE HERE`, replace the comment entirely — don't leave it in your final submission
- Test your code with the commented-out test lines before moving on
- If you're stuck, ask yourself: *Is this an IS-A or HAS-A relationship?*

**Common mistakes:**
- Forgetting to call `super().__init__()` in child class constructors
- Trying to instantiate an abstract class directly (Python will throw a `TypeError`)
- Using `if type(x) == SomeClass` instead of `isinstance(x, SomeClass)`
- Putting the solution logic in the wrong class (reread the task!)

**On the Challenge section:**
- Challenge 2 is a written design question — there is no single correct answer, but your reasoning must be grounded in IS-A vs HAS-A logic
- Attempt the challenges even if you're not 100% sure — partial credit counts

---


*IST1012 – Computer Programming II (Python)*  
*Lab materials maintained by the course instructor.*
