# 🧠 Alzheimer's Disease Prediction System

## 📌 Project Overview

The **Alzheimer's Disease Prediction System** is a Machine Learning web application developed using **Python, Scikit-learn, and Streamlit**.

The application uses demographic, medical, lifestyle, cognitive, and symptom-related information to predict the likelihood of Alzheimer's disease.

The trained **Gradient Boosting Classifier** is integrated into an interactive Streamlit web application, allowing users to enter patient-related information and receive a model-based prediction.

> ⚠️ This application is intended for educational and research purposes only. It is not a medical diagnostic tool and should not be used as a substitute for professional medical advice.

---

## 🚀 Live Demo

🌐 **Streamlit App:**  
https://alzheimers-disease-classification-rtgxmsoe6zmchhsudtzw3f.streamlit.app/

---

## 📊 Model Performance

The selected Gradient Boosting model achieved:

- **Accuracy:** 95.12%
- **ROC-AUC:** 94.93%

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Joblib
- Streamlit
- Jupyter Notebook

---

## 🤖 Machine Learning Model

The project uses a **Gradient Boosting Classifier** as the final selected model.

The trained model and preprocessing scaler are saved using Joblib:

- `alzheimers_gb_model.pkl`
- `scaler.pkl`

These files are loaded by the Streamlit application to generate predictions.

---

## 📂 Project Structure

```text
Alzheimers-disease-classification/
│
├── app.py
├── requirements.txt
├── alzheimers_gb_model.pkl
└── scaler.pkl
