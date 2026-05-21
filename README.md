# Diabetes Classification App

A Machine Learning web application that predicts whether a person is diabetic or non-diabetic based on medical input features.

## Project Overview

This project uses a Logistic Regression model trained on the Pima Indians Diabetes Dataset.  
The application is deployed using Streamlit for interactive user predictions.

## Features

- Predicts diabetes status in real time
- User-friendly web interface
- Machine Learning based prediction system
- Feature scaling using StandardScaler
- Deployed using Streamlit Cloud

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Streamlit

## Machine Learning Workflow

1. Data Loading
2. Data Preprocessing
3. Train-Test Split
4. Logistic Regression Model Training
5. Model Evaluation
6. ROC-AUC Analysis
7. Feature Scaling
8. Model Deployment

## Model Performance

### Logistic Regression
- Accuracy: ~75%
- ROC-AUC Score: ~0.81

The model was evaluated using:
- Confusion Matrix
- Classification Report
- ROC Curve
- AUC Score

## Dataset

Dataset used:
Pima Indians Diabetes Dataset

Features include:
- Pregnancies
- Glucose
- Blood Pressure
- Skin Thickness
- Insulin
- BMI
- Diabetes Pedigree Function
- Age

Target:
- Outcome (Diabetic / Non-Diabetic)

## Project Structure

```text
diabetes-classification/
│
├── app.py
├── diabetes_model.pkl
├── scaler.pkl
├── requirements.txt
└── README.md
