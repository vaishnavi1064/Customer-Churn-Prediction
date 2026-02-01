# 🎮 Video Game Sales Prediction Web App

A Django-based web application that predicts video game sales using a trained Machine Learning model, demonstrating an end-to-end ML workflow from data analysis to deployment.

## 🚀 Overview
- Analyzed a structured video game sales dataset using exploratory data analysis (EDA) to identify trends across platforms, genres, and regions, informing feature selection for predictive modeling  
- Trained and compared regression models (Linear Regression and Support Vector Regression) using scikit-learn to predict global video game sales, and serialized the best-performing model for production inference  
- Deployed the trained model within a Django web application by implementing inference-time feature encoding and validation logic, enabling real-time sales predictions through a user-facing interface  

## 🧠 Tech Stack
- Python, Django  
- Scikit-learn  
- Pandas, NumPy  
- SQLite  
- Heroku  

## ▶️ Run Locally
```bash
git clone https://github.com/your-username/video-games-sales.git
cd video-games-sales
pip install -r requirements.txt
python manage.py runserver
