# Lab 2: Encapsulation and Class Interaction

## IST1012 — Cybersecurity Fundamentals | Difficulty: Medium

---

## Objective

This lab builds on Lab 1 by introducing **encapsulation** — the practice
of protecting an object's internal data from unauthorized or invalid
modification. Students will also learn to design classes that work
together, a key skill for building security tools.

## Prerequisites

- Completion of Lab 1 (Classes and Objects basics)
- Python 3.5 or later, Jupyter Notebook
- Understanding of: classes, `__init__`, attributes, methods

## What Students Will Learn

| # | Skill |
|---|-------|
| 1 | Mark attributes as private using underscore convention |
| 2 | Write getter/setter methods with validation |
| 3 | Design classes that interact with each other |
| 4 | Build a rate-limited authentication system |

## Lab Structure

| Section | Time | Description |
|---------|------|-------------|
| Warm-Up | 5-10 min | Why direct attribute access is dangerous |
| Core Concepts | 10-15 min | Private attrs, getters/setters, class interaction |
| Guided Exercises | 25-30 min | 4 tasks with increasing complexity |
| Challenge | 10 min | Rate-limited login system |

## How to Run the Notebook

1. Clone or download this repository.
2. Open a terminal in the lab folder.
3. Run `jupyter notebook Lab2_Medium_Student.ipynb`
4. Complete each cell in order.

## Submission Guidelines

- Complete all exercises.
- Run Kernel → Restart & Run All to ensure no errors.
- Submit the `.ipynb` file via the course portal.

## Grading Criteria

| Criterion | Points |
|-----------|--------|
| Warm-up questions | 10 |
| Exercise 1 — UserProfile with validation | 20 |
| Exercise 2 — TokenBucket | 15 |
| Exercise 3 — Firewall (two classes) | 20 |
| Exercise 4 — AuditTrail | 15 |
| Challenge — SecureAuthSystem | 15 |
| Code style and readability | 5 |
| **Total** | **100** |

## Estimated Time Breakdown

- Warm-up: ~8 minutes
- Core concepts: ~12 minutes
- Exercises 1-4: ~25 minutes
- Challenge: ~10 minutes
- Review: ~5 minutes

## Tips for Students

- Always validate input in setter methods — never trust the caller.
- Use `_` prefix consistently for private attributes.
- When two classes interact, keep responsibilities clear.
- Test edge cases: empty inputs, repeated calls, boundary values.
