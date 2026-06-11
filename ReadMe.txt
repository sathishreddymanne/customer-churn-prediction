# Customer Churn Prediction

## Project Overview

Customer churn is one of the major challenges faced by telecom companies. This project focuses on predicting whether a customer is likely to leave the service based on factors such as tenure, monthly charges, contract details, and service usage patterns.

The goal of this project is to analyze customer behavior, identify churn-related patterns, and build machine learning models that can help businesses take proactive measures to retain customers.

## Dataset

The dataset contains customer information including:

* Gender
* Tenure
* Monthly Charges
* Internet Service
* Contract Details
* Churn Status

## Project Workflow

### Data Preprocessing

* Loaded and explored the dataset using Pandas.
* Handled missing values and checked for duplicate records.
* Performed data cleaning and feature preparation.
* Converted categorical variables into numerical format for model training.

### Exploratory Data Analysis (EDA)

* Analyzed churn distribution across customers.
* Studied the relationship between churn, tenure, and monthly charges.
* Generated visualizations using Matplotlib and Seaborn.
* Examined feature correlations to understand customer behavior.

### Model Development

The following machine learning models were trained and evaluated:

* Logistic Regression
* K-Nearest Neighbors (KNN)
* Support Vector Machine (SVM)
* Decision Tree Classifier
* Random Forest Classifier

### Model Evaluation

Models were evaluated using:

* Accuracy Score
* Confusion Matrix
* Classification Performance Comparison

Best model accuracy achieved: **86%**

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

## Key Learnings

* Data preprocessing and feature preparation
* Exploratory Data Analysis (EDA)
* Feature scaling techniques
* Classification algorithms
* Hyperparameter tuning using GridSearchCV
* Model evaluation and comparison

## Future Improvements

* Perform advanced feature engineering.
* Address class imbalance more effectively.
* Deploy the model using Flask or FastAPI.
* Build an interactive dashboard for churn prediction.
