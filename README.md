
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
- Jupyter Notebook

**📈 Model Evaluation
Model performance was evaluated using multiple metrics to ensure robustness and reliability:

**Accuracy

Proportion of correctly predicted instances out of the total.

Suitable for balanced datasets but can be misleading for imbalanced data.

Precision, Recall, and F1-Score

Precision: Proportion of true positives out of all predicted positives.

Recall: Proportion of true positives out of all actual positives.

F1-Score: Harmonic mean of precision and recall, balancing both measures.

ROC-AUC

Measures the ability of the model to distinguish between classes.

Higher values indicate better classification performance.

**✅ Conclusion
The project successfully developed and evaluated multiple machine learning models to predict loan approval outcomes.
Key insights include:

Significant predictors: Applicant income, credit history, loan amount, and property area strongly influence approval decisions.

The best-performing model achieved strong accuracy, balanced precision-recall performance, and a high ROC-AUC score.

The model can serve as a decision-support tool for financial institutions to streamline the loan approval process and reduce manual effort.






