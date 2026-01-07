# Heart Failure Prediction - Machine Learning

This is a project for the Course of Machine Learning Algorithms, year 2022.

## Overview

This project compares three approaches to predicting death in heart failure patients:

1. **Full Model** - Logistic regression with all 10 predictors
2. **Reduced Model** - Backward stepwise selection to find significant predictors
3. **PC Model** - Factor Analysis of Mixed Data (FAMD) + logistic regression on PC scores

## Data

299 patients. 96 patients (32%) died during the study.

**Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/519/heart+failure+clinical+records)

| Variable | Type | Description |
|----------|------|-------------|
| age | Continuous | Age in years |
| anaemia | Binary | Decrease in red blood cells |
| diabetes | Binary | Has diabetes |
| high_blood_pressure | Binary | Has hypertension |
| sex | Binary | Gender (0=female, 1=male) |
| smoking | Binary | Smoker |
| creatinine_phosphokinase | Continuous | CPK enzyme level (mcg/L) |
| ejection_fraction | Continuous | % blood pumped per heartbeat |
| platelets | Continuous | Platelet count |
| serum_creatinine | Continuous | Creatinine level (mg/dL) |
| serum_sodium | Continuous | Sodium level (mEq/L) |

