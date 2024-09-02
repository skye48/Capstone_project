# Project: Predicting employees leaving
_Capstone project for Google Advanced Data Analytics Certificate on Coursera

**Overview**  
This project is part of the Google Advanced Data Analytics Certificate program on Coursera. It focuses on applying data analytics skills and knowledge to solve a business problem related to employee retention. The goal was to build a logistic regression model to predict which employees are most likely to leave the company.

**Data Understanding**  
The dataset used in this project, HR_capstone_dataset.csv, was sourced from [Kaggle](https://www.kaggle.com/datasets/mfaisalqureshi/hr-analytics-and-job-prediction?select=HR_comma_sep.csv). It consists of self-reported information from employees of a fictitious multinational vehicle manufacturing corporation. The dataset contains:
  - 14,999 rows: Each row represents an individual employee's self-reported information.
  - 10 columns: Various features related to employee demographics, job satisfaction, and workplace conditions.

| Column name | Type | Description |
|-------------|------|-------------|
| satisfaction_level |int64 | The employee’s self-reported satisfaction level [0-1] |
| last_evaluation | int64 | Score of employee's last performance review [0–1] |
| number_project | int64 | Number of projects employee contributes to |
| average_monthly_hours | int64 | Average number of hours employee worked per month |
| time_spend_company | int64 | How long the employee has been with the company (years) |
| work_accident | int64 | Whether or not the employee experienced an accident while at work |
| left | int64 | Whether or not the employee left the company |
| promotion_last_5years | int64 | Whether or not the employee was promoted in the last 5 years |
| department | str | The employee's department |
| salary | str | The employee's salary (low, medium, or high) |  

**Findings**  
After cleaning and analyzing the data, several key insights were identified:
  - Overwork: Employees at the company are generally overworked.
  - Tenure and Retention: The longer employees stay at the company, the less likely they are to leave.
  - Main Reasons for Leaving: Low job satisfaction and a lack of promotion opportunities are the primary factors contributing to employee turnover.
