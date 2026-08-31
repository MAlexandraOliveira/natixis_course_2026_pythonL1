# 🐍 Natixis Python Level 1

## 📚 Course Overview

This introductory course is designed for students with no previous programming experience. Students will learn to read and write Python from the very beginning, work with Python's core data structures, and carry out a first real data analysis with Pandas. Every class is taught from a Google Colab notebook, so there is nothing to install.

> 📅 **Materials are published as the course progresses.** Each class appears here on the day it is taught, and its solutions afterwards.

# 📋 Course Structure (Introductory Python - Level 1)

## 🚀 Class 1: Python Basics
### 🐍 Getting Started
- Why Python, and where we will write it
- Google Colab: cells, running code, saving your work
- `print()`, comments, and the order a program runs in

### 📦 Variables & Data Types
- Variables and naming rules
- `str`, `int`, `float`, `bool`, `list`
- Checking a type with `type()`
- Casting between types, and reading input with `input()`

### ➗ Operators
- Arithmetic and assignment operators
- Comparison and logical operators
- Membership with `in` and `not in`

### ✨ f-strings
- Putting values inside text
- Formatting numbers, for example `{total:,.2f}`

### 🔀 Control Flow
- Making decisions with `if` / `elif` / `else`
- Indentation and why it matters
- Repeating work with `while` and `for`
- `range()`, and stopping or skipping with `break` and `continue`

### 📝 Exercises
- [Class 1 Exercises](class-1/L1C1%20exercises.ipynb)
- Class 1 Solutions — *published after the class*

---

## 📊 Class 2: Data Structures
### 📋 Lists
- Creating, indexing and slicing
- `.append`, `.remove`, `.pop`, `.insert`, `.sort`
- Changing an item, and checking membership

### 📌 Tuples
- Creating and unpacking
- Why a tuple cannot be changed, and when you want that

### 🎯 Sets
- `.add` and `.discard`
- Fast membership tests, and removing duplicates
- Union, intersection and difference

### 📖 Dictionaries
- Keys and values, and access with `.get`
- Adding, updating and deleting entries
- `.keys`, `.values`, `.items`, and looping over a dictionary
- Nesting one level deep

### 🔧 Built-in Functions
- What "built-in" means, and how it differs from a method
- `enumerate`, `sorted`, `sum`, `min`, `max`
- `sorted()` against `.sort()`, and why one returns `None`

### 🤔 Choosing the Right Structure
- Which container to reach for, and the question that decides it

### 📝 Exercises
- Class 2 Exercises — *published on the day of the class*
- Class 2 Solutions — *published after the class*

---

## 📈 Class 3: Data Analysis with Pandas
### 🐼 DataFrames
- What a DataFrame is, and how it differs from a list
- `import pandas as pd`
- Reading a CSV, and mounting Google Drive

### 🔍 Exploring & Filtering
- `.head()`, `.info()`, `.describe()`, `.shape`, `.columns`
- Selecting one column and several columns
- Filtering rows, and combining conditions with `&` and `|`

### 🧹 Data Quality
- Finding missing values with `.isnull().sum()`
- `.dropna()`, `.fillna()`, `.drop_duplicates()`, `.drop()`
- Tidying messy text with `.str.lower()` and `.replace()`

### ➕ Creating & Changing Columns
- Adding a calculated column
- Building a column from a condition

### 📊 Summarising
- `.sum()`, `.mean()`, `.min()`, `.max()`, `.round()`
- `.unique()`, `.nunique()`, `.value_counts()`
- Grouping with `.groupby()`, and sorting the result
- Exporting with `.to_csv()`

### 📝 Exercises
- Class 3 Exercises — *published on the day of the class*
- Class 3 Solutions — *published after the class*

---

## 🚀 Class 4: Mini-Project
### 💡 Project — Monthly Budget Review
- Read the raw expenses file and clean it
- Work out who is over and under budget, and by how much
- Print a readable report with a status per department
- Export a summary the finance team could open in Excel
- Apply everything from Classes 1 to 3, not only Pandas

---

## 🎯 Learning Objectives

By the end of this course, students will be able to:
- Read and write Python, and understand the order in which a program runs.
- Use variables, the core data types, casting and f-strings to produce readable output.
- Control a program with `if` / `elif` / `else`, `while` and `for` loops.
- Choose between lists, tuples, sets and dictionaries, and explain why.
- Use Python's built-in functions such as `enumerate`, `sorted`, `sum`, `min` and `max`.
- Load a CSV into a Pandas DataFrame and inspect it.
- Clean real data: missing values, duplicates and inconsistent text.
- Filter rows, create calculated columns, and summarise with `groupby`.
- Build a small end-to-end report and export it for someone else to use.

## ✅ Prerequisites

None. This is the entry point of the programme and assumes no previous programming experience.

Students only need:
- A Google account
- A web browser
- No prior Python, and no software installed

Level 1 is a prerequisite for Level 2.

## 📁 Course Materials

### 📚 Class Notebooks
- [Class 1 — Python Basics](class-1/L1C1_python_basics.ipynb)
- Class 2 — Data Structures *(published on the day of the class)*
- Class 3 — Data Analysis with Pandas *(published on the day of the class)*
- Class 4 — Mini-Project *(published on the day of the class)*

### 📝 Exercises & Solutions
- **Class 1**: [Exercises](class-1/L1C1%20exercises.ipynb) | Solutions *(after the class)*
- **Class 2**: *published on the day of the class*
- **Class 3**: *published on the day of the class*
- **Class 4**: *published on the day of the class*

### 📊 Datasets
- [expenses.csv](datasets/expenses.csv) — used from Class 3 onwards

## 🚀 Getting Started

1. **📥 Setup Environment**
   - Sign in to a Google account
   - Open [Google Colab](https://colab.research.google.com) in your browser
   - Nothing to install: Python, Pandas and Matplotlib are already there

2. **📚 Start Learning**
   - Open the [Class 1 notebook](class-1/L1C1_python_basics.ipynb) for the theory, and run every cell yourself
   - Practise with the [Class 1 Exercises](class-1/L1C1%20exercises.ipynb)
   - Check your work against the solutions, shared after the class

3. **🔄 Progress Through Classes**
   - Follow the same pattern for Classes 2-4

4. **💡 Apply Your Skills**
   - The final class of this course is dedicated to a project that applies everything covered throughout this introductory course.

---

## ⚠️ Intellectual Property Notice

**Important**: This course material is the intellectual property of the course instructors and should not be distributed, shared, or reproduced without their explicit written consent. All content, exercises, and materials are protected by copyright and are intended solely for enrolled students of this course.

---

*This course provides a first foundation in Python programming, with a focus on writing readable code and carrying out a practical data analysis from start to finish.*
