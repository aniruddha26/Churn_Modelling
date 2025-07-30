# Churn Modelling using ANN

This is a practice deep learning project for predicting customer churn in a bank using a simple Artificial Neural Network (ANN). The model classifies whether a customer will leave the bank or not based on various features.

## 🔍 Problem Statement

Customer churn is a critical business problem in the banking sector. The goal of this project is to build a binary classification model that predicts if a customer is likely to leave the bank.

## 🧠 Model Overview

- **Model Type:** Artificial Neural Network (ANN)
- **Hidden Layers:** 2
- **Activation Functions:** ReLU (hidden layers), Sigmoid (output layer)

## ⚙️ Technologies and Concepts Used

- **Python**
- **Deep Learning with Keras/TensorFlow**
- **Data Preprocessing:**
  - Label Encoding
  - One Hot Encoding
  - Feature Scaling (StandardScaler)
- **Model Evaluation:**
  - Accuracy
  - Confusion Matrix

## 📁 Dataset

The dataset used is a bank customer dataset which includes features like geography, gender, age, balance, credit score, etc.

> 📌 Note: The dataset is included in the repository for practice purposes only.

## 🚀 Getting Started

1. Clone the repository:
   bash
   git clone https://github.com/aniruddha26/Churn_Modelling.git
   cd Churn_Modelling

2. Install the required packages:
   bash
   Copy
   Edit
   pip install -r requirements.txt

3. Run the notebook or Python script to train the model.

## 📊 Results
The ANN was able to achieve good classification accuracy on the test set. The final model was evaluated using metrics like accuracy and confusion matrix.

## 👨‍💻 Author
Aniruddha Alkari

## 📌 Disclaimer
This project is for educational and practice purposes only. It is not production-ready.