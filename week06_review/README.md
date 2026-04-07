# Lab 3: Inheritance, Polymorphism, and Composition

## IST1012 — Python Programming II | Difficulty: Above Medium

---

## Objective

This lab introduces three powerful OOP concepts: **inheritance** (building
specialized classes from general ones), **polymorphism** (using a single
interface to operate on different types), and **composition** (building
complex objects from simpler components). Students will apply these
patterns to realistic cybersecurity scenarios.

## Prerequisites

- Completion of Labs 1 and 2
- Python 3.5 or later, Jupyter Notebook
- Solid understanding of: classes, objects, `__init__`, methods,
  encapsulation, getters/setters

## What Students Will Learn

| # | Skill |
|---|-------|
| 1 | Create parent and child classes with inheritance |
| 2 | Override methods for specialized behavior |
| 3 | Use polymorphism to process heterogeneous collections |
| 4 | Apply composition to build modular systems |
| 5 | Design a plugin-style architecture |

## Lab Structure

| Section | Time | Description |
|---------|------|-------------|
| Warm-Up | 5-10 min | Motivate inheritance, review isinstance |
| Core Concepts | 10-15 min | Inheritance, polymorphism, composition |
| Guided Exercises | 25-30 min | 4 tasks building on each concept |
| Challenge | 10 min | Plugin-style log analyzer framework |

## How to Run the Notebook

1. Clone or download this repository.
2. Open a terminal in the lab folder.
3. Run `jupyter notebook Lab3_Advanced_Student.ipynb`
4. Complete all cells in order.

## Submission Guidelines

- Complete all exercises.
- Run Kernel -> Restart & Run All to ensure no errors.
- Submit the `.ipynb` file via the course portal.

## Grading Criteria

| Criterion | Points |
|-----------|--------|
| Warm-up questions | 10 |
| Exercise 1 — Scanner hierarchy + polymorphism | 15 |
| Exercise 2 — Router with super() | 15 |
| Exercise 3 — Alert Dashboard (composition) | 20 |
| Exercise 4 — Credential Vault (inheritance + composition) | 20 |
| Challenge — Plugin-style analyzer | 15 |
| Code style and readability | 5 |
| **Total** | **100** |

## Estimated Time Breakdown

- Warm-up: ~7 minutes
- Core concepts: ~13 minutes
- Exercises 1-4: ~27 minutes
- Challenge: ~10 minutes
- Review: ~3 minutes

## Tips for Students

- Draw diagrams on paper: boxes for classes, arrows for inheritance.
- Ask yourself: "is-a" or "has-a"? That decides inheritance vs composition.
- Test each class independently before combining them.
- Use `isinstance()` to verify your inheritance hierarchy.
- The challenge is designed to stretch you — partial credit is available.
