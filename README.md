# Task 1: Student Marks Analysis

## What it does
This project analyzes a list of student marks and calculates:
- Total marks
- Average marks
- Highest marks
- Lowest marks

## Tools
- Python
- Jupyter Notebook

## How to run
1. Open `Task1_Student_Marks_Analysis.ipynb` in Jupyter Notebook or VS Code.
2. Click **Run All**.

## Approach
1. The marks are stored in a Python list (manually created sample data).
2. `sum()` calculates the total.
3. The average is the total divided by the number of students, `len(marks)`.
4. `max()` and `min()` find the highest and lowest marks.
5. The results are printed in a simple table.

## Dataset
Manually created student marks, stored in the `marks` list in the notebook.

## Deployment
This project runs as a Jupyter Notebook, with no server to deploy.

1. Install the requirements: `pip install -r requirements.txt`
2. Run Jupyter: `jupyter notebook`
3. Open `Task1_Student_Marks_Analysis.ipynb` and click **Run All**.

## Rollback
Each release is tagged in Git.

- Version 1.0 (`v1.0`): notebook and README only.
- Version 1.1 (`v1.1`): adds `requirements.txt` and the deployment section.

To roll back to version 1.0, run:
```
git checkout v1.0
```
To return to the latest version, run:
```
git checkout main
```
