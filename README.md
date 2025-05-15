# HR-Analytics-Job-Prediction

## Project Overview

This project is the capstone for the Google Advanced Data Analytics Professional Certificate. The goal was to build a machine learning model to predict employee attrition for Salifort Motors, a fictional alternative energy vehicle manufacturer. The model enables the company to make informed decisions about employee retention.

## Process Summary

* Explored and cleaned HR data, handling outliers and encoding categorical variables
* Conducted exploratory data analysis to understand attrition patterns
* Engineered features related to satisfaction level, evaluation score, average monthly hours, tenure, promotion history, and more
* Built and evaluated a logistic regression model to predict attrition

## Key Findings

* Employees with low satisfaction and high or moderate evaluation scores were more likely to leave
* High attrition was observed among employees working excessive hours with no recent promotions
* Most employees who left had not received a promotion in the past five years
* Employees with more than six years of tenure generally did not leave

## Model Performance

* Accuracy: 83%
* Precision: 79%
* Recall: 83%
* F1 Score: 80%
* No resampling was needed due to a reasonably balanced dataset

## Business Insights

* Attrition is linked to overwork, low satisfaction, and lack of promotion
* Burnout appears to be a significant factor among employees working long hours with minimal recognition
* Tenure beyond six years is a strong indicator of retention

## Recommendations

* Clarify overtime and workload expectations
* Reevaluate performance evaluation criteria to avoid bias toward overwork
* Implement targeted retention strategies for employees with 3–5 years of tenure
* Recognize and reward contributions fairly across all working hour brackets
* Address team-level culture and work-life balance proactively

## Tools and Technologies

* Python (Pandas, NumPy, Scikit-learn)
* Jupyter Notebook
* Matplotlib, Seaborn
