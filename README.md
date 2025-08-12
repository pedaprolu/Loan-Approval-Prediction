
# Loan Approval Prediction

## 📌 Overview
This project aims to predict whether a loan application will be approved based on applicant details such as income, credit history, loan amount, and other demographic and financial attributes. The model can help financial institutions make quicker, more data-driven lending decisions.

---

## 📊 Dataset
- **Rows:** ~X
- **Columns:** X features + target variable (`Loan_Status`)
- **Target Variable:** 
  - `Y` = Loan Approved
  - `N` = Loan Not Approved

---

## 🔍 Project Workflow
1. **Data Cleaning & Preprocessing**
   - Handle missing values
   - Encode categorical variables
   - Scale numerical features
   - Handle class imbalance (SMOTE)

2. **Exploratory Data Analysis (EDA)**
   - Univariate & Bivariate analysis
   - Correlation heatmaps
   - Distribution plots

3. **Modeling**
   - Logistic Regression
   - Decision Tree
   - Random Forest
   - XGBoost

4. **Evaluation Metrics**
   - Accuracy
   - Precision, Recall, F1-score
   - ROC-AUC Curve

5. **Best Model**
   - **XGBoost** achieved the highest accuracy of **XX%**

---

## 🛠️ Technologies Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- XGBoost
- Imbalanced-learn
- Jupyter Notebook

---

## 📂 Repository Contents
- `notebooks/` – Jupyter notebook with complete analysis
- `reports/` – Project report & presentation
- `requirements.txt` – Python dependencies
- `README.md` – Project documentation

---
