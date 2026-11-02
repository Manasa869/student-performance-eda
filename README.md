# Student Performance Analysis

## Project Overview
This project explores student performance data using Python and exploratory data analysis (EDA). It investigates how factors such as study time, absences, previous class failures, and school are associated with students’ final grades.

## Dataset
The project uses the UCI Student Performance dataset. The analysis focuses on the Portuguese student dataset (`student-por.csv`).

## Tools
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Jupyter Notebook

## Research Questions
1. How are second-period grades (G2) associated with final grades (G3)?
2. How do study-time categories relate to final grades?
3. How are absences associated with final grades?
4. How do final grades vary by school?
5. How do past class failures relate to final grades?

## Key Findings
- G2 and G3 show a strong positive relationship in the dataset.
- Students with more past class failures generally have lower final grades.
- Final grades vary across study-time categories, but the differences are modest.
- The school groups have similar median final grades in this dataset.
- Absences show a broad spread of final grades, so absences alone do not explain performance.

These are associations in this dataset, not evidence that any factor causes a change in grades.

## Project Structure
- `data/raw/` — original dataset files
- `notebooks/` — EDA notebook
- `images/` — exported charts
- `requirements.txt` — Python dependencies

## How to Run
1. Clone this repository.
2. Create and activate a Python virtual environment.
3. Install dependencies:
   `pip install -r requirements.txt`
4. Open `notebooks/student_performance_eda.ipynb` in Jupyter or VS Code and run the cells.

## Limitations
This analysis is observational and uses data from a specific dataset and school context. Some categories have relatively few students, so group comparisons should be interpreted cautiously.