# Linear regression with shallow neural networks
This repository contains a project where **shallow neural networks** are implemented to perform **linear regression** on environmental data. The goal is to model the relationship between **global temperature variations** and atmospheric conditions using neural networks.

## 📌 Project Overview

This project explores how **neural networks** can be used for **regression analysis**, predicting **monthly variations in average global temperature** based on multiple atmospheric and environmental factors.

The dataset includes:
- **Atmospheric gas concentrations** (e.g., CO₂, CH₄, NOₓ)
- **Density of suspended particles** (aerosols)
- **Solar radiation levels**
- **El Niño Southern Oscillation (ENSO) indices**

For more details on similar datasets and methodologies, visit:  
[MIT OpenCourseWare - The Analytics Edge](https://ocw.mit.edu/courses/sloan-school-of-management/15-071-the-analytics-edge-spring-2017/linear-regression/assignment-2/).

## 🚀 Approach

### 1️⃣ Data Preprocessing
- Load and clean environmental data  
- Normalize and standardize numerical features  
- Handle missing values and feature engineering  

### 2️⃣ Model Development
- Construct **shallow neural networks** (1-2 hidden layers)  
- Train models using **Mean Squared Error (MSE) loss**  
- Experiment with **activation functions** (ReLU, Tanh, Sigmoid)  
- Optimize using **Adam and Stochastic Gradient Descent (SGD)**  

### 3️⃣ Model Evaluation
- Compare **Neural Network Regression** with traditional **Linear Regression**  
- Assess performance using **MSE, R² score, and residual analysis**  
- Tune hyperparameters for improved accuracy  

### 4️⃣ Results & Insights
- Analyze the impact of **greenhouse gases and aerosols** on temperature variation  
- Examine **solar radiation and El Niño patterns** in climate trends  

## 📊 Dataset

The dataset consists of:
- **Climate indicators**: Monthly records of gas concentrations and aerosol density  
- **Temperature anomalies**: Global temperature variations over time  
- **External factors**: Solar activity, El Niño index  
