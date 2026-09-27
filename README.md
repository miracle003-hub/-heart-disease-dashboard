# Heart Disease Analysis Dashboard

A data analysis project exploring survival outcomes in heart failure patients, built end-to-end using SQL Server, Python, Excel, and Power BI.

## Overview

This project analyzes the UCI Heart Failure Clinical Records dataset (299 patients) to understand how age, kidney function (serum creatinine), heart pumping efficiency (ejection fraction), and lifestyle/health factors (smoking, high blood pressure, diabetes, anaemia) relate to survival outcomes.

## Tools Used

- **Python** (pandas) — data cleaning, age-group bucketing
- **SQL Server (SSMS)** — relational storage, SQL views for aggregated reporting
- **Excel** — Power Query connection to SQL Server, PivotTables, dashboard version 1
- **Power BI** — DAX measures, custom visuals, dashboard version 2

## Key Findings

- Overall survival rate: **67.89%**
- Survival rate drops sharply with age: **81.08%** (31-45) → **70.4%** (46-60) → **69.16%** (61-75) → **36.67%** (76+)
- Serum creatinine (a kidney function marker) rises consistently with age, suggesting worsening kidney function contributes to poorer outcomes in older patients
- Male and female survival rates are nearly identical (68.04% vs 67.62%), indicating age is a far stronger predictor than sex in this dataset

## Files in This Repo

- `heart_disease_analysis.ipynb` — Python data cleaning and preparation notebook
- `heart_failure_clinical_records_dataset.csv` — source dataset (UCI Machine Learning Repository)
- `Hospital_heart Disease.pbix` — Power BI dashboard
- Excel dashboard file

## Dataset Source

[UCI Machine Learning Repository — Heart Failure Clinical Records](https://archive.ics.uci.edu/dataset/519/heart+failure+clinical+records)

## Author

Built by Meera as part of a data analysis portfolio project.
