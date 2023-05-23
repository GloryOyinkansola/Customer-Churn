## Customer Churn Analysis

### Introduction
#### Problem statement
There has been an increase in the number of customers leaving a Bank. The goal of the Bank is to greatly reduce the rate of churn and retain as many customers as possible. In fact, research has shown that obtaining new customers is five times more expensive than retaining current ones.
This problem would be solved by identifying which group of customers are leaving or likely to leave, why they are leaving, and how to reduce the rate of customer churn. Reducing the rate of churn would increase the worth of the bank.

Churn prediction is the process of identifying which consumers are most likely to stop using a service.
Customer churn is a critical concern for businesses across industries, but it is particularly important in the banking industry. As organizations expand, the loss of existing customers can have a disastrous impact on future performance. Therefore, predicting customer churn is a crucial task for many firms, including banks


### Data Source
The data used in this project was sourced from Kaggle. The dataset includes information on customers' demographics, age, credit score, estimated salary, balance, etc.

### Objectives
The objectives of this project are to:
1. Identify the drivers of customer churn in the banking industry
2. Determine which customers are most at risk of churning
3. Establish thresholds for taking action based on the likelihood of churn
4. Identify which group of customers have the highest churn rate
5. Evaluate six predictive machine learning models and determine which model is best for predicting churn.

### Data Analysis Process
Data cleaning: Outliers were removed, and irrelevant columns were dropped.
Exploratory data analysis: Charts and graphs were used to identify trends and patterns in the data.
Feature engineering: Categorical variables were transformed into numeric using one hot encoder.
Balancing of target variable: The SMOTE technique was used to balance the target variable 'Exited'.
Data scaling: The RobustScaler was used to scale the data.
Model selection: Six predictive machine learning models were evaluated, including Logistic Regression, Support Vector Machine, K-Neighbors Classifier, Decision Tree Classifier, Random Forest Classifier, and Gradient Boosting Classifier.
Model evaluation: The models were evaluated using accuracy, precision, recall, and F1 score metrics. The Random Forest Classifier performed the best.

### Insights
The analysis revealed the following insights:
20.9% of customers churned.
Customers located in Germany have the highest churn rate.
Customers with 3 or 4 products have a higher chance of churning.
Inactive customers have a higher chance of churning.
Older customers (between 40 and 70 years old) have a higher chance of churning.

### Conclusion
The Random Forest Classifier model had the highest accuracy, precision, recall, and F1 score and is therefore the best model to evaluate customer churn.

### Suggestions
1. Recognize and appreciate customers that are still with the bank to encourage them to stay.
2. Create campaigns and special offers for customers in Germany and inactive customers.
3. Improve the overall customer experience to retain more customers.
4. Educate customers on the bank's products and offers.
5. Conduct surveys with customers who have already churned to understand their reasons for leaving and adopt a proactive approach to avoiding future customer churn.
