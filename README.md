# Project: Predicting employees leaving
This project is a capstone project for Google Advanced Data Analytics Certificate on Coursera. In this project, I will apply data analytics skills and knowledge which I have learned from this course to solve a business problem.

**Overview**  
The goal of this project was to create a logistic regression model to predict employees likely to quit.

**Data Understanding**  
This project uses a dataset called HR_capstone_dataset.csv came from [Kaggle](https://www.kaggle.com/datasets/mfaisalqureshi/hr-analytics-and-job-prediction?select=HR_comma_sep.csv). It represents 10 columns of self-reported information from employees of a fictitious multinational vehicle manufacturing corporation. The dataset contains:  
  14,999 rows – each row is a different employee’s self-reported information.  
  10 columns  
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
After cleaning and analyzing data, there are some findings as followed:
- Employees at the company are overworked.
- The longer employees stay at a company, the less likely they are to leave.
- The low level of satisfaction and no chance of promotion are the main reasons why employees left.
