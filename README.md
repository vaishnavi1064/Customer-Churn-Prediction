# 📉 Customer Churn Prediction

A machine learning project focused on predicting customer churn using structured customer behavior data. The project demonstrates an end-to-end classification workflow, from exploratory data analysis to model training and evaluation.

## 🚀 Overview
- Performed exploratory data analysis (EDA) on customer behavior data and identified class imbalance, with approximately 20–25% of customers churning, guiding metric selection and modeling strategy  
- Trained and optimized multiple classification models (Logistic Regression, Random Forest, and XGBoost) using GridSearchCV and RandomizedSearchCV  
- Evaluated model performance using ROC-AUC, recall, and confusion matrices on an 80/20 train–test split to prioritize churn detection  

## 🧠 Tech Stack
- Python  
- Scikit-learn  
- XGBoost  
- Pandas, NumPy  
- Matplotlib, Seaborn  

## 📊 Dataset
- Structured customer-level dataset containing demographic, account, and service usage features  
- Target variable: customer churn (binary classification)  

## ▶️ Run Locally
```bash
git clone https://github.com/your-username/customer-churn-prediction.git
cd customer-churn-prediction
pip install -r requirements.txt
python churn_prediction.py
