# Insurance Fraud Detection Using Machine Learning

## Introduction
This project focuses on detecting fraudulent insurance claims using supervised machine learning models. By analyzing historical insurance claim data, the goal is to build models that classify claims as fraudulent or genuine, helping improve risk assessment and decision-making in the insurance process.

---

## Background
Insurance fraud is a significant challenge that results in substantial financial losses. Accurate fraud detection systems help reduce operational costs, improve claim verification, and enhance efficiency.

This project demonstrates an end-to-end machine learning pipeline including data cleaning, feature engineering, model training, and performance evaluation using Python and Scikit-learn.

---

## Project Objectives

1. Prepare and clean raw insurance claim data for modeling  
2. Engineer meaningful features for fraud prediction  
3. Compare Logistic Regression and Random Forest models  
4. Identify the best-performing classification model  
5. Evaluate model performance using appropriate metrics  

---

## Tools & Technologies Used

- Python  
- Jupyter Notebook  
- Pandas and NumPy  
- Scikit-learn  

---


---

## Workflow Overview

### 1. Data Cleaning
Notebook: Data-Cleaning.ipynb

- Loaded raw insurance claim dataset  
- Handled missing and inconsistent values  
- Converted data into suitable formats for modeling  

Outcome: Clean dataset ready for feature engineering.

---

### 2. Feature Engineering
Notebook: Feature_Engineering.ipynb

- Encoded categorical variables  
- Selected relevant predictive features  
- Prepared dataset for machine learning algorithms  

Outcome: Structured dataset optimized for classification tasks.

---

### 3. Model Training

Logistic Regression  
Notebook: Logistic_Model.ipynb  
- Built baseline classification model  
- Evaluated prediction performance  

Random Forest Classifier  
Notebook: RandomForest_Model.ipynb  
- Implemented ensemble learning model  
- Compared results against Logistic Regression  

---

### 4. Best Model Selection
Notebook: Best_Model.ipynb

- Compared model evaluation metrics  
- Selected the best-performing model based on accuracy  

---

## Key Findings

- Data preprocessing significantly improved model performance  
- Feature engineering enhanced prediction capability  
- Random Forest achieved higher accuracy than Logistic Regression  
- Random Forest captured complex relationships in the dataset more effectively  
- Ensemble learning proved more suitable for this fraud detection task  

---

## Model Evaluation Metrics

Models are evaluated using:

- Accuracy  
- Precision  
- Recall  
- F1-Score  

These metrics provide a reliable assessment for fraud classification problems.

---

## What I Learned

- Practical experience in data preprocessing and feature engineering  
- Comparing machine learning models on real-world datasets  
- Understanding why ensemble models often outperform linear models  
- Importance of evaluation metrics in fraud detection systems  

---

## Future Improvements

- Test advanced models such as XGBoost  
- Handle class imbalance using resampling techniques  
- Deploy model for real-time fraud detection  

---


