# 🏡 California Housing Price Prediction

This project aims to build a Machine Learning model to predict the median house prices in California based on various features such as geographic location, number of rooms, building age, and environmental factors.

The model was trained using the publicly available California Housing Dataset (1990) and evaluated using regression metrics including MAE, MAPE, and R² Score.  
The project also includes visual data analysis and model interpretation using SHAP values to identify the most influential features affecting house prices.

## 🚀 Project Overview

This project aims to build a machine learning model to **predict median house prices** in California based on features such as geographic location, population density, building age, and household income.

The goal is not just to predict accurately, but also to understand which features influence housing prices the most — providing insight for potential real estate investment or pricing strategies.

---

## 🎯 Objectives

- Predict housing prices using regression models.
- Evaluate performance using metrics: **MAE**, **MAPE**, and **R² Score**.
- Compare multiple ML algorithms and tune their performance.
- Interpret model results and feature importance using **SHAP**.

---

## 🔍 Key Insights

✅ **Best Model**: XGBoost Regressor  
✅ **Best R² Score**: 0.83  
✅ **Top Features**:
- Median Income 💰
- Geographic Location (Latitude & Longitude) 📍
- Rooms per Household 🏘️

Interpretability is enhanced using **SHAP values**, allowing a deeper understanding of how each feature impacts the prediction.

---

## 🛠️ Tech Stack

- **Python** (pandas, numpy, matplotlib, seaborn)
- **scikit-learn**, **XGBoost**, **SHAP**
- **Jupyter Notebook**
- **VS Code**, **Git**, **GitHub**

---

## 📊 Project Workflow

```text
📁 california-housing-capstone
│
├── data/                # Raw and cleaned dataset
├── notebooks/           # Main analysis and modeling notebooks
├── models/              # Saved models (if any)
├── images/              # Graphs and visualizations
├── requirements.txt     # Environment dependencies
└── README.md            # Project documentation
