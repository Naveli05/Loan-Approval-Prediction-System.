# 🏦 Loan Approval Prediction using Machine Learning

This project builds an end-to-end **Loan Approval Prediction System** using Python and Machine Learning.  
It analyzes applicant demographics, financial details, and credit behavior to predict whether a loan should be approved.

---

## 🚀 Project Overview

Banks receive thousands of loan applications daily, making manual review slow and error-prone.  
This project uses **data preprocessing**, **EDA**, and **ML models** to automate loan approval decisions.

The dataset includes:
- Applicant personal information  
- Income & employment details  
- Credit history  
- Target variable: repayment behavior  

---

## 🧹 Data Cleaning & Preprocessing

- Removed duplicates  
- Treated missing values  
- Converted negative day counters into real values  
- Handled outliers in income & employment  
- Label-encoded categorical features  
- Standardized numerical columns  

### 🔧 Feature Engineering
Created useful derived features:
- **Age**  
- **Years Employed**  
- **Employment Flag (Is_Working)**  
- **Account Length (from credit history)**  
- **Household Size**  
- **Unemployed Flag**  
- Cleaned education, occupation & housing categories  

---

## 📊 Exploratory Data Analysis (EDA)

Performed detailed analysis including:
- Distribution of age, income, dependents  
- Countplots of gender, housing type, education  
- Target variable imbalance  
- Correlation heatmap  
- Loan approval vs credit behavior insights  

---

## 🤖 Machine Learning Models

Several classification models were trained and compared:

- Logistic Regression  
- KNN Classifier  
- SVM  
- Decision Tree  
- Random Forest  
- AdaBoost  

📌 **Best Model:** **KNN Classifier**  
It performed best in recall, especially for detecting *risky applicants (class 1)*.

---

## 🎯 Key Insights

- Dataset was imbalanced; KNN handled class 1 better.  
- Income, credit history, employment status, and education had strong influence.  
- Model can help automate and speed up loan approval workflows.  

---

## 🛠 Tech Stack

- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-Learn  
- Jupyter Notebook  

---

## 📁 Project Highlights

- Full data cleaning & feature engineering  
- Extensive EDA  
- Multiple ML models with comparison  
- Final model selected based on accuracy & recall  
- End-to-end predictive modeling  

---

## ✔ Final Outcome

An ML-based solution that predicts loan approval decisions and can help financial institutions:
- Improve accuracy  
- Reduce manual workload  
- Identify risky applicants  
- Speed up loan processing  

---

