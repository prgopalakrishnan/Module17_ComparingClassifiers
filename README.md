# Bank Marketing Classifier Comparison - Assignment 17.1

## Project Overview
This project analyzes a dataset from a Portuguese banking institution containing the results of multiple marketing campaigns. The goal is to predict whether a client will subscribe to a term deposit using various machine learning classifiers. This helps the bank prioritize clients with the highest probability of subscribing, improving marketing efficiency.

## Dataset
- Source: [UCI Machine Learning Repository - Bank Marketing Dataset](https://archive.ics.uci.edu/ml/datasets/bank+marketing)
- Description: Contains client demographic information, campaign history, and past contact outcomes.
- Observations: 41,188
- Features: 20 attributes including age, job, marital status, balance, and campaign-related variables.

## Methodology
1. **Data Preparation**
   - Handling missing values
   - Encoding categorical variables
   - Feature scaling for numerical columns
2. **Exploratory Data Analysis (EDA)**
   - Distribution of target variable
   - Correlation heatmaps
   - Visual insights on features
3. **Machine Learning Models**
   - Logistic Regression
   - Decision Tree
   - K-Nearest Neighbors (KNN)
   - Support Vector Machines (SVM)
4. **Evaluation**
   - Accuracy
   - ROC-AUC
   - F1-score
   - Confusion matrix
5. **Hyperparameter Tuning**
   - Grid search on Decision Tree for max_depth, min_samples_split, and min_samples_leaf
6. **Insights & Recommendations**
   - Key predictors of client subscription
   - Business recommendations for targeting high-probability clients

## Findings
- Previous positive contact outcomes, age, and balance are strong predictors.
- Decision Trees provide interpretable rules for actionable marketing.
- Logistic Regression and Decision Trees are fast and interpretable; SVM gives slightly higher accuracy but is slower.
- Marketing campaigns should prioritize high-probability clients identified by the models.

## Next Steps
- Experiment with ensemble models (Random Forest, Gradient Boosting) for improved accuracy.
- Continuously update models with new campaign data.
- Automate predictions for dynamic campaign targeting.
