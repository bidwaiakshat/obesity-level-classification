# Obesity Level Classification Using XGBoost

## Overview
A multiclass machine learning project that predicts
obesity levels from demographic, eating-habit, and
physical-condition features.

## Dataset
[Obesity Levels Dataset on Kaggle](https://www.kaggle.com/datasets/fatemehmehrparvar/obesity-levels)

Target variable: `NObeyesdad`

## Workflow
- Exploratory data analysis and visualizations
- Data cleaning and duplicate handling
- Feature encoding and train-test split
- SMOTE applied to training data
- XGBoost hyperparameter tuning using cross-validation
- Evaluation with classification metrics and a confusion matrix

## Results
- Test accuracy: 95.45%
- Macro precision: 95.28%
- Macro recall: 95.36%
- Macro F1-score: 95.31%
- Weighted F1-score: 95.45%
- Weighted one-vs-rest ROC-AUC: 0.9984
- Best cross-validation macro F1-score: 0.9446

## Files
- `Minor_Project_Documented.ipynb`: Main notebook
- `Obesity_Level_Classification_Project_Report.pdf`: One-page report

## Limitations
Results depend on the selected dataset and evaluation split.
They do not establish clinical validity or guarantee
performance on real-world populations.

## Disclaimer
This is an educational ML project, not a medical diagnostic tool.
