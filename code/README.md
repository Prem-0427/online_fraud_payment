# 🛡️ Online Fraud Detection System

A Machine Learning based web application that detects fraudulent financial transactions using classification algorithms.  
The system predicts whether a transaction is Fraudulent or Legitimate based on transaction details.

---

## 📌 Project Description

Online financial fraud has increased significantly with digital transactions.  
This project aims to detect fraudulent transactions using supervised machine learning algorithms.

The model is trained on transaction data and deployed using Flask to provide real-time fraud prediction via a web interface.

---

## 🎯 Project Objectives

- Understand fraud detection using Machine Learning
- Perform data preprocessing and feature engineering
- Train multiple classification models
- Compare model performance
- Deploy the best model using Flask
- Provide real-time prediction through web UI

---

## 🧠 Machine Learning Models Used

The following classification algorithms were implemented:

- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost

Each model was evaluated using:

- Accuracy
- Confusion Matrix
- Classification Report

The best performing model was selected and saved using pickle.

---

## 📊 Dataset

Dataset used: Financial Fraud Transaction Dataset  
Target column: `isFraud`

Main features include:

- step
- type
- amount
- oldbalanceOrg
- newbalanceOrig
- oldbalanceDest
- newbalanceDest

---

## ⚙️ Technologies Used

### Programming Language
- Python 3.x

### Libraries
- pandas
- numpy
- scikit-learn
- xgboost
- matplotlib
- seaborn
- pickle
- Flask

### Tools
- Anaconda
- VS Code / PyCharm
- Git & GitHub
- Render (for deployment)

---

## 🏗️ Project Structure

