# IST1012 Lab: Advanced Data Sequences, Dictionaries, and Sets

## 📋 Lab Overview

This hands-on lab explores Python's core data structures—lists, tuples, dictionaries, and sets—through a cybersecurity lens. Students will discover tricky behaviors, unique use cases, and advanced techniques that go beyond introductory material.

**Course:** IST1012 - Computer Programming II
**Format:** Jupyter Notebook (interactive)

---

## 🎯 Objectives

By the end of this lab, students will be able to:

1. Identify and explain mutable vs. immutable behavior in Python data structures
2. Apply advanced slicing, unpacking, and comprehension techniques
3. Use dictionary methods for efficient data lookups and merging
4. Leverage set operations for security analysis (intersection, difference, symmetric difference)
5. Recognize common pitfalls and tricky behaviors that can cause bugs in security code

---

## 📚 Prerequisites

Before starting this lab, students should have:

- [ ] Basic Python syntax knowledge (variables, functions, loops, conditionals)
- [ ] Understanding of basic list and dictionary operations
- [ ] Jupyter Notebook installed (or access to JupyterHub/Google Colab)
- [ ] Python 3.5 or higher installed

**Recommended Review:**
- Python list basics (indexing, appending, iteration)
- Dictionary key-value pairs
- Basic function definitions

---

## 📖 What Students Will Learn

### Core Concepts
| Topic | Skills Gained |
|-------|---------------|
| **Mutability** | Distinguish between mutable/immutable types; avoid reference bugs |
| **Advanced Slicing** | Extract data using `[start:stop:step]`, negative indices, reversing |
| **Tuple Unpacking** | Use `*` operator, swap variables, parse structured data |
| **Dictionary Methods** | Safe lookups with `.get()`, `.setdefault()`, `.update()` |
| **Set Operations** | Intersection `&`, difference `-`, symmetric diff `^`, union `|` |
| **Comprehensions** | Build dicts and sets efficiently with comprehension syntax |

### Cybersecurity Applications
- Parsing firewall and IDS logs
- Tracking failed login attempts by IP
- Comparing user access across systems
- Detecting unauthorized network ports
- Building IP reputation systems
- Analyzing password strength

---

## 🏗️ Lab Structure

| Section | Duration | Description |
|---------|----------|-------------|
| **Part 1: Warm-up** | 5-10 min | Conceptual questions; quick code predictions |
| **Part 2: Core Concepts** | 10-15 min | Brief explanations with code examples |
| **Part 3: Guided Exercises** | 25-30 min | Hands-on tasks increasing in difficulty |
| **Part 4: Challenges** | 10 min | Real-world cybersecurity problems |

### Exercise Breakdown

**Warm-up (3 questions)**
- Mutable vs Immutable classification
- Reference behavior prediction
- Dictionary key type testing

**Guided Exercises (6 tasks)**
1. Log Analysis with Slicing
2. Network Connection Parsing with Unpacking
3. Login Attempt Tracker with Dictionary Methods
4. Security Group Analysis with Sets
5. Port Anomaly Detection with Set Comparisons
6. Dictionary Comprehensions for Log Parsing

**Challenges (2 problems)**
1. IP Reputation System (multi-system threat detection)
2. Password Policy Analyzer (character class checking)

---

## 🚀 How to Run the Notebook

### Option 1: Local Jupyter Installation

```bash
# Navigate to lab directory
cd path/to/lab/folder

# Start Jupyter Notebook
jupyter notebook IST1012_Lab3.ipynb
```

### Option 2: JupyterHub (if provided by institution)

1. Log in to your institution's JupyterHub
2. Upload the `.ipynb` file
3. Open and begin working

### Option 3: Google Colab

1. Go to [colab.research.google.com](https://colab.research.google.com)
2. File → Upload notebook
3. Select the `.ipynb` file
4. Begin working (ensure Python 3 runtime)

### Running Cells

- **Run a cell:** `Shift + Enter`
- **Run all cells:** Kernel → Restart & Run All
- **Clear outputs:** Kernel → Restart & Clear Output

---

## 📤 Submission Guidelines

### What to Submit

1. **Completed Jupyter Notebook** (`.ipynb` file)
   - All code cells executed
   - All exercises attempted
   - Comments explaining your approach

### How to Submit

1. Save your notebook (`Ctrl+S` or `Cmd+S`)
2. Download as `.ipynb` if using Colab
3. Correctly place it into your github repository.


---


## ⏱️ Estimated Time Breakdown

| Activity | Time |
|----------|------|
| Reading instructions & warm-up | 5-10 min |
| Studying core concepts | 10-15 min |
| Exercises 3.1 - 3.3 | 12-15 min |
| Exercises 3.4 - 3.6 | 12-15 min |
| Challenge problems | 10 min |
| Review & cleanup | 5 min |
| **Total** | **~60 min** |

---

## 💡 Tips for Students

### General Tips

1. **Read the cell before coding.** Understand what's being asked before typing.

2. **Run code frequently.** Test small changes rather than writing everything at once.

3. **Use `print()` for debugging.** Insert print statements to see intermediate values.

4. **Don't skip warm-up.** These predictions reveal important Python behaviors.

5. **Try before looking for hints.** Struggle a bit—it helps learning stick.

### Data Structure Tips

| Concept | Pro Tip |
|---------|---------|
| **Slicing** | Remember: `[::-1]` reverses any sequence |
| **Unpacking** | Use `_` for values you don't need: `first, _, last = tuple` |
| **Dict access** | Always use `.get(key, default)` to avoid KeyError |
| **Sets** | Convert lists to sets when you need unique values or comparisons |
| **Mutability** | When in doubt, create a copy: `new_list = old_list[:]` |

### Common Mistakes to Avoid

- ❌ Using `=` to copy a list (creates reference, not copy)
- ❌ Using a list as a dictionary key (lists are mutable, not hashable)
- ❌ Using mutable default arguments in functions
- ❌ Forgetting that `set()` removes duplicates

### If You Get Stuck

1. Re-read the concept explanation in Part 2
2. Check the example code provided
3. Search the Python documentation
4. Ask a classmate (collaboration on learning, not copying)
5. Attend office hours

---

## 🔗 Additional Resources

- [Python Official Documentation - Data Structures](https://docs.python.org/3/tutorial/datastructures.html)
- [Real Python - Lists and Tuples](https://realpython.com/python-lists-tuples/)
- [Real Python - Dictionaries](https://realpython.com/python-dicts/)
- [Real Python - Sets](https://realpython.com/python-sets/)

---

## 📝 Academic Integrity

- You may discuss concepts with classmates
- You must write your own code
- Copying code from classmates or the internet is a violation
- Cite any external resources used
- When in doubt, ask the instructor

---

## 🆘 Getting Help

- **Office Hours:** [Check syllabus]

---

*Last Updated: March 2026*  
*Course: IST1012 - Computer Programming II*
*Lab Instructor: Ismail Taha Samed ÖZKAN*  

