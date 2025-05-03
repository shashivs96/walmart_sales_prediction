# Walmart Inventory Demand Forecasting

This project addresses a real-world business challenge faced by a retail store chain — optimizing inventory levels to better match demand and avoid under/overstocking issues. The dataset used contains historical sales data, and the project aims to forecast demand using data science techniques.

## 🧠 Problem Statement

A retail store with multiple outlets across the country is facing issues in managing inventory. The goal is to build a predictive model to forecast product demand, thereby helping in effective inventory planning and supply chain management.

## 🛠️ Tools and Technologies Used

- **Python**
- **Pandas, NumPy** for data manipulation
- **Matplotlib, Seaborn, Plotly** for data visualization
- **Scikit-learn** for modeling
- **Statistical modeling** with time series techniques

## 📈 Workflow Overview

1. **Data Loading and Cleaning**  
   Load the sales dataset (`Walmart.csv`), handle missing values, and perform initial inspection.

2. **Exploratory Data Analysis (EDA)**  
   Analyze sales trends, seasonality, and store-specific patterns using rich visualizations.

3. **Feature Engineering**  
   Extract features like month, year, week, etc. from the date column to improve model performance.

4. **Model Building and Evaluation**  
   Apply regression models to forecast demand and evaluate them using RMSE, MAE, and MAPE.

## 🚀 How to Run

1. Clone the repository or download the notebook:
   ```bash
   git clone https://github.com/shashivs96/walmart-inventory-forecasting.git
