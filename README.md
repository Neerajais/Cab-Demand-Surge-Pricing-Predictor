# 🚕 Cab Demand & Surge Pricing Predictor

An end-to-end **Data Analytics & Machine Learning project** that forecasts cab demand, predicts surge pricing, and estimates ride cancellation risk across multiple city zones.  
Inspired by real-world ride-hailing platforms like **Ola / Uber / Rapido**.

🔗 **Live Demo:** Deployed on **Render**  
👉 https://cab-demand-prediction.onrender.com/

---

## 📌 Problem Statement
Ride-hailing platforms face challenges such as:
- Sudden demand spikes during peak hours
- Inefficient surge pricing strategies
- High ride cancellation rates
- Poor driver allocation across zones

This project leverages **Machine Learning & Time-Series Forecasting** to solve these problems using data-driven insights.

---

## 🎯 Project Objectives
- Forecast **24-hour cab demand** by zone
- Predict **surge pricing trends**
- Identify **high-demand hotspots**
- Predict **ride cancellation risk**
- Provide **actionable business insights** through dashboards

---

## 🧠 Solution Overview
The system combines **ML models + interactive dashboards** to simulate real-time decision-making for ride-hailing platforms.

### Key Modules:
- Demand Forecasting
- Surge Pricing Prediction
- Geo-Spatial & Heatmap Analysis
- Cancellation Risk Prediction
- Business KPI Dashboard

---

## 🛠️ Tech Stack
- **Programming:** Python  
- **Libraries:** Pandas, NumPy, Scikit-learn  
- **Visualization:** Matplotlib, Plotly  
- **Dashboard:** Streamlit  
- **Deployment:** Render  

---

## 🤖 Machine Learning Models Used

### 📈 Demand & Surge Forecasting
- ARIMA
- LSTM
- Prophet  
(Ensemble-based time-series forecasting)

### ⚠️ Cancellation Risk Prediction
- Logistic Regression
- Random Forest
- XGBoost (Ensemble Model)

---

## 📊 Dashboard Features

### 🧩 Main Dashboard
- Total rides
- Average surge multiplier
- Estimated revenue
- Top-performing zone
- Hourly demand trend

### 🔮 Demand Forecast
- 24-hour AI-predicted demand by zone
- Morning & evening peak detection

### 🔥 Heatmap Analysis
- Zone-wise demand intensity
- Cancellation rate
- Driver rating
- Hourly revenue insights

### 🌍 Geo-Spatial Analysis
- High-demand zones
- Ride distribution by area
- Peak-hour demand patterns

### ❌ Cancellation Prediction
- Ride-level cancellation risk scores
- Factors like:
  - High surge
  - Late-night rides
  - Long distance
  - Weather conditions

### 💸 Surge Pricing Forecast
- 24-hour surge trend
- Peak & low demand windows
- Surge multiplier insights

---

## 📈 Key Insights
- Peak demand occurs during **morning (8–10 AM)** and **evening (6–9 PM)**  
- Surge pricing can go up to **2.5x during rush hours**
- Cancellation risk increases with:
  - High surge
  - Late-night rides
  - Long-distance trips
- Zone-level insights help optimize **driver allocation & revenue**

---

## 🚀 Deployment
The application is deployed using **Render** for public access.

Steps:
1. Build Streamlit app
2. Configure `requirements.txt`
3. Deploy using Render Web Service
