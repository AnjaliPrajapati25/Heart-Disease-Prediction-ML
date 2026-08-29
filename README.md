# ❤️ Heart Disease Prediction using Machine Learning

A machine learning-based web application that predicts the risk of heart disease based on patient health-related attributes.

The project includes the complete machine learning workflow, from exploratory data analysis and preprocessing to model comparison, model selection, and deployment through a Streamlit web application.

<br/>

## 📸 Application Preview

<img width="669" height="857" alt="app" src="https://github.com/user-attachments/assets/99559dd4-adb1-4966-bb8b-a61eefa106e5" />

<br><br>

## 📌 Project Overview

This project uses a heart disease dataset containing **918 records** and patient-related features such as age, sex, chest pain type, resting blood pressure, cholesterol, fasting blood sugar, resting ECG, maximum heart rate, exercise-induced angina, oldpeak, and ST slope.

Several classification algorithms were trained and evaluated, and **K-Nearest Neighbors (KNN)** achieved the best performance among the tested models.

<br>

## 🎯 Objective

The objective of this project is to build a machine learning classification system that predicts whether a patient is at:

* 🟢 Low Risk of Heart Disease
* 🔴 High Risk of Heart Disease

The prediction is intended for educational and demonstration purposes and should not be considered a medical diagnosis.

<br><br>


## 🛠️ Technologies Used

### Programming Language

* Python

### Data Analysis

* Pandas
* NumPy

### Data Visualization

* Matplotlib
* Seaborn

### Machine Learning

* Scikit-learn
* K-Nearest Neighbors (KNN)
* Logistic Regression
* Naive Bayes
* Decision Tree
* Support Vector Machine (SVM)
* StandardScaler

### Deployment / Frontend

* Streamlit

### Model Serialization

* Joblib

<br>

## 🔄 Machine Learning Workflow

```text
Dataset
   ↓
Data Loading
   ↓
Exploratory Data Analysis
   ↓
Data Preprocessing
   ↓
Categorical Feature Encoding
   ↓
Train-Test Split
   ↓
Feature Scaling
   ↓
Model Training
   ↓
Model Evaluation
   ↓
Model Selection
   ↓
Save Trained Model
   ↓
Streamlit Application
   ↓
Heart Disease Prediction
```

<br>

## 📊 Model Performance

The following classification models were evaluated:

| Model               |   Accuracy |   F1 Score |
| ------------------- | ---------: | ---------: |
| Logistic Regression |     87.50% |     88.78% |
| **KNN**             | **88.59%** | **89.86%** |
| Naive Bayes         |     86.96% |     87.88% |
| Decision Tree       |     74.46% |     75.39% |
| SVM (RBF Kernel)    |     86.41% |     88.04% |

### 🏆 Selected Model

**K-Nearest Neighbors (KNN)** was selected because it achieved the highest accuracy and F1 score among the evaluated models.

<br><br>

## 🧹 Data Preprocessing

The dataset contains both numerical and categorical features.

Categorical variables were converted into numerical features using one-hot encoding. The resulting features were then converted to integer values.

The dataset was divided into training and testing sets using an **80:20 split** with stratification.

`StandardScaler` was applied to the training and testing features before model training.

<br>

## 🌐 Streamlit Application

The Streamlit application provides an interactive interface where users can enter patient information such as:

* Age
* Sex
* Chest Pain Type
* Resting Blood Pressure
* Cholesterol
* Fasting Blood Sugar
* Resting ECG
* Maximum Heart Rate
* Exercise-Induced Angina
* Oldpeak
* ST Slope

After clicking the **Predict** button, the application processes the input using the saved scaler and KNN model and displays the prediction.

<br>

## ✨ Key Highlights

* End-to-end machine learning project from data preprocessing to deployment
* Comparison of multiple classification algorithms
* KNN selected based on the highest Accuracy and F1 Score
* Interactive Streamlit-based prediction interface
* Saved trained model, scaler, and feature columns using Joblib
* Simple and user-friendly interface for entering patient information

<br>

## 🌟 Conclusion
```
This project demonstrates the practical application of machine learning in healthcare through data analysis, model comparison, and an interactive prediction interface. It showcases the complete process of building and deploying a machine learning model using Python and Streamlit.
```



