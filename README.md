# Smart Temperature Prediction using IoT Sensor Data

## Overview
This project presents a machine learning-based framework for short-term temperature prediction using IoT environmental sensor data.

The system is designed for smart-city HVAC optimization, enabling efficient energy usage and improved thermal comfort.

## Dataset
- 405,184 records collected over 7 days
- Features:
  - Temperature
  - Humidity
  - CO, LPG, Smoke
  - Light, Motion

## Methodology
1. Data preprocessing and standardization
2. Exploratory Data Analysis (EDA)
3. Model training using:
   - Linear Regression
   - Decision Tree
   - KNN
   - Random Forest
   - Gradient Boosting
   - XGBoost (Best)

## Results
- Best Model: **XGBoost**
- R² Score: **0.934**
- RMSE: **0.334**
- Most predictions within ±1°C

## Explainability
- Feature importance analysis
- SHAP-based interpretation
- Key features: Humidity, Light, CO

## Applications
- Smart building HVAC systems
- Energy optimization
- Real-time environmental monitoring

## Paper
Published in IEEE ICECTE 2026

## Author
Payel Sen
MSc CSE, CUET
