# Student Grade Calculator

A simple Python application that calculates the average grade of a student
and determines whether the student passes.

## Installation

```bash
pip install -r requirements.txt
```

## Run Tests

```bash
pytest -v
```

## Run Linting

```bash
flake8 .
```

## Usage

```python
from calculator import calculate_average, is_passing, get_grade_category

average = calculate_average([12, 15, 9])  # 12.0
is_passing(average)                       # True  (passing grade is 10)
get_grade_category(average)               # "Good"
```
