# Credit_Card_Approval-ML_project
💳 Credit Card Approval Prediction System - A complete end-to-end Machine Learning + Web App project that predicts whether a person will be approved for credit card based on their input information.

---

## 🧠 Use Case

Credit card companies and banks need a reliable system to evaluate whether an applicant is **eligible for credit card approval**.  
This project automates the process using a trained **Machine Learning model** and provides predictions via a clean **Streamlit frontend** and a **FastAPI backend**.

---

## 🚀 Tech Stack

| Layer      | Tech Used                        |
|------------|----------------------------------|
| ML Model   | Scikit-learn, Pandas, Joblib     |
| Backend    | FastAPI, NumPy                   |
| Frontend   | Streamlit, Requests              |
| Deployment | Localhost                        |

---

## 📁 Project Structure

#### credit-card-approval-prediction
- app.py # ML model training & evaluation
- main.py # FastAPI backend to serve predictions
- streamlit.py # Streamlit frontend UI
- rf_model.pkl # Saved trained Random Forest model
- scaler.pkl # Saved StandardScaler object
- clean_dataset.csv # Cleaned dataset used for training
- README.md # You're reading it

---

## 🎯 Features

- 🔍 Clean dataset processing & visualizations
- 🧠 ML Models:
  - Logistic Regression
  - Random Forest Classifier ✅ (Best Accuracy)
  - Support Vector Machine
- 🧪 Accuracy comparison of models
- 🔗 REST API endpoint for predictions
- 🖥️ User-friendly Streamlit frontend
- 💡 JSON-based request/response format

---

### 📊 Accuracy Comparison of ML Models

- Logistic Regression ~ 83%
- Random Forest Classifier ~ 91% (Best)
- Support Vector Machine ~ 85%
