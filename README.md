# 🏦 Home Loan Default - Risk Management

## 📌 Problem Statement

This project addresses the critical task of identifying loan defaulters using machine learning techniques. The aim is to assist financial institutions in minimizing risk by predicting whether an applicant is likely to default on a loan, based on historical financial and credit data.

---

## 📁 Dataset Information

🔗 **Dataset Link**: [Download Here](https://d3ilbtxij3aepc.cloudfront.net/projects/CDS-Capstone-Projects/PRCP-1006-HomeLoanDef.zip)

### 📂 Files Used

- `application_train.csv`: Main dataset with the target variable (`TARGET`) - 1 for Defaulter, 0 for Non-defaulter
- `bureau.csv`: Previous credits reported to Credit Bureau
- `bureau_balance.csv`: Monthly status of those credits
- `POS_CASH_balance.csv`: POS and cash loans monthly data
- `credit_card_balance.csv`: Monthly balances of applicant’s credit cards
- `previous_application.csv`: All previous Home Credit loan applications
- `installments_payments.csv`: History of payments and missed payments

---

## 🔍 Tasks Completed

### ✅ Task 1: Exploratory Data Analysis (EDA)

- Reviewed distribution of target variable
- Analyzed demographic and financial features
- Visualized feature relationships and trends
- Handled missing values and outliers

### ✅ Task 2: Predictive Modeling

Built and evaluated the following models:

- Logistic Regression
- Decision Tree Classifier
- K-Nearest Neighbors (KNN)
- Random Forest Classifier
- XGBoost Classifier

Applied:
- Label Encoding and One-Hot Encoding
- Feature scaling (for KNN, Logistic Regression)
- Hyperparameter tuning using GridSearchCV and cross-validation

**XGBoost** gave the best performance and was selected for final prediction.

---

## ⚙️ Technologies & Libraries Used

- Python
- Jupyter Notebook
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- XGBoost

---

