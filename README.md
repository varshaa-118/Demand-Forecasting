.

📊 Demand Forecasting with Prophet (Retail Sales)
Forecast weekly sales for a retail store using Facebook Prophet with external features like temperature, fuel price, and unemployment rate.

🚀 Project Overview
Retail businesses rely heavily on accurate demand forecasts to optimize inventory, reduce overstock/understock situations, and improve customer satisfaction.

This project applies Facebook Prophet for time series forecasting on a real-world Walmart dataset — including:

🏪 Sales per store per department

🌡️ Temperature

⛽ Fuel price

📉 CPI and Unemployment

🏷️ Holiday effect

✅ Key Results
Metric	Value
📈 MAE	1098.13
📉 RMSE	1717.36
📁 Dataset Details
The dataset is from Kaggle - Walmart Store Sales Forecasting and includes:

sales.csv: Weekly sales data (by store & department)

features.csv: Extra variables (markdowns, fuel price, temperature, CPI, etc.)

stores.csv: Store metadata (type, size)

🧠 Model Used
Facebook Prophet

Additive time series model with trend, seasonality, and holiday components

Incorporates external regressors (temperature, fuel price, etc.)

🧪 Features Used
📆 Weekly Date

🌡️ Temperature

⛽ Fuel Price

📊 CPI

📉 Unemployment Rate

🛠️ How to Run This Project
🔗 Clone the repo or open in Google Colab

📂 Upload the 3 CSV files:

sales.csv

features.csv

stores.csv

▶️ Run all cells

📉 Forecast sales and view evaluation metrics + plots

📸 Visualization
📈 Actual vs Predicted Weekly Sales


↑ Replace with your actual plot or Colab export

📦 Tech Stack
Python

Pandas & NumPy

Facebook Prophet

scikit-learn

Matplotlib

✨ Highlights
Handles missing data

Memory-efficient for Colab runtime

Regressor-enriched Prophet model

MAE & RMSE optimized

🧹 Future Improvements
Multi-store modeling in batches

Model versioning with MLflow

Advanced hyperparameter tuning

Add holiday effects explicitly




