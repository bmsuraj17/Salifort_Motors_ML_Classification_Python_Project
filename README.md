# Salifort Motors Classification Project: Predicting Employee Turnover
## Overview
This project aims to analyze employee data collected by the HR department at Salifort Motors and build a model that predicts whether an employee is likely to leave the company. The goal is to provide data-driven suggestions to improve employee satisfaction levels and reduce turnover rates.

## Business Problem
The HR department at Salifort Motors is concerned about high employee turnover and wants to take proactive measures to retain valuable employees. By identifying factors that contribute to employees leaving the company, Salifort Motors can implement strategies to increase retention and improve overall employee satisfaction.

## Dataset
The dataset contains 14,999 rows and 10 columns, including variables such as satisfaction level, last evaluation score, number of projects, average monthly hours, tenure, work accidents, promotions in the last 5 years, department, and salary.

## Methodology
We used logistic regression and tree-based machine learning models (decision tree and random forest) to predict employee turnover. The models were evaluated based on precision, recall, f1-score, and accuracy.

## Results
### Logistic Regression:

Precision: 80%
Recall: 83%
F1-score: 80%
Accuracy: 83%

### Tree-based Machine Learning (Random Forest):

AUC: 93.8%
Precision: 87.0%
Recall: 90.4%
F1-score: 88.7%
Accuracy: 96.2%

## Recommendations
Based on the model results and feature importances, we recommend the following strategies to improve employee satisfaction and reduce turnover:

Cap the number of projects employees can work on.
Consider promoting employees who have been with the company for at least four years.
Reward employees for working longer hours or provide clearer expectations around workload and time off.
Hold discussions to understand and address the company's work culture.

## Next Steps
Further analysis could include exploring additional features or conducting surveys to gather more insights from employees. Continuous monitoring of employee satisfaction and turnover rates will also be important to assess the effectiveness of implemented strategies.
