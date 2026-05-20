# IST1012 Lab — Recursion in Python

## 1. Lab Title

**Recursion in Python: From Basics to Cybersecurity Applications**

## 2. Objective of the Lab

This lab introduces recursion as a programming technique and connects it to real-world cybersecurity scenarios. Students will learn to identify base cases and recursive cases, trace call stacks, and implement recursive solutions for string manipulation, exponentiation (relevant to cryptography), brute-force password generation, and file system scanning.

## 3. Prerequisites

Before starting this lab, students should be comfortable with:

- Writing and calling Python functions (`def`, `return`)
- Basic data types: strings, lists, integers
- Conditional statements (`if` / `else`)
- Running code in a Jupyter Notebook environment

No prior knowledge of recursion is required.

## 4. What Students Will Learn

| Objective | Exercise |
|-----------|----------|
| Define recursion and identify base/recursive cases | Warm-Up + Core Concepts |
| Trace recursive execution on the call stack | Core Concepts (factorial walkthrough) |
| Implement recursive functions for cybersecurity problems | Exercises 1–3 |
| Apply recursion to nested data structures | Challenge (directory scanner) |

## 5. Lab Structure

The lab is divided into four parts designed to fit within a 60-minute session:

| Part | Section | Duration | Description |
|------|---------|----------|-------------|
| 1 | Warm-Up | 5–10 min | Conceptual questions and a small code trace |
| 2 | Core Concepts | 10–15 min | Short explanations with code examples (factorial, list sum) |
| 3 | Guided Exercises (×3) | 25–30 min | Hands-on coding with increasing difficulty |
| 4 | Challenge | 10 min | Optional advanced problem (recursive directory scanner) |

## 6. Instructions — How to Run the Notebook

### Option A: Local (Anaconda / Jupyter)

```bash
# 1. Make sure Jupyter is installed
pip install notebook

# 2. Navigate to the lab folder
cd path/to/lab/

# 3. Launch Jupyter
jupyter notebook IST1012_Recursion_Lab_Student.ipynb
```

### Option B: Google Colab

1. Go to [colab.research.google.com](https://colab.research.google.com)
2. Click **File → Upload notebook**
3. Upload `IST1012_Recursion_Lab_Student.ipynb`
4. Work through the cells from top to bottom

### Option C: GitHub Classroom (if configured)

1. Accept the assignment link provided by your instructor.
2. Clone the repository to your machine or open it in the cloud IDE.
3. Complete the notebook and push your changes before the deadline.

## 7. Submission Guidelines

1. Complete all exercises directly in the notebook (replace every `pass` with your code).
2. Run all cells to make sure there are no errors.
3. **Save** the notebook (`Ctrl+S` / `Cmd+S`).
4. Submit the `.ipynb` file through the course LMS (Canvas / Blackboard / GitHub Classroom) by the posted deadline.
5. Late submissions follow the policy stated in the syllabus.

## 8. Grading Criteria

| Component | Points | Criteria |
|-----------|--------|----------|
| Exercise 1 — String Reversal | 30 | Correct recursive implementation; handles empty and single-char strings |
| Exercise 2 — Power Function | 30 | Correct recursive implementation; handles `exp = 0` and `exp = 1` |
| Exercise 3 — Password Generator | 30 | Returns all combinations; correct base case; no use of `itertools` |
| Challenge — Directory Scanner | 10 (bonus) | Correctly traverses nested dicts; filters by extension |
| **Total** | **100** | |

**Deductions:**
- Using loops instead of recursion for the core logic: −50% on that exercise
- Using forbidden built-ins (`[::-1]`, `**`, `pow`, `itertools`): −50% on that exercise
- Code does not run (syntax errors): −100% on that exercise

## 9. Estimated Time Breakdown

```
 0:00 – 0:10   Part 1: Warm-Up
 0:10 – 0:25   Part 2: Core Concepts (read, run examples)
 0:25 – 0:35   Exercise 1: Recursive String Reversal
 0:35 – 0:45   Exercise 2: Recursive Power Function
 0:45 – 0:55   Exercise 3: Recursive Password Generator
 0:55 – 1:00   Challenge (bonus) + Wrap-Up
```

## 10. Tips for Students

- **Start with the base case.** Ask yourself: "What is the simplest input where I already know the answer?" That is your base case.
- **Trust the recursion.** Assume the recursive call works correctly for a smaller input. Your job is only to handle the current step.
- **Trace by hand.** If your code is not working, write out the calls on paper for a small input (e.g., `n = 3`). This almost always reveals the bug.
- **Test incrementally.** Run your function with the simplest test case first before trying complex inputs.
- **Do not be afraid of `RecursionError`.** It just means you are missing a base case or not making the problem smaller. Fix the base case and try again.
- **Ask for help early.** If you are stuck for more than 5 minutes on one exercise, raise your hand or post in the course chat.

---

*IST1012 — Computer Programming II | Lab: Recursion*
