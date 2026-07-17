# Customer Churn Prediction using Machine Learning

## Project Overview

Customer churn prediction is a machine learning classification problem where the goal is to predict whether a customer is likely to leave a service.

In this project, I built an end-to-end machine learning pipeline to predict customer churn using different classification algorithms and selected the best model based on performance metrics.

The project includes data analysis, preprocessing, feature engineering, model training, evaluation, model comparison, and hyperparameter tuning.

---

## Problem Statement

A bank wants to identify customers who are likely to churn so that it can take preventive actions and improve customer retention.

The objective is to build a classification model that predicts whether a customer will subscribe or not based on customer information.

---

## Dataset

Dataset: UCI Bank Marketing Dataset

Source:
https://archive.ics.uci.edu/dataset/222/bank+marketing

The dataset contains customer information such as:

- Age
- Job
- Education
- Marital status
- Contact details
- Previous campaign information
- Economic indicators

Target Variable:

- `y`
  - yes → Customer subscribed
  - no → Customer did not subscribe

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost

---

## Machine Learning Workflow

### 1. Data Understanding

- Dataset shape and information
- Data types analysis
- Target variable analysis

### 2. Data Cleaning

- Removed duplicate records
- Checked missing values
- Handled categorical values

### 3. Exploratory Data Analysis (EDA)

- Target distribution analysis
- Feature distribution analysis
- Correlation analysis

### 4. Data Preprocessing

- Train-Test Split
- One Hot Encoding for categorical features
- Standard Scaling for numerical features

### 5. Model Training

Models trained and compared:

- Logistic Regression
- Balanced Logistic Regression
- Decision Tree
- Random Forest
- XGBoost

---

## Model Comparison

| Model | Accuracy | Recall |
|------|----------|--------|
| Logistic Regression | 90.95% | 42.24% |
| Balanced Logistic Regression | 86.42% | 90.84% |
| Decision Tree | 89.02% | 51.08% |
| Random Forest | 91.40% | 46.66% |
| XGBoost | 91.07% | 54.63% |

---

## Final Model

Selected Model:

Balanced Logistic Regression

Reason:

The dataset was imbalanced, so recall for the positive class was more important than only accuracy.

Performance:

- Recall: ~91%
- F1-score: ~60%
- ROC-AUC: ~0.94

---

## Key Learnings

- Handling imbalanced datasets
- Understanding precision and recall trade-offs
- Feature preprocessing for machine learning models
- Comparing multiple classification algorithms
- Hyperparameter tuning using GridSearchCV
- Evaluating models beyond accuracy

---

## Project Structure

