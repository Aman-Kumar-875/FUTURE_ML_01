# 📊 Retail Sales Forecasting with Python & Power BI

This project was developed as part of the **Future Interns** Machine Learning internship program.  
The goal was to build a predictive model for retail sales and visualize past and future trends using **Power BI**.

---

## 🔍 Project Objective

To analyze historical retail sales data and develop a forecasting model that:
- Predicts future sales
- Identifies monthly seasonality, weekday trends, and holiday spikes
- Presents insights in an interactive dashboard

---

## 🚀 Tools & Technologies Used

- Python (Google Colab)
- Pandas, NumPy
- Seaborn, Matplotlib
- Prophet (for time-series forecasting)
- XGBoost (for regression model)
- Power BI (for dashboard)
- Git & GitHub (for version control)

---

## 📁 Dataset

- Source: [Kaggle – Retail Sales Forecasting](https://www.kaggle.com/datasets/tevecsystems/retail-sales-forecasting)
- File Used: `mockkaggle.csv`
- Features:
  - `date` (datetime)
  - `sales` (int)
  - `price` (float)
  - `stock` (simulated / engineered)

---

## 🧠 Feature Engineering

- Extracted `Month`, `MonthName`, `Weekday`, `HolidayLabel`
- Rolling average (7-day) of sales
- Added `PredictionError` and `PercentageError`
- Created trend indicators for holidays and weekdays

---

## 🧪 Model Development (XGBoost)

- Trained model using engineered features
- Evaluated using MAE, RMSE, and R² Score
- Predicted future sales values

---

## 📊 Power BI Dashboard Features

- 📈 Sales trend line (Actual vs Forecast)
- 🗓️ Monthly & Yearly comparisons
- 🧠 Weekday-based insights
- 🎉 Holiday vs Non-Holiday performance
- 📦 Stock vs Sales visualization
- 📌 KPI Cards showing total sales, error range, etc.
