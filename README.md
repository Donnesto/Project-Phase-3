# Project-Phase-3
# Overview
This project aims to develop a machine learning model to predict customer churn for a telecom company. Churn prediction is crucial for businesses to identify customers who are likely to cancel their subscriptions, allowing the company to take proactive measures to retain them.

# Data Understanding
The dataset has the following columns:

State, account length,area code,phone number,international plan,voice mail plan, number vmail messages,total day minutes,total day calls,total day charge, total eve minutes, total eve calls,total eve charge, total night minutes,total night calls,total night charge,total intl minutes,total intl calls,total intl charge,customer service calls,churn.
The dataset used for this analysis contains information about syria tel customers, including features such as customer demographics, usage patterns, and customer service interactions. The target variable is binary, indicating whether a customer churned or not.

# Analysis
# Exploratory Data Analysis (EDA)
Explored the dataset to understand the distribution of features and the target variable.
Analyzed correlations between features and identified potentially important predictors.
Baseline Model: Logistic Regression
Trained a logistic regression model as the baseline.
Evaluated the model's performance using accuracy and recall metrics.
Identified features with high importance using feature importance analysis.
Advanced Models
Explored more complex models including Random Forest and Gradient Boosting Classifier.
Tuned hyperparameters using grid search and randomized search to improve model performance.
Evaluated each model's performance and compared results with the baseline.
# Model Evaluation
Evaluated models based on various metrics including accuracy, recall, precision, and F1-score.
Visualized performance metrics using classification reports, confusion matrices, ROC AUC curves, and feature importance plots.
Results
## Logistic Regression:
Achieved an accuracy of 85.76% and recall of 19% for predicting churn.
Identified top features contributing to churn prediction.
## Random Forest Classifier:
Improved accuracy to 94.15% and recall to 64% compared to logistic regression.
Identified key features influencing churn prediction.
## Gradient Boosting Classifier:
Achieved an accuracy of 95.20% and recall of 73%.
Tuned hyperparameters to optimize model performance.
# Conclusion
Gradient Boosting Classifier yielded the highest performance with an accuracy of 95.20% and recall of 73%.
Identified features such as customer service calls, total day minutes, and international plan as significant predictors of churn.
Further improvements could be explored by conducting more exhaustive hyperparameter tuning or experimenting with ensemble methods like XGBoost.
# Next Steps
Deploy the trained model into production for real-time churn prediction.
Monitor model performance and retrain periodically to adapt to changing patterns.
Explore additional data sources or features to enhance model predictive power.
