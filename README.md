# Machine-Learning-Algorithms-to-predict-the-attrition-of-Bank-Customers

## Introduction
The banking industry all over the world is characterized by fierce competition among players and the survival of any bank depends largely on its ability to retain customers who are the major reason why the bank is in business. Hence, most product and marketing activities of banks are focused on minimizing customer churn to maximize profits.

In this work, I explored two different supervised machine learning algorithms, K-Nearest Neighbor and Random Forest, to predict customer churn in ABC Multistate bank. The primary objective is to identify the most effective predictive model for customer attrition, which would enable the bank to implement strategies aimed at improving customer retention.

## Dataset
The dataset used for this work is a publicly available dataset from Kaggle (https://www.kaggle.com/datasets/gauravtopre/bank-customer-churn-dataset/data), and contains information about 10,000 customers of ABC Multistate Bank. The dataset is used for the purpose of determining customer churn, indicating whether a customer has left (1) or remained(0) with the bank.

## Results and Discussion
The analysis revealed that Random Forest classifier achieved a higher accuracy score of 84%, indicating that it has good overall performance in predicting customer churns. While KNN had a relatively low precision score of 40% for churn, Random Forest had a precision score of 60%.

Based on the comparison of the two classifiers, Random Forest outperformed KNN on all metrics. It achieves a better balance between precision and recall for both churn and non-churn classes, making it a more effective algorithm for predicting customer churn based on the data.
