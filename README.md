# Turnover-detection-suggestions
Predicting employee turnover using machine learning — a capstone project for the Google Advanced Data Analytics Specialization.

The task was to build a machine learning model to predict employee turnover at Salifort Motors and identify the key factors contributing to employee attrition. The project involved data cleaning, exploratory analysis, model training and evaluation, and generating actionable business insights based on model outcomes.

The Random Forest model significantly outperformed logistic regression, achieving 92.2 % recall on the test set, accurately identifying 9 out of 10 employees who left; all other metrics (accuracy, precision, F1) exceeded 98 %.

Key predictors included satisfaction level, projects per year, tenure, last evaluation, and working hours. Overworked employees with low satisfaction were more likely to leave.

Recommendations to reduce turnover:
Trigger alerts when satisfaction drops below 0.5; reduce working hours for those exceeding 200/month.
Base promotions on tenure and project relevance, especially near the 4-year mark, not just workload.
Rebalance workloads—employees with only 1 project showed higher attrition than those with 2–4.
