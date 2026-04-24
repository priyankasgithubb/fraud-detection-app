Fraud Detection Web App

A Machine Learning-based web application that predicts whether a financial transaction is fraudulent or not. Built using a trained ML pipeline and deployed with Streamlit for an interactive user interface.

Overview

Fraudulent financial transactions are a major concern in digital payments. This project uses a trained Machine Learning model to classify transactions as **fraudulent** or **legitimate** based on transaction details.

The application provides a simple interface where users can input transaction data and get instant predictions.

Live Demo Link :
https://fraud-detection-app-24.streamlit.app/

Tech Stack

**Programming Language:** Python
**Machine Learning:** scikit-learn
**Frontend/UI:** Streamlit
**Data Handling:** Pandas
**Model Serialization:** Joblib

---

Features

Real-time fraud prediction
Clean and interactive UI
Preprocessing + model pipeline integration
Easy-to-use input fields
Lightweight and fast


Input Parameters

The model takes the following inputs:

**Transaction Type** (PAYMENT, TRANSFER, CASH_OUT)
**Amount**
**Old Balance (Sender)**
**New Balance (Sender)**
**Old Balance (Receiver)**
**New Balance (Receiver)**


App Preview

<img width="536" height="635" alt="image" src="https://github.com/user-attachments/assets/59ced754-5cf2-485c-bceb-bebbf6d6b640" />


Dataset

The dataset is not included in this repository due to size limitations.

You can use any similar financial transaction dataset or download one from:

Kaggle (recommended)


Model Details

* Model Used: Logistic Regression
* Pipeline includes preprocessing + model
* Handles categorical and numerical features
