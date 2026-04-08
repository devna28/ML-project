# Air-Quality-Index-Using-Machine-Learning---Mini-Project

This project uses a Random Forest Regressor to predict Carbon Monoxide ($CO(GT)$) levels based on various air quality sensor data and environmental factors. The model achieves high accuracy and provides insights into which pollutants are the strongest predictors of air quality.

## 📊 Project Overview

Predicting air quality is crucial for public health, environmental monitoring, and urban planning. This project leverages machine learning to estimate Carbon Monoxide (CO(GT)) levels using sensor data and environmental factors.

Using the UCI Air Quality Dataset, the project performs data preprocessing, feature engineering, and model training to build a reliable predictive system for real-time CO concentration.

## 🛠️ Tech Stack
Language: Python

Libraries: Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn

Model: Random Forest Regressor

## 🔍 Data Processing & Feature Engineering

### ✅ Data Cleaning

Replaced sensor error values (-200) with mean values to maintain data integrity.

### ⏱️ Feature Extraction

Extracted hour from the time column to capture daily traffic and pollution patterns.

### 📦 Outlier Detection

Used Interquartile Range (IQR) to identify and visualize pollution spikes across all 11 features.

### 📏 Feature Scaling

Applied StandardScaler to normalize feature ranges for improved model performance.

### 🚀 Model Performance

The dataset was split into 70% training and 30% testing.

R² Score: 0.88
→ The model explains 88% of the variance in CO levels.
Mean Absolute Error (MAE): 0.28
🧬 Features Used for Prediction (X)

## 🧪 Chemical Sensors

PT08.S1(CO)
C6H6(GT)
NOx(GT)
PT08.S3(NOx)
NO2(GT)
PT08.S4(NO2)
PT08.S5(O3)

## 🌡️ Environmental Factors

Temperature (T)
Relative Humidity (RH)
Absolute Humidity (AH)

## ⏰ Temporal Feature

Hour of the Day

## 📈 Visualizations

Correlation Heatmap
Shows relationships between different gas concentrations and environmental variables.
Outlier Boxplots
Highlights extreme pollution values and data distribution.
Actual vs Predicted Plot
Demonstrates the accuracy and reliability of the model.
Feature Importance Plot
Identifies key predictors:
Nitrogen Oxides (NOx)
Benzene (C6H6)
These are the most influential features for predicting CO levels.

## 🎯 Conclusion

The Random Forest Regressor model provides strong predictive performance for air quality analysis. By identifying key pollutants and patterns, this project can support smarter environmental monitoring and decision-making systems.
