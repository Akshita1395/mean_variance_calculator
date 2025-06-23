# Mean-Variance-Standard Deviation Calculator

This project is part of the freeCodeCamp Data Analysis with Python certification.

## 📌 Project Description

The goal of this project is to write a Python function that takes a list of 9 numbers and returns a dictionary containing the mean, variance, standard deviation, max, min, and sum along both axes and for the flattened 3x3 matrix.

The calculations are performed using **NumPy**.

## ✅ Function Specification

- **Function name**: `calculate()`
- **Input**: A list of exactly 9 numbers
- **Output**: A dictionary with the following structure:

```python
{
  'mean': [column-wise, row-wise, flattened],
  'variance': [column-wise, row-wise, flattened],
  'standard deviation': [column-wise, row-wise, flattened],
  'max': [column-wise, row-wise, flattened],
  'min': [column-wise, row-wise, flattened],
  'sum': [column-wise, row-wise, flattened]
}
