# ❤️ Heart Disease Prediction Web App

A machine learning–based web application that predicts the risk of heart disease using patient health parameters.

## 🚀 Live Demo
🔗 https://heart-disease-prediction-app-cdo6fcce7agjvigxfqfacu.streamlit.app/

## 📌 Features
- Interactive Streamlit UI
- Machine Learning model (KNN / SVM)
- Real-time prediction
- Scaled input using StandardScaler

## 🛠 Tech Stack
- Python
- Streamlit
- Scikit-learn
- Pandas, NumPy
- Joblib

## 📊 Input Parameters
- Age
- Sex
- Chest Pain Type
- Resting Blood Pressure
- Cholesterol
- Fasting Blood Sugar
- Resting ECG
- Max Heart Rate
- Exercise-Induced Angina
- Oldpeak
- ST Slope

## 🧠 Model
- Algorithm: KNN / SVM
- Preprocessing: One-Hot Encoding, Feature Scaling
- Output: Binary classification (High risk / Low risk)

## ▶️ How to Run Locally
```bash
pip install -r requirements.txt
streamlit run heat.py
