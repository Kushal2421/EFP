# ⚡ Electricity Bill Forecasting & Fraud Detection

A full-stack data science project that forecasts monthly electricity bills and detects potential fraud in semi-urban households, using historical usage data, weather conditions, and device consumption patterns.

## 🚀 Project Overview

This project aims to:
- 🔮 **Forecast electricity bills** based on historical consumption, weather, and device usage.
- 🚨 **Detect possible fraud** by identifying anomalies in usage and billing.
- 📊 Provide an **interactive dashboard** for users to analyze trends and predict future bills.

---

## 🛠️ Features

- 📅 Filter bills by **month and year**
- 📈 **Visual trend analysis** of historical bills
- 🤖 **ML-powered prediction** of future bills
- 🔍 **Fraud detection** using pattern analysis
- 🎨 **Modern Streamlit dashboard** with dark mode styling
- 💾 Model saved and loaded using Joblib

---

## 🧪 Sample Dataset

```csv
| date       | bill_amount | units_used | device_usage_kwh | weather | is_fraud |
|------------|-------------|------------|------------------|---------|----------|
| 6/1/2024   | 1200        | 200        | 180              | hot     | 0        |
| 7/1/2024   | 1250        | 210        | 190              | hot     | 0        |
| 8/1/2024   | 1800        | 310        | 180              | hot     | 1        |


💻 How to Run
1. Clone this repository
git clone https://github.com/your-username/electricity-bill-forecasting.git
cd electricity-bill-forecasting

2. Install dependencies
pip install -r requirements.txt

3. Run the dashboard
streamlit run dashboard.py

