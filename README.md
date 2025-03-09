# SyriaTel Customer Churn Prediction


## Business Understanding

This project aims to help SyriaTel identify customers at risk of leaving so the company can take proactive steps to retain them. By accurately predicting customer churn, SyriaTel can take proactive measures to retain these customers, thereby reducing revenue loss and increasing customer lifetime value.The management and marketing teams can implement targeted strategies like personalized offers and improved service, reducing customer loss and boosting profitability.

## Problem Statement

SyriaTel has been experiencing a high churn rate leading to losses for the company.This project aims to create a predictive model that accurately identifies customers at risk of churning for SyriaTel, a telecommunications company.

By proactively identifying customers who may discontinue their services, the objective is to decrease customer attrition and retain a higher number of customers. Ultimately, the project seeks to support SyriaTel in reducing financial losses caused by customer churn, improving overall customer retention rates, and optimizing business strategies to enhance profitability.

## Objectives

The primary business objectives of this project for SyriaTel are to reduce customer churn, improve customer retention rates, and enhance overall customer satisfaction.

We will focus on the following questions to achieve our objectives;

Identify Key Predictors of Customer Churn: Determine which features most significantly influence customer churn at SyriaTel.

Provide Actionable Insights for Customer Retention by translating the findings from the predictive models into actionable recommendations for the management and marketing teams at SyriaTel.

Build and compare different machine learning models that is, logistic regression and decision trees to predict customer churn with high accuracy.

## Dataset Overview

The dataset contains information on 3,333 customers, with 21 features covering demographic data, service usage, and customer interaction metrics. The target variable is churn, indicating whether a customer has left the company.

# Exploratory Data Analysis (EDA)

## Churn Distribution
We observed a class imbalance in the churn data, with significantly more customers not churning compared to those who did.


![image](https://github.com/user-attachments/assets/355bb6bf-fa78-475a-b37d-b26b3d554df6)

# Multivariate Analysis
## Correlation Heatmap
A heatmap was used to visualize the correlation between numerical features. Several features exhibited perfect multicollinearity, leading to the removal of redundant features to improve model performance.
![image](https://github.com/user-attachments/assets/fc60d410-8377-4ab1-bd50-1cd84c091090)

# Feature Engineering
Feature engineering involved creating combined features, ratios, and flags to enhance the predictive power of the model. Redundant features were dropped to simplify the model.

## Model Development
Logistic Regression, Decision Trees, and Random Forests
Three models were developed: Logistic Regression, Decision Trees, and Random Forests. Each model was evaluated using metrics such as precision, recall, accuracy, and F1-score.

## Model Evaluation
Confusion Matrix: Visualized the performance of each model by showing the distribution of true positives, true negatives, false positives, and false negatives.
ROC Curve and AUC: The ROC curve and AUC score provided insight into the models' ability to distinguish between churned and non-churned customers.

![image](https://github.com/user-attachments/assets/39af86e4-c23f-4708-b3f1-e070add57c66)

# Model Tuning
Hyperparameter tuning was applied to each model to improve performance. The Decision Tree model showed the best generalization, with a good balance between precision, recall, accuracy, and F1-score.

## Feature Importance
The Decision Tree model identified the most important features influencing churn, including:

Total Combined Charge
International Plan (No)
High Customer Service Calls
Total Combined Usage

 ![image](https://github.com/user-attachments/assets/010239b0-8642-4f27-a6dd-dde4c7eef8ee)

# Conclusion

Cost-Related Factors: The biggest drivers of churn are cost-related, especially total charges. This highlights the importance of pricing and perceived value in SyriaTel’s customer retention efforts.

Service Dissatisfaction: Frequent customer service interactions, particularly high call volumes, suggest that unresolved issues or poor service experiences increase churn risk. Improving customer support could help retain more customers.

Plan Offerings: The availability of specific plans, such as international plans, significantly impacts churn. This suggests a need to reassess how these plans are marketed and whether they provide sufficient value to customers.

# Recommendation
Focus retention efforts on customers with high total charges, as they are at the greatest risk of churn. Consider offering discounts, personalized plans, or loyalty rewards to increase perceived value.

Improve Customer Service: Reduce churn by improving the customer service experience, ensuring that issues are resolved efficiently and that customers feel their concerns are being addressed.

Given the importance of the international plan features, SyriaTel should consider re-evaluating these offerings to ensure they meet customer needs and are priced competitively.

