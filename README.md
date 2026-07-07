# 📉 Customer Churn Prediction using Deep Learning

A Deep Learning project that predicts whether a customer is likely to leave a telecom service using an Artificial Neural Network (ANN) built with TensorFlow/Keras.

---

## 📌 Project Overview

Customer churn is one of the biggest challenges for subscription-based businesses. In this project, an Artificial Neural Network (ANN) is trained on the **Telco Customer Churn** dataset to classify whether a customer will churn based on demographic information, account details, and subscribed services.

The project covers the complete machine learning pipeline:

- Data Loading
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Data Preprocessing
- Feature Engineering
- One-Hot Encoding
- Feature Scaling
- Train-Test Split
- ANN Model Building
- Model Training
- Model Evaluation
- Predictions

---

## 📂 Dataset

**Dataset Used:** Telco Customer Churn Dataset

The dataset contains customer information such as:

- Gender
- Senior Citizen
- Partner
- Dependents
- Tenure
- Phone Service
- Internet Service
- Contract Type
- Monthly Charges
- Total Charges
- Payment Method
- Churn (Target Variable)

---

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- TensorFlow
- Keras

---

## 📊 Data Preprocessing

The following preprocessing steps were performed:

- Removed unnecessary columns (`customerID`)
- Converted `TotalCharges` and `MonthlyCharges` to numeric values
- Removed missing values
- Converted categorical values into numerical format
- Applied One-Hot Encoding
- Normalized numerical features
- Split dataset into training and testing sets

---

## 🧠 Model Architecture

The ANN consists of:

Input Layer
- 26 Input Features

Hidden Layer 1
- 20 Neurons
- ReLU Activation

Hidden Layer 2
- 15 Neurons
- ReLU Activation

Output Layer
- 1 Neuron
- Sigmoid Activation

### Loss Function

Binary Crossentropy

### Optimizer

Adam

### Evaluation Metric

Accuracy

---

## 📁 Project Structure

```
customer-churn-prediction/
│
├── Telco-Customer-Churn.csv
├── 04_churn_prediction.ipynb
├── README.md

```

---

## 📚 Learning Outcomes

This project helped in understanding:

- Data preprocessing techniques
- Handling categorical data
- Feature scaling
- Binary classification
- Building Deep Learning models using TensorFlow/Keras
- Model evaluation and prediction
- End-to-end Machine Learning workflow

---

## ⭐ If you found this project helpful

Please consider giving the repository a **⭐ Star** to support the project!
