Predict Heart Disease
A web application to predict the risk of heart disease using machine learning. Users can input their health data, and the app predicts whether they are at risk of heart disease based on a trained KNN model.

Demo
App Screenshot
Add a screenshot of your Streamlit app if possible

Features
User-friendly web interface built with Streamlit
Predicts heart disease risk (high/low) from user inputs
Uses a trained KNN classifier
Scales user inputs appropriately
Handles categorical features automatically
Quick and interactive predictions
Dataset
The model is trained on the Heart Disease dataset, which includes the following features:
Age, Sex, Chest Pain Type, Resting BP, Cholesterol, Fasting Blood Sugar, Resting ECG, Max Heart Rate, Exercise Angina, Oldpeak, ST Slope, HeartDisease (target)
How It Works
Data Preprocessing:

Handles missing/zero values by imputing with mean values.
Encodes categorical variables using one-hot encoding.
Scales numerical features for model compatibility.
Model Training:

K-Nearest Neighbors (KNN) classifier is trained on the processed data.
Model is saved as KNN_heart.pkl, along with the scaler and feature columns.
Prediction Web App:

Built with Streamlit.
Loads the trained model, scaler, and column info at runtime.
Collects user health parameters.
Preprocesses input to match training format.
Outputs risk prediction (High/Low).
