# Predict Heart Disease

**A web application to predict the risk of heart disease using machine learning.**  
Users can input their health data, and the app predicts whether they are at risk of heart disease based on a trained **KNN classifier**.

---

## 🚀 Demo

<img width="991" height="770" alt="image" src="https://github.com/user-attachments/assets/4b2e6be3-a74d-4b2b-bf2c-6307a4917ef8" />


---

## ✨ Features

- **User-friendly web interface built with Streamlit**
- **Predicts heart disease risk (High/Low) from user inputs**
- **Uses a trained KNN classifier**
- **Scales user inputs appropriately**
- **Handles categorical features automatically**
- **Quick and interactive predictions**

---

## 📊 Dataset

The model is trained on the Heart Disease dataset, which includes the following features:

- **Age**
- **Sex**
- **Chest Pain Type**
- **Resting BP**
- **Cholesterol**
- **Fasting Blood Sugar**
- **Resting ECG**
- **Max Heart Rate**
- **Exercise Angina**
- **Oldpeak**
- **ST Slope**
- **HeartDisease (target)**

---

## ⚙️ How It Works

### 1. Data Preprocessing

- Handles missing/zero values by imputing with mean values.
- Encodes categorical variables using one-hot encoding.
- Scales numerical features for model compatibility.

### 2. Model Training

- **K-Nearest Neighbors (KNN) classifier** is trained on the processed data.
- Model is saved as `KNN_heart.pkl`, along with the scaler and feature columns.

### 3. Prediction Web App

- Built with **Streamlit**.
- Loads the trained model, scaler, and column info at runtime.
- Collects user health parameters.
- Preprocesses input to match training format.
- Outputs risk prediction (**High/Low**).

---

*Feel free to update this README with additional details, screenshots, or usage instructions as your project evolves!*
