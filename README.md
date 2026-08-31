# Natixis Python Level 1 — Course Summary

This introductory Python course assumes no previous programming experience. The curriculum
spans four classes of three hours each, covering the language basics, Python's core data
structures, data analysis with pandas, and a mini-project that puts all three together. Every
class is taught from a Google Colab notebook, so there is nothing to install.

> 📅 **Materials are published as the course progresses.** Each class appears here on the day
> it is taught, and its solutions afterwards. If a folder below is not in the repository yet,
> that class is still to come.

## Key Course Components

**Class 1 — Python Basics** introduces how a program runs and how to write one: `print()` and
comments, variables and the core data types, casting and `input()`, the arithmetic, comparison
and logical operators, and f-strings for putting values inside text. It closes with decisions
(`if` / `elif` / `else`) and repetition (`while`, `for`, `break`, `continue`), pulled together
into a single invoice-review example.

**Class 2 — Data Structures** covers the four containers Python gives you — lists, tuples,
sets and dictionaries — how each is created, changed and searched, and, most importantly, how
to choose between them. It also introduces the built-in helpers used constantly thereafter:
`enumerate`, `sorted`, `sum`, `min` and `max`.

**Class 3 — Data Analysis with pandas** moves from single values to whole tables. It explains
what a DataFrame is, how to load a CSV and take a first look at it, how to select columns and
filter rows, and how to deal with real data quality problems — missing values, duplicates and
inconsistent text. It finishes with creating new columns and summarising with `groupby`.

**Class 4 — Mini-Project** asks students to build a monthly budget review: read the raw
expenses file, clean it, work out who is over and under budget, print a readable report with a
status per department, and export a summary the finance team could open in Excel. It needs
everything from the three classes before it, not just pandas.

## Prerequisites

None. This is the entry point of the three-level programme, and it assumes no previous
programming experience. Level 1 is a prerequisite for Level 2.

## Required Setup

A Google account and a web browser. Classes are taught in **Google Colab**, which runs Python
in the browser with pandas already installed — there is nothing to install and nothing to
configure. Students open a notebook from a link and start typing.

`class-1/vscode_setup.pptx` covers installing Python and VS Code locally, for anyone who wants
to work outside Colab. It is optional and never required by any exercise.

## What is in this repository

```
class-1/   Python basics                    ← available now
class-2/   Data structures
class-3/   Data analysis with pandas
class-4/   Mini-project
datasets/  expenses.csv, used from Class 3 onwards
```

Each of the first three classes has an **exposition** notebook, taught at the front of the
room, and an **exercises** notebook worked through in the second half. A **SOLUTIONS** notebook
is added after the class has run. Class 4 is a project brief, with its solution released
afterwards.

Exercises are graded in four sections, from a warm-up to a challenge, and every one states the
output it expects so students can check themselves as they go. Nothing in an exercise uses a
function or method that has not already been shown in a class.

## How a class runs

Roughly 40 minutes of exposition, a 15-minute break, then 90 minutes of exercises — leaving
time in a three-hour session for questions and for walking the room.
