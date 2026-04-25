# Solar Radiation Drift Correction Using Machine Learning and Deep Learning

## 📌 Project Overview

This project addresses the challenge of reconstructing accurate **incoming shortwave solar radiation measurements** in the presence of sensor drift.

Using data from the **Trans-African Hydro-Meteorological Observatory (TAHMO)** network, the study applies both **machine learning** and **deep learning techniques** to predict solar radiation values at 15-minute intervals, particularly for periods where sensor readings are unreliable or missing.

---

## 🎯 Problem Statement

Solar radiation sensors deployed in weather stations degrade over time due to environmental exposure, resulting in **nonlinear drift and measurement bias**.

This affects:

* Climate monitoring
* Agricultural planning
* Renewable energy forecasting

The objective of this project is to develop a **data-driven model** capable of reconstructing accurate solar radiation values using available meteorological variables.

---

## 🎯 Objectives

### General Objective

To develop a predictive system for reconstructing solar radiation data under sensor drift conditions.

### Specific Objectives

* Perform exploratory data analysis on time-series weather data
* Preprocess and clean multi-station meteorological datasets
* Engineer temporal and environmental features
* Implement baseline and advanced regression models
* Develop deep learning models for time-series prediction
* Evaluate and compare model performance

---

## 🧪 Dataset Description

The dataset is obtained from the **TAHMO Solar Radiation Prediction Challenge (Zindi)**.

### Key Characteristics:

* Data recorded at **15-minute intervals**
* Collected from **50 weather stations**
* Includes:

  * Solar radiation (target variable)
  * Temperature
  * Relative humidity
  * Rainfall
* Training data: **odd months**
* Test data: **even months (to be predicted)**

---

## 🔁 Machine Learning Workflow

1. Data Collection
2. Exploratory Data Analysis (EDA)
3. Data Cleaning & Preprocessing
4. Feature Engineering
5. Model Development
6. Model Evaluation
7. Submission Generation

---

## ⚙️ Models Implemented

### 🔹 Baseline Models

* Linear Regression
* Ridge / Lasso Regression

### 🔹 Advanced Machine Learning Models

* Random Forest Regressor
* Gradient Boosting
* XGBoost / LightGBM

### 🔹 Deep Learning Models

* Feedforward Neural Networks (MLP)
* Long Short-Term Memory (LSTM) Networks
* Recurrent Neural Networks (RNN)

---

## 📊 Evaluation Metrics

* Root Mean Squared Error (RMSE)
* Mean Absolute Error (MAE)

---

## ⚠️ Key Challenges Addressed

* Sensor drift and measurement bias
* Missing data reconstruction
* Multi-station variability
* Temporal dependencies in time-series data
* Integration of external environmental data

---

## 📁 Project Structure

* `data/` → raw, processed, and external datasets
* `notebooks/` → EDA, modeling, and experiments
* `src/` → reusable code modules
* `experiments/` → experiment tracking and configurations
* `results/` → predictions, plots, and evaluation metrics
* `submissions/` → competition submission files
* `reports/` → figures and final documentation

---

## 🚀 Expected Contribution

This project provides:

* A scalable solution for correcting sensor drift
* Comparative analysis of ML and DL models for time-series regression
* Insights into temporal modeling for environmental data

---

## 🌍 Significance

The study contributes to improving:

* Meteorological data quality in Africa
* Solar energy forecasting
* Climate research and environmental monitoring

---

## 🧠 Conclusion

By leveraging machine learning and deep learning techniques, this project aims to reconstruct reliable solar radiation data, enabling better decision-making in climate-sensitive sectors.

---
