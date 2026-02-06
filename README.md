# Fuel Cost Forecasting for Fleet Management 🚗⛽

**Author:** Ioanna Lagou  
**Date:** Feb 2026  

This project predicts **next-month fuel cost per vehicle** using historical fleet data.  
It includes **exploratory data analysis (EDA)** and model comparison to support fleet management decisions.

## 📌 Problem Statement
Fleet managers need to forecast fuel expenses and identify high-cost vehicles to optimize budgeting and maintenance planning.

## 📊 Dataset
- Vehicles: type, brand, region  
- Fuel usage: month, km_driven, fuel_cost, fuel_type  
- Time period: Sep 2025 – Jan 2026 (synthetic data)

## 🔍 Exploratory Data Analysis (EDA)
- Missing values check  
- Monthly fuel cost trends  
- Total km driven per vehicle  
- Regional analysis (after merging vehicle metadata)

## 🧠 Modeling
**Target:** Next-month fuel cost per vehicle  
**Features:** km_driven, current fuel_cost

**Models compared:**
- Linear Regression  
- Random Forest Regression  

**Metrics:**
- MAE (Mean Absolute Error)  
- RMSE (Root Mean Squared Error)

Linear Regression achieved the best performance on this dataset.

## 🛠 Tech Stack
- Python  
- pandas, numpy  
- scikit-learn  
- matplotlib  
- SQLite  
- Jupyter Notebook

## ▶️ How to Run
```bash
pip install -r requirements.txt
jupyter notebook
