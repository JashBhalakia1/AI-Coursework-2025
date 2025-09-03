# BBT 3201 [Aug–Dec 2025] — Practical Exercise 1

This repository contains my solutions for **Practical Exercise 1**.  
Each question is solved in a separate cell in the Jupyter Notebook (`Practical_Exercise1.ipynb`), with explanatory comments.  

---

## 📘 Tasks Overview

### Q1. Seconds in Given Number of Days
- Prompt the user for a number of days.  
- Compute and display the equivalent number of seconds (`days × 24 × 60 × 60`).  

### Q2. Volume of a Sphere
- Prompt the user for a radius.  
- Compute the volume of a sphere using the formula:  
  \[(4/3) × π × r³\]  
- Used Python’s exponent operator `**` and `math.pi`.  

### Q3. Area & Perimeter of a Square (Using Functions)
- Functions defined:  
  - `square_area(side)`  
  - `square_perimeter(side)`  
- Prompt the user for side length, compute area and perimeter, and display results.  

### Q4. Uppercase or Lowercase Character (Using Functions)
- Function `check_character(ch)` checks whether input is:  
  - Uppercase  
  - Lowercase  
  - Not a letter  
- Validates input to ensure only **one character** is provided.  

### Q5. Pseudocode Translation
- Translated the given pseudocode into Python.  
- Implemented using a `while` loop:  
  - Start with `x = 0`, `y = 20`.  
  - Subtract 4 from `y`, add `2/y` to `x`.  
  - Repeat until `y < 6`.  
- Final value of `x` is displayed.  

### Q6. Input Values into an Array and Compute Average
- Use a loop to collect **5 numeric values** from the user.  
- Store them in a list.  
- Compute the average using `sum(values) / len(values)`.  
- Display both the list and the average.  

---

## 📘 Codility Challenge — AbsDistinct
- The **AbsDistinct challenge** (counting the number of distinct absolute values in a sorted array) is solved separately.  
- This solution is attached in a separate file as required.  
- Implemented in **Java** (Codility format) and also provided in **Python** for practice.  

---

## 📂 Files in this Repository
- `Practical_Exercise1.ipynb` — Jupyter Notebook with solutions for Q1–Q6.  
- `AbsDistinct_Solution.java` — Java solution for Codility AbsDistinct task.  
- *(Optional)* `AbsDistinct_Solution.py` — Python equivalent of the Codility task.  

---

## ✅ Notes
- Each task is solved in **its own cell**, with appropriate comments.  
- The Codility solution is **kept separate** as per instructions.  
- Code is written in Python (Q1–Q6) and Java (Codility challenge).  
