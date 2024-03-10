# SYRIA-TEL CUSTOMER CHURN PREDICTION

![image](https://github.com/Donnesto/Project-Phase-3/assets/151524351/1642d379-d12d-468b-8ff5-d69848941e0e)

# Overview
Customer churn, or the termination of a customer's service, is a major problem for SyriaTel, a well-known telecommunications provider. This can result in lost revenue and decreased market competitiveness. This project intends to reveal predictive patterns and create workable strategies to keep customers and reduce revenue loss by utilizing data analysis and machine learning.

# Business Understanding:
Problem Statement:
Customer churn poses a significant challenge for SyriaTel, resulting in revenue loss and decreased business stability. The primary issue revolves around predicting customer departure and understanding the underlying reasons. SyriaTel aims to mitigate customer churn and uphold satisfaction to ensure long-term business sustainability.

# Data Understanding
The data used in this project is from SyriaTel telecommunications company: [here](https://www.kaggle.com/datasets/becksddf/churn-in-telecoms-dataset)

It contains information about syria tel customers, including features such as customer demographics, usage patterns, and customer service interactions. The target variable is binary, indicating whether a customer churned or not.

# Objective
This project aims to develop a classifier to identify customers likely to churn, enabling SyriaTel to implement effective churn prevention strategies and enhance overall business performance. Key objectives include developing precise machine learning models using historical data, analyzing consumer behavior patterns, utilizing feature engineering techniques, evaluating model performance, providing actionable insights for retention strategies, enhancing understanding of customer behaviors, and assessing the financial impact of reducing churn for SyriaTel.

# Exploratory Data Analysis (EDA)
Descriptive statistics were computed for numerical features, revealing insights into the distribution and variability of data.
The distribution of churn status showed that approximately 14.5% of customers had churned.
Analysis of account length and service-related features highlighted patterns and trends in customer behavior.
Churn distributions by international plan, voice mail plan, and customer service calls provided insights into factors influencing churn.

## Baseline Model: Logistic Regression

Accuracy: Achieved an accuracy of 85.76%.
Recall: Recall for class 0 (non-churn) was high at 98%, but for class 1 (churn), it was low at 19%.
Precision: Achieved a precision of 87% for class 0 and 59% for class 1.
Feature Importance: Identified key features driving churn prediction, such as customer service calls and usage patterns.

## Random Forest Classifier (A more complex model)
Accuracy: Achieved an accuracy of 94.15%.
Recall: Significantly improved recall for class 1 (churn) to 64% compared to logistic regression.
Precision: High precision for both classes, indicating accurate positive predictions.
Feature Importance: Identified features such as total day minutes and customer service calls as crucial for predicting churn.


## Gradient Boosting Classifier:
Accuracy: Achieved an accuracy of 95.65%.
Recall: Improved recall for class 1 (churn) to 78% compared to logistic regression and random forest.
Precision: High precision for both classes, indicating accurate positive predictions.

# Conclusion
In conclusion, this  project has provided valuable insights into the dynamics of customer churn within SyriaTel. Through advanced data analysis and machine learning techniques, this analysis has developed predictive models capable of identifying customers at risk of churning with a high degree of accuracy. By leveraging these insights and adopting proactive retention strategies, SyriaTel can effectively mitigate churn, foster long-term customer loyalty, and drive sustainable business growth in the highly competitive telecom industry.

# Next Steps
Targeted Marketing Campaigns: Design campaigns based on predictive insights to retain at-risk customers.
Customer Engagement Strategies: Improve satisfaction and loyalty through personalized support and communication.
Subscription Plan Optimization: Tailor plans to meet individual needs and preferences.
Proactive Customer Retention: Implement proactive measures to retain high-value customers.
Continuous Model Monitoring: Regularly monitor and update models to ensure accuracy and relevance over time.


The presentation can be viewed [here](https://www.canva.com/design/DAF_AtiWMgc/4i0quEGanAQwMRy05UK5xQ/edit?utm_content=DAF_AtiWMgc&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton) 
