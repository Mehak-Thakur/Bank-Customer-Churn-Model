Bank Customer Churn Prediction
This repository contains a comprehensive machine learning project aimed at predicting customer churn in the banking sector. The project leverages Support Vector Machine (SVC) and includes advanced techniques like hyperparameter tuning, data resampling (Random Over-Sampling and Random Under-Sampling), and standardization to enhance model performance.

Project Overview
Customer churn is a critical issue for banks, as retaining customers is more cost-effective than acquiring new ones. This project builds a robust predictive model to identify customers who are likely to churn, enabling proactive retention strategies.

Key Features
Support Vector Machine (SVC): A powerful algorithm for classification tasks.
Data Balancing: Handles class imbalance using Random Over-Sampling and Random Under-Sampling techniques.
Hyperparameter Tuning: Fine-tunes the model parameters using GridSearchCV.
Standardization: Ensures all features have the same scale for optimal model performance.
Steps Included
Data Preparation:

Import and explore the dataset.
Handle missing values and perform feature engineering.
Data Preprocessing:

Split the data into training and testing sets.
Standardize the feature set for consistency.
Data Resampling:

Address class imbalance using Random Over-Sampling and Under-Sampling techniques.
Model Building:

Train a Support Vector Machine classifier on the processed data.
Hyperparameter Tuning:

Use GridSearchCV for finding the best hyperparameters.
Evaluation:

Assess the model performance using metrics like accuracy, precision, recall, F1-score, and confusion matrix.
