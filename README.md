# Churn Prediction

This project aims to predict customer churn for a telecommunications company using machine learning techniques.

## Project Overview

The goal of this project is to analyze customer data and build a model that can predict whether a customer is likely to churn (discontinue their service) or not. We use various classification algorithms and compare their performance to find the best model for this task.

## Dataset

The dataset used in this project is the "Telco-Customer-Churn" dataset, which contains information about:
- Customer demographics (gender, age, partners, dependents)
- Account information (tenure, contract type, payment method)
- Services each customer has signed up for (phone, internet, online security, etc.)
- Charges (monthly and total)

## Methodology

1. Data Preprocessing:
   - Handling missing values
   - Encoding categorical variables
   - Feature selection using SelectKBest

2. Exploratory Data Analysis:
   - Visualizing the distribution of features
   - Analyzing correlations between features

3. Addressing Class Imbalance:
   - Using SMOTEENN for oversampling and undersampling

4. Model Building and Evaluation:
   - Logistic Regression
   - Random Forest Classifier
   - Decision Tree Classifier
   - Gradient Boosting Classifier

5. Hyperparameter Tuning:
   - Using RandomizedSearchCV for Gradient Boosting Classifier

6. Model Deployment:
   - Saving the best model using pickle for future use

## Results

After comparing different models, the Gradient Boosting Classifier showed the best performance with an accuracy of 97.17% after hyperparameter tuning.

## How to Use

1. Clone this repository
2. Install the required packages (listed in requirements.txt)
3. Run the Jupyter notebook or Python script
4. To make predictions on new data, use the saved model 'Model.sav'




