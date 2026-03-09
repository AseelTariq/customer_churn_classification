# Customer Churn Prediction using Machine Learning

This project applies machine learning techniques to predict customer churn in a banking dataset.  
Customer churn prediction helps organizations identify customers who are likely to leave and take proactive actions to improve retention.

---

## Project Objective
The goal of this project is to build and compare multiple machine learning models to determine the most effective approach for predicting customer churn.

---

## Dataset
The dataset contains information about 10,000 bank customers with features describing customer demographics, financial behavior, and service usage.

Example features:
- CreditScore
- Age
- Tenure
- Balance
- Number of Products
- Estimated Salary
- Geography
- Gender
- Active Member Status

Target variable:
- Exited (0 = Customer stayed, 1 = Customer churned)

---

## Machine Learning Models
The following classification models were implemented and compared:

- LightGBM
- K-Nearest Neighbors (KNN)
- Naive Bayes

LightGBM achieved the best overall performance due to its ability to model complex relationships in structured data.

---

## Project Workflow
1. Data preprocessing and cleaning  
2. Categorical feature encoding  
3. Feature scaling  
4. Feature engineering  
5. Model training and testing  
6. Model comparison and evaluation  

---

## Evaluation Metrics
The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- ROC-AUC

---

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- LightGBM
- Matplotlib

---

## Project Goal
To compare different machine learning models and identify the most effective approach for predicting customer churn in structured banking data.
