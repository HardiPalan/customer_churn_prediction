# Customer Churn Prediction

This project is focused on predicting customer churn using machine learning models. Customer churn refers to when customers stop doing business with a company, and predicting churn can help businesses take proactive steps to retain customers. The model is built using a dataset of customer information, including various factors that influence customer retention.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Model Building](#model-building)
- [Results](#results)

## Project Overview

The primary objective of this project is to predict whether a customer will churn (leave the company) based on historical data. Using various machine learning algorithms, this model can help businesses identify at-risk customers and take action to reduce churn.

## Dataset

The dataset includes customer information such as:
- **Customer ID**: Unique identifier for each customer
- **Gender**: Gender of the customer
- **Senior Citizen**: Whether the customer is a senior citizen
- **Partner**: Whether the customer has a partner
- **Dependents**: Whether the customer has dependents
- **Tenure**: Number of months the customer has been with the company
- **PhoneService**: Whether the customer has phone service
- **InternetService**: Type of internet service used
- **Contract**: Contract type (Month-to-month, One year, Two year)
- **MonthlyCharges**: The amount charged to the customer monthly
- **TotalCharges**: The total amount charged during the tenure
- **Churn**: Whether the customer churned (dependent variable)

## Exploratory Data Analysis

An Exploratory Data Analysis (EDA) was performed to understand the dataset and its characteristics:
- Analyzing the distribution of features such as tenure, contract type, and monthly charges.
- Studying the correlation between independent variables and churn.
- Visualizing the data using histograms, heatmaps, and boxplots to detect outliers and patterns.

## Model Building

Several machine learning models were built and evaluated to predict customer churn:
1. **Logistic Regression**: A simple and interpretable model for binary classification.
2. **Decision Tree Classifier**: To capture non-linear relationships between features and churn.
3. **Random Forest Classifier**: An ensemble method to improve accuracy by averaging multiple decision trees.
4. **Support Vector Machine (SVM)**: A powerful classification algorithm that works well for higher-dimensional data.
5. **Gradient Boosting Classifier**: An advanced ensemble method that boosts weak learners.

Key evaluation metrics used for model comparison:
- **Accuracy**
- **Precision**
- **Recall**
- **F1-Score**

## Results

The best-performing model was the **Random Forest Classifier**, which achieved the following performance metrics:
- **Accuracy**: 82%
- **Precision**: 0.79
- **Recall**: 0.76
- **F1-Score**: 0.77

The model successfully identifies customers at risk of churn, allowing businesses to take targeted actions.
