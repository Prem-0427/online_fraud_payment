💳 Online Payment Fraud Detection System using Machine Learning
📌 Project Overview
The Online Payment Fraud Detection System is a machine learning–based web application designed to detect fraudulent financial transactions. With the rapid increase in digital payments, fraud detection has become essential to protect users and financial institutions from financial losses.
This system uses machine learning classification algorithms to analyze transaction details and predict whether a transaction is Fraudulent or Safe. The trained model is integrated into a Flask web application to provide real-time predictions through a user-friendly interface.
🎯 Project Objectives
Detect fraudulent online transactions using machine learning
Reduce financial losses caused by fraud
Provide real-time fraud prediction through a web interface
Demonstrate integration of ML models with web applications
🧠 Machine Learning Algorithms Used
The following classification algorithms were used:
Logistic Regression
Decision Tree
Random Forest
XGBoost
Each model was evaluated using:
Accuracy
Confusion Matrix
Classification Report
The best-performing model was selected and saved as model.pkl.
📊 Dataset Information
The dataset contains online transaction details such as:
Step (Time of transaction)
Type (PAYMENT, TRANSFER, CASH_OUT, etc.)
Amount
Old balance of sender
New balance of sender
Old balance of receiver
New balance of receiver
Fraud label (0 = Safe, 1 = Fraud)
Dataset Source: Financial transaction dataset (Kaggle / online payment dataset)
🏗️ System Architecture
User → Web Interface → Flask Backend → ML Model → Prediction → Result Display
💻 Technology Stack
Frontend
HTML
CSS
Backend
Python
Flask
Machine Learning
Scikit-learn
Pandas
NumPy
Deployment
Render / Localhost
Version Control
Git
GitHub
📁 Project Structure
online-fraud-detection/
│
├── app.py                  # Flask application
├── train_model.py         # Model training script
├── model.pkl              # Trained machine learning model
├── encoder.pkl            # Label encoder
├── requirements.txt       # Python dependencies
│
├── templates/
│   ├── home.html          # Home page
│   ├── predict.html       # Input form page
│   └── submit.html        # Result page
│
└── README.md              # Project documentation
