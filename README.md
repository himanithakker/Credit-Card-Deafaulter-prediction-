
# Credit Card Defaulter Prediction

## Overview

The main scope of this project is to predict the occurrence of credit card defaulters based on customers' previous history. We have utilized supervised machine learning techniques to analyze a Kaggle dataset of credit card defaulters. To manage the large dataset, we have used Google Colab for computation.

## Data Description

The dataset, collected from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/default+of+credit+card+clients), includes the following features:

- ID: ID of each client
- LIMIT_BAL: Amount of given credit in NT dollars
- SEX: Gender (1=male, 2=female)
- EDUCATION: Education level
- MARRIAGE: Marital status
- AGE: Age in years
- PAY_X: Repayment status in months
- BILL_AMTX: Amount of bill statement in months
- PAY_AMTX: Amount of previous payment in months
- default.payment.next.month: Default payment (1=yes, 0=no)

## Methodology

1. **Importing Libraries and Dependencies**
2. **Data Visualization and Analysis**
3. **Observing Feature Correlations**
4. **Data Cleaning and Preprocessing**
5. **Feature Scaling of Numerical Attributes**
6. **Applying Machine Learning Algorithms for Classification**
   - SVM
   - Decision Tree
   - Random Forest
   - Logistic Regression
   - K Nearest Neighbors
   - Ensemble Classifier using Decision Trees
7. **Applying Grid-Search CV for Hyperparameter Tuning**
8. **Performance Evaluation of Models**

## Conclusion

Using various machine learning techniques, we achieved the following results for predicting credit card defaulters:

- Logistic Regression: 82.5% accuracy
- Stochastic Gradient Descent: 83.33% accuracy
- Support Vector Machine: 80.83% accuracy
- K-Nearest Neighbors: 80.83% accuracy
- Decision Tree: 82.83% accuracy
- Random Forest: 81% accuracy
- XGBOOST: 82.16% accuracy

The strongest predictors of default are the previous repayment status (PAY_X), credit limit (LIMIT_BAL), and previous payment amount (PAY_AMTX).

Among these techniques, Stochastic Gradient Descent and Decision Tree demonstrated better predictive performance.

Feel free to explore the project for more details and insights.

