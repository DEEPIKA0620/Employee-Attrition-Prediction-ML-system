# Employee Attrition Prediction

## Project Overview

Employee attrition can significantly impact organizational productivity and increase recruitment costs. This project uses Machine Learning algorithms to predict employee attrition and identify factors that influence employee turnover.

## Problem Statement

Organizations need effective methods to identify employees who are at risk of leaving. The objective of this project is to build a machine learning model that predicts employee attrition using HR-related employee data.

## Dataset

* Dataset: IBM HR Analytics Employee Attrition Dataset
* Total Records: 1470
* Features: Employee demographics, job information, compensation, satisfaction metrics, and work-related factors.
* Target Variable: Attrition (Yes/No)

## Tools and Technologies

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## Project Workflow

1. Data Understanding
2. Data Cleaning
3. Exploratory Data Analysis (EDA)
4. Feature Engineering
5. Data Encoding
6. Model Training
7. Model Evaluation
8. Attrition Analysis

## Machine Learning Models Used

* Logistic Regression
* Decision Tree Classifier
* Random Forest Classifier

## Model Performance

| Model               | Accuracy | Precision | Recall | F1 Score |
| ------------------- | -------- | --------- | ------ | -------- |
| Logistic Regression | 88.78%   | 71.43%    | 25.64% | 37.74%   |
| Decision Tree       | 79.93%   | 23.68%    | 23.08% | 23.38%   |
| Random Forest       | 88.10%   | 83.33%    | 12.82% | 22.22%   |

## Key Insights

* Employees with fewer years at the company are more likely to leave.
* Overtime may contribute to attrition but is not the sole factor.
* Job role and monthly income influence employee retention.
* Multiple workplace factors collectively affect attrition.

## Conclusion

Logistic Regression provided the best balance between precision, recall, and F1 score. The developed model can support HR departments in identifying employees at risk of leaving and assist in retention planning.

