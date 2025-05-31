# Customer_Churn_Prediction

Customer churn—the loss of customers—is a critical problem for many businesses. This project leverages machine learning to predict which customers are at risk of leaving, enabling targeted retention strategies.

#### Project Overview
This project builds a predictive model using Logistic Regression to identify customers likely to churn based on their historical data, usage patterns, and demographics. Early identification of at-risk customers helps businesses take proactive measures to improve retention.


####  Dataset
Source: Kaggle Customer Churn Datase
Features: Customer demographics, account information, service usage, and churn status.
Target: Churn (Yes/No)


####  Modeling Approach
Exploratory Data Analysis (EDA): Understand feature distributions, handle missing values, and visualize churn patterns.
Model Selection: Tested Logistic Regression algorithms
Evaluation Metrics: Accuracy, precision, recall, F1-score, ROC-AUC. Compared performance to baseline models (e.g., always predicting the majority class)

####  Deployment
The model is deployed as a web app using [Streamlit/Flask]. Users can input customer data and receive churn predictions in real time
