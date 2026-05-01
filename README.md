# 📊 Loan Default Risk Prediction & Credit Risk Analytics System

An advanced **Machine Learning-based Credit Risk Analytics System** designed to predict loan default probability, identify key risk drivers, and support financial decision-making using multiple models and statistical techniques.

---

## 🚀 Project Overview

Loan defaults pose a significant challenge to financial institutions, leading to increased non-performing assets (NPAs) and financial losses.

This project develops an **end-to-end predictive system** that:
- Classifies loan applicants as **default / non-default**
- Identifies **key features influencing risk**
- Compares multiple ML models for optimal performance
- Incorporates **time-series forecasting** for default trends

---

## 🎯 Objectives

- Predict loan approval / default risk using ML models  
- Identify **important risk factors** affecting default  
- Perform **feature selection and multicollinearity analysis**  
- Compare multiple classification algorithms  
- Analyze **default trends over time**

---

## 🧠 Business Problem

Financial institutions face challenges in:
- Identifying high-risk borrowers  
- Reducing bad loans  
- Improving credit decision-making  

👉 This system helps:
- Improve **loan approval accuracy**
- Reduce **credit risk exposure**
- Enable **data-driven lending strategies**

---

## ⚙️ Tech Stack

- **Programming:** Python  
- **ML Models:** Logistic Regression, Decision Tree, Random Forest, Gradient Boosting  
- **Feature Engineering:** Label Encoding, RFE  
- **Statistical Analysis:** VIF (Multicollinearity)  
- **Time Series:** Prophet  
- **Libraries:** Pandas, NumPy, Scikit-learn, Statsmodels  
- **Visualization:** Matplotlib, Seaborn  

---

## 📂 Project Workflow

Data Collection
↓
Data Cleaning & Encoding
↓
Feature Engineering
↓
Feature Selection (RFE)
↓
Multicollinearity Check (VIF)
↓
Model Training (Multiple Models)
↓
Model Evaluation
↓
Feature Importance Analysis
↓
Time Series Forecasting (Prophet)


---

## 🤖 Machine Learning Models Used

- **Logistic Regression** → Baseline model  
- **Decision Tree** → Rule-based classification  
- **Random Forest** → Ensemble learning  
- **Gradient Boosting** → High-performance boosting model  

---

## 📊 Model Evaluation

Evaluation metrics used:
- Accuracy  
- F1-Score  
- Classification Report  

> 📌 Replace with your actual values:
- Logistic Regression Accuracy: 85%  
- Random Forest Accuracy: 90%  
- Gradient Boosting Accuracy: 89%  

---

## 🔍 Feature Engineering & Selection

### ✔ Label Encoding
- Converted categorical variables into numerical format  

### ✔ Recursive Feature Elimination (RFE)
- Selected top **15 important features**  

### ✔ VIF (Variance Inflation Factor)
- Identified multicollinearity between features  

---

## 📈 Feature Importance Insights

Using Random Forest:

- Top features influencing loan approval:
  - Credit-related attributes  
  - Income level  
  - Employment status  
  - Loan amount  

👉 These features are critical for **credit risk assessment**

---

## ⏳ Time Series Analysis

- Created a **Default variable**
- Aggregated monthly default counts  
- Used **Prophet model** to forecast future defaults  

👉 This adds a **predictive business dimension**:
- Helps banks anticipate future risk trends  

---

## 💡 Key Insights

- Financial indicators strongly influence loan approval  
- Ensemble models outperform baseline models  
- Feature selection improves model efficiency  
- Default trends can be forecasted using time-series models  

---

## 🔮 Future Improvements

- Hyperparameter tuning (GridSearchCV)  
- ROC-AUC and confusion matrix visualization  
- SHAP for model explainability  
- Deployment using Streamlit / Flask  
- Cloud deployment (AWS / Azure)  

---

## ▶️ How to Run
git clone https://github.com/Happy295-hue/loan-default-risk-prediction.git

cd loan-default-risk-prediction
pip install -r requirements.txt

---

## Author
Harshit Saraf <br>
Business Analyst

# ⭐ If you found this project useful, consider giving it a star!
