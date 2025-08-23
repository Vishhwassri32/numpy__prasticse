# NumPy Student Marks Analysis

This project demonstrates how to represent and analyze student marks using **NumPy arrays**.

## 📌 Dataset
We have 5 students and their marks in 3 subjects (Maths, Science, English):

- Students: Aman, Vishwas, Priya, Rohit, Neha
- Marks (2D NumPy array):
  - Row → Student
  - Column → Subject (Maths, Science, English)

```python
import numpy as np

students = np.array(["Aman", "Vishwas", "Priya", "Rohit", "Neha"])

# Marks: [Maths, Science, English]
marks = np.array([
    [78, 85, 90],
    [90, 88, 95],
    [65, 70, 60],
    [82, 79, 85],
    [95, 92, 98]
])
