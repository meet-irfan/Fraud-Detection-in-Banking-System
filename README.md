# ♻ Fraud-Detection-in-Banking-System
This project implements a Fraud Detection System for banking transactions using the XGBoost machine learning algorithm. The goal is to classify transactions as either Fraudulent or Non-Fraudulent based on input features such as transaction amount, transaction time, and transaction type. The system includes a web-based interface using Gradio for ease of use.

Key Features:
XGBoost Classifier: A robust gradient-boosting algorithm used for high accuracy in fraud detection.
Scalable Input Data: Features are scaled using StandardScaler to optimize model performance.
Web-Based GUI: The Gradio interface provides a simple way to input transaction data and receive predictions in real-time.
Modular Code: The code is well-organized for easy understanding and extension.
# Technologies Used:
Python <br>
XGBoost <br>
Scikit-learn <br>
Gradio <br>
Pandas and NumPy <br>
Project Setup <br>
Prerequisites: <br>
# Ensure you have the following libraries installed in your environment: 

Python 3.x <br>
XGBoost <br>
Scikit-learn <br>
Gradio <br>
Joblib <br>
Pandas <br>
# Project Structure
fraud-detection-banking <br>

├── app.py                 ✔  Main file to launch the Gradio interface <br>
├── train_model.py           ✔ Script for training and saving the XGBoost model <br>
├── requirements.txt         ✔ List of required packages <br>
├── xgboost_fraud_model.pkl  ✔  Pre-trained XGBoost model <br>
├── scaler.pkl               ✔ Scaler used for transforming input data <br>
├── README.md                 ✔ Project documentation <br>
└── credit_card_data.csv      ✔ Sample dataset (if applicable) <br>

# Dataset 
You can download the dataset from Kaggle and use it to train the model. <br>
Link : https://www.kaggle.com/datasets?search=credit_card_data.csv <br>

# License
This project is licensed under the MIT License - see the LICENSE file for details. 




NumPy <br>
