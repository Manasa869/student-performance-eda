# Student Performance Analysis

## Overview
This project explores student performance using Python and exploratory data analysis (EDA). It examines how study time, past class failures, school, absences, and second-period grades relate to final math grades.

## Dataset
The project uses the UCI Student Performance dataset. The analysis focuses on the math-course data.

## Tools
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Jupyter Notebook

## Key Findings
- Second-period grades (G2) have a strong positive association with final grades (G3).
- Students with more past class failures generally have lower final grades.
- GP students had a slightly higher average final grade than MS students, though the distributions overlap and the groups differ in size.
- Median final grades varied only modestly across study-time categories.

## Limitations
These are observational patterns, not evidence of causation. Some groups are small, and the dataset represents students from only two schools.

## How to Run
1. Clone or download this repository.
2. Create and activate a Python virtual environment.
3. Install the packages listed in `requirements.txt`.
4. Open `notebooks/student_performance_eda.ipynb` in Jupyter or VS Code and run the cells.