# ⚡ Hourly Energy Consumption Forecasting
📈 **Time-Series Forecasting Project**  
📅 **Duration:** 2025  

---

## 📌 Project Overview
Forecasted hourly energy demand using an XGBoost regression model trained on lag and calendar-based features. The project demonstrates advanced feature engineering for time-series forecasting and performance comparison with ARIMA baseline models.

---

## 🚀 Key Highlights
- Created **lag**, **rolling mean**, and **calendar** features.  
- Applied **5-fold TimeSeriesSplit** cross-validation for evaluation.  
- Achieved **RMSE = 3740.77** and **MAPE ≈ 8.9%**.  
- Forecasting supports **energy planning and demand management**.

---

## 📁 Dataset
[Kaggle — PJME Hourly Energy Consumption Dataset](https://www.kaggle.com/datasets/robikscube/hourly-energy-consumption)

---

## 🧪 Libraries Used
`xgboost`, `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`

---

## 🧠 Learning Outcomes
- Time-series forecasting with gradient boosting models.  
- Advanced lag feature engineering and validation strategy.  
- Comparative analysis against ARIMA baseline.

---

## 📊 Evaluation Metrics
- **RMSE:** 3740.77  
- **MAPE:** 8.9%  

---

## ⚙️ How to Run
```bash
git clone https://github.com/your-username/Energy-Consumption-XGBoost.git
cd Energy-Consumption-XGBoost
pip install -r requirements.txt
jupyter notebook
