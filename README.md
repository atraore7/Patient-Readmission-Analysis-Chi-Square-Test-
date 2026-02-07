# Patient Readmission Analysis (Chi‑Square Test)

## Overview
This project explores whether the type of hospital service a patient receives is associated with their likelihood of being readmitted. Using exploratory data analysis and a Chi‑Square test, the project evaluates categorical relationships to support data‑driven decision‑making in healthcare operations.

## Business Question
Is there a statistically significant difference between the service a patient receives and their readmission status?

## Dataset
- Medical records containing demographic, clinical, and service‑related variables

Key variables:
- Services (primary service received during hospital stay)
- ReAdmis (0 = not readmitted, 1 = readmitted)

Cleaned data and analysis scripts are stored in the data/ and notebooks/ folders.

## Data Preparation
- Imported and inspected the medical dataset
- Removed duplicates and checked for missing values
- Identified categorical and continuous variables
- Created crosstab tables for categorical comparisons
- Prepared data for Chi‑Square testing

## Modeling Approach
- Analysis technique: Chi‑Square Test of Independence
- Used to determine whether two categorical variables (Services and ReAdmis) are statistically related

## Results
- p‑value: 0.03
- Chi‑Square statistic: 8.89
- Degrees of freedom: 3
- Critical value: 7.81

Because the p‑value is below 0.05 and the Chi‑Square statistic exceeds the critical value, there is a statistically significant relationship between the service a patient receives and their readmission status.

## Insights
- Readmission likelihood varies significantly across different service types
- Certain services may require additional staff training or improved processes
- Identifying high‑readmission service areas can help hospitals allocate resources more effectively
- Results support operational decisions related to staffing, workflow improvements, and patient care strategies

## Conclusion
The Chi‑Square test indicates a meaningful association between hospital service type and patient readmission. These findings can guide healthcare organizations in evaluating service performance, improving patient outcomes, and reducing avoidable readmissions.
