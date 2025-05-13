# Comparative Analysis of Machine Learning Regression Models for Soybean Yield and Biofuel Output Forecasting

## Overview
This repository contains the code, data, and documentation for my MSc thesis in IT for Business Data Analytics, titled **"Comparative Analysis of Machine Learning Regression Models for Soybean Yield and Biofuel Output Forecasting."** The project explores the application of machine learning (ML) techniques to predict soybean harvesting volumes and soybean-based biofuel production using historical data spanning from 1948 to 2024. The study leverages datasets from governmental agencies, financial markets, and climate records to build and evaluate predictive models, providing actionable insights for stakeholders in agriculture and renewable energy sectors.

## Key Objectives
1. **Develop ML Models**: Implement and compare multiple regression models, including Linear Regression, Random Forest (RF), Bayesian Regression, K-Nearest Neighbors (KNN), and Artificial Neural Networks (ANNs), to forecast soybean yields and biofuel production.
2. **Identify Key Drivers**: Analyze feature importance to understand the economic, environmental, and geopolitical factors influencing soybean and biofuel outputs.
3. **Provide Business Insights**: Offer recommendations for farmers, agribusinesses, biofuel producers, policymakers, and technology providers based on model performance and findings.
4. **Enhance Predictive Accuracy**: Explore data preprocessing, feature selection, and hyperparameter tuning to optimize model performance.

## Dataset Sources
The project integrates data from multiple authoritative sources:
- **USDA:NASS**: Historical soybean production metrics for Illinois (1948–2024).
- **USDA:ERS**: Food expenditure trends, bioenergy statistics, and import/export data.
- **USDE:AFDC**: Energy price movements for biodiesel, gasoline, and other fuels (2000–2024).
- **FRED**: Producer Price Index (PPI) for nitrogenous fertilizers (1975–2024).
- **Macrotrends**: Soybean commodity market prices (1971–2024).
- **Illinois State Water Survey**: Climate and weather records (1989–2024).

## Methodology
1. **Data Exploration and Visualization**: Identified correlations and trends using Python libraries like `pandas`, `matplotlib`, and `seaborn`.
2. **Data Preprocessing**: Handled missing values, removed collinear features, and standardized data using `StandardScaler`.
3. **Model Implementation**: Trained and evaluated regression models (`scikit-learn`) with cross-validation and hyperparameter tuning (`GridSearchCV`).
4. **Performance Metrics**: Assessed models using R², RMSE, MAE, and feature importance analysis.

## Key Findings
- **Soybean Yield Prediction**: The Random Forest model outperformed others with a test R² of **0.79**, while linear models suffered from overfitting.
- **Biofuel Production Prediction**: Bayesian Regression and ANNs achieved the highest accuracy (test R² of **0.97**), highlighting the predictability of economic-driven outputs.
- **Feature Importance**: Fertilizer/energy costs and soybean oil supply were critical predictors, while temperature trends showed minimal impact.

## Business Implications
- **Farmers/Agribusinesses**: Use ensemble models (e.g., RF) for yield forecasting to optimize planting and resource allocation.
- **Biofuel Producers**: Leverage high-performing models (e.g., Bayesian Regression) to align production with market demand.
- **Policymakers**: Promote data transparency and sustainable practices to mitigate supply chain volatility.
- **Technology Providers**: Develop user-friendly tools integrating IoT and real-time monitoring for precision agriculture.

