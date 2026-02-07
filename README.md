# Customer Churn Prediction – Indian Telecom Sector
##  Project Overview
This project focuses on predicting customer churn in the Indian telecom sector using demographic and usage data. The goal is to build predictive models to identify customers who are likely to stop using a telecom service and to determine the factors that most influence churn. 

Additionally, the project compares the performance of two categorical encoding methods – **Ordinal Encoding** and **One-Hot Encoding** – and evaluates their impact on model performance.

## Scenario
The telecommunications sector in India is highly competitive, with customers frequently switching between providers. Churn, defined as the process where customers discontinue the use of a company's services, is a major challenge for telecom companies. Predicting churn accurately enables companies to take proactive measures to retain customers, which is essential for business growth.

This project uses data from four major Indian telecom operators: Airtel, Reliance Jio, Vodafone, and BSNL. The dataset contains both demographic information and usage patterns. 

## Objectives

- Predict whether a customer will churn using demographic and usage features.  
- Identify key factors that contribute most to customer churn.  
- Compare the performance of **Ordinal Encoding** vs **One-Hot Encoding** for categorical features.  
- Evaluate model performance using accuracy metrics and feature importance visualizations.

## Datasets

The project uses two datasets:

- `telecom_demographics.csv`: Contains customer demographic information.
- `telecom_usage.csv`: Contains customer usage patterns and churn
information.

**Target variable:** `churn` (binary, 0 = not churned, 1 = churned)
