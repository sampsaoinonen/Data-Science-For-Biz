# Predicting Monthly Salaries in the Finnish Tech Sector

Course project for Data Science for Business I at Aalto University.

The project examines how accurately reported gross monthly salaries can be predicted using industry experience, professional role, seniority, location, company size, and working time.

## Files

- `Salary_prediction.ipynb`: analysis notebook, including data preparation, descriptive analysis, model comparison, evaluation, and sensitivity analyses.

## Data

The analysis uses the processed Koodiklinikka 2025 salary survey:

https://koodiklinikka.github.io/palkkakysely/2025/

The dataset is published by Koodiklinikka under the Creative Commons Attribution 4.0 International license.

## Running the analysis

1. Download the notebook.
2. Download the processed CSV dataset from the survey website.
3. Place the CSV in the location specified in the notebook's data-loading cell, or update that cell to match your local file location.
4. Install the dependencies listed in `requirements.txt`.
5. Open the notebook in JupyterLab and run all cells in order.

## Scope

The analysis predicts reported salary levels within the survey sample. It does not predict future salary development or establish causal relationships.
