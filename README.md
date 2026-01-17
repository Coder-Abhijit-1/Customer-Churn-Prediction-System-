📉 Customer Churn Prediction System
📌 Overview

The Customer Churn Prediction System is a machine learning–based project that predicts whether a telecom customer is likely to churn or stay with the company. The system analyzes customer behavior, service usage, and account-related information to identify high-risk customers and provide churn probability.

This project demonstrates an end-to-end machine learning workflow using real-world telecom data.
---
🎯 Problem Statement

Customer churn is a major challenge for telecom companies, leading to revenue loss and reduced customer base. Traditional churn identification methods are manual and inefficient. This project aims to build a data-driven churn prediction system that helps businesses proactively identify customers who are likely to leave.

🧠 Solution Approach

Collect telecom customer data from Kaggle

Perform data analysis and visualization

Clean and preprocess the dataset

Apply feature encoding and transformation

Train multiple machine learning models

Select the best-performing model for prediction

🛠️ Technologies Used

Python

NumPy

Pandas

Matplotlib

Seaborn

Scikit-learn

Jupyter Notebook

📊 Dataset

Source: Kaggle
Dataset: Telco Customer Churn Dataset

The dataset includes:

Customer demographics (gender, senior citizen, partner, dependents)

Account information (tenure, contract type, payment method)

Service details (internet service, phone service)

Billing information (monthly charges, total charges)

Target Variable:

1 → Churn

0 → Not Churn

🚀 How It Works

Load the telecom dataset

Analyze dataset structure and missing values

Perform data cleaning and preprocessing

Apply One-Hot Encoding to categorical variables

Conduct Exploratory Data Analysis (EDA)

Train machine learning models:

Decision Tree Classifier

Random Forest Classifier

Select Random Forest as the final model

Provide numerical input values

Get churn prediction and churn risk percentage

▶️ How to Run the Project

Clone the repository:

git clone https://github.com/your-username/Customer-Churn-Prediction-System.git


Navigate to the project directory

Open Jupyter Notebook:

jupyter notebook


Run all cells to train the model and test predictions

✅ Results

The Random Forest Classifier produced reliable predictions with good accuracy. The system successfully identifies customers who are likely to churn and provides a churn probability score to measure risk level.

🔮 Future Enhancements

Deploy the model using Flask or Streamlit

Perform hyperparameter tuning for better accuracy

Add advanced models like XGBoost

Build a user-friendly web interface

Integrate real-time customer data

👤 Author

Abhijit Mondal
Final Year B.Tech (IT)
Asansol Engineering College
