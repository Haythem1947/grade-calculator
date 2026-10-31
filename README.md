@'
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
from calculator import calculate_average, get_grade_category, is_passing

average = calculate_average([10, 12, 14])
print(average, is_passing(average), get_grade_category(average))
```
'@ | Set-Content README.md -Encoding ascii
