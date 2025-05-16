# String Matching Project (CS312) - KMP Algorithm

## Overview

This project implements the **Knuth-Morris-Pratt (KMP)** string matching algorithm to find all occurrences of a pattern inside a given text efficiently.

The goal is to detect every starting index in the text where the pattern appears as a substring.

---

## Features

- Finds all matches of a pattern within a text using KMP (linear time complexity).
- User-friendly GUI built with Tkinter to input text and pattern.
- Displays match positions, execution time, and explains time complexity.
- Includes a performance graph showing how the algorithm scales with increasing input size.

---

## Input

- **Text (T)**: a string of length *n*.
- **Pattern (P)**: a string of length *m*.

---

## Time Complexity

- The KMP algorithm runs in **O(n + m)** time.
- Here, **n** is the length of the text, and **m** is the length of the pattern.
- The algorithm preprocesses the pattern to create an LPS (Longest Prefix Suffix) array, then scans the text efficiently to find all matches without redundant comparisons.

---

## How to Run

1. Make sure you have Python 3 installed.  
2. Install dependencies:  
   ```bash
   pip install matplotlib
   python kmp_gui.py
''
   In the GUI:

Paste or type your text into the Text box.

Enter the pattern to search in the Pattern field.

Click Search Pattern to see matches and execution details.

Click Show Performance Graph to view runtime scaling.

----
Author
Omar – Arab Academy for Science, Technology, and Maritime Transport (AAST)

License
This project is provided for academic purposes only.
