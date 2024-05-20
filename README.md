# Employee_turnover_analysis
![employee-turnover](https://github.com/Bhagyasri00/Employee_turnover_analysis/assets/142825445/10ebd49d-981d-4565-b194-8992849683f6)

# Project Description

In this project, I conducted an in-depth analysis of employee turnover data to uncover the key drivers behind attrition rates within the company. Our investigation revealed significant disparities across departments, highlighted salary discrepancies, and identified nuanced turnover patterns related to employee tenure. Additionally, we went beyond descriptive analysis by comparing the predictive capabilities of two prominent models, Logistic Regression and Random Forest. This comprehensive approach not only provided valuable insights into the factors influencing turnover but also offered actionable information for strategic decision-making to enhance employee retention and organizational stability.

#Problem Statement

The project's goal is to study why employees leave the company. By looking at data about employees who have left, we want to find out what factors make them decide to go. This will help us figure out how to keep more employees happy and stay with the company

# Libraries Used

Pandas
Maplotlib
Seaborn
Sci-kit Learn

# Insights Found 

**Sales Department Challenges**: Many employees work in Sales, but they leave the company more often than others. This might mean there are problems specific to the Sales Department, like high-pressure targets or job dissatisfaction.

**Safety Concerns**: Workplace incidents lead to many employees leaving, indicating that better safety measures are needed. If employees feel unsafe, they're more likely to look for other jobs.

**Low Salaries**: A lot of employees earn low salaries, which could be why they leave. When people feel they aren't paid enough, they might leave to find better-paying jobs.

**Tenure and Turnover**: Employees often leave after about five years, which could show problems with career growth or feeling burnt out.

**Limited Growth Opportunities**: Few employees have been promoted recently, suggesting there aren't many chances to grow within the company. When employees feel stuck, they might leave to find better opportunities elsewhere.

Here are few Visualisations:
![percentage_of_employees_left_by_years_spent_in_company](https://github.com/Bhagyasri00/Employee_turnover_analysis/assets/142825445/b59473c9-1d44-4e59-9d2d-bd94dea756f4)
![work_related_incidents_contributing_to_turnover](https://github.com/Bhagyasri00/Employee_turnover_analysis/assets/142825445/d89b4592-4876-4dfa-96f7-8ab3210e56c5)
![distribution_of_average_monthly_hours_worked](https://github.com/Bhagyasri00/Employee_turnover_analysis/assets/142825445/83b3f320-5730-4572-a125-a35c80bf4d46)
![count_of_employees_in_each_department](https://github.com/Bhagyasri00/Employee_turnover_analysis/assets/142825445/eeff365b-e9c4-4e88-ad22-1a78f005e585)
![distribution_of_satisfaction_level](https://github.com/Bhagyasri00/Employee_turnover_analysis/assets/142825445/683f4bb3-43cc-4fba-8c83-0cb59b978703)
![number_of_projects_per_employee](https://github.com/Bhagyasri00/Employee_turnover_analysis/assets/142825445/84a219de-cb86-4653-9d23-a44ac364a74f)

# Models Used

For predicting employee turnover, we employed two machine learning models:

1. **Logistic Regression**: A traditional classification algorithm widely used for binary classification tasks. Logistic Regression models the probability of a binary outcome based on one or more predictor variables.

2. **Random Forest**: A powerful ensemble learning method that operates by constructing multiple decision trees during training and outputs the mode of the classes for classification tasks.

These models were trained on our employee turnover dataset to identify patterns and predict potential turnover risks.

## Feature Importance Analysis

The feature importance analysis was performed using the Random Forest model. Random Forest is well-suited for feature importance assessment as it provides a straightforward way to rank the importance of features based on their contribution to the model's predictive performance.

By analyzing feature importance, we gained insights into which factors have the most significant impact on predicting employee turnover. This information is invaluable for understanding the drivers of turnover within the company and informing targeted retention strategies.
![feature_importance](https://github.com/Bhagyasri00/Employee_turnover_analysis/assets/142825445/68f27af4-08eb-4989-8af0-846126cae4bf)


# Model Performance

The Random Forest model exhibited high accuracy, achieving a score of 98% during testing. This demonstrates the effectiveness of the model in accurately predicting employee turnover and provides valuable insights for retention strategies within the company.
![Screenshot 2024-05-20 102726](https://github.com/Bhagyasri00/Employee_turnover_analysis/assets/142825445/2eba522d-97dc-4989-acd0-ff9d26aa828d)




















