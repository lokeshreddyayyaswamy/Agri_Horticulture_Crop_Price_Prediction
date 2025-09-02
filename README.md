# 🌾 Agri-Commodity Price Forecasting

This project focuses on forecasting agricultural commodity prices using time-series analysis.  
We use historical data (up to **2014**) to build forecasting models such as **ARMA, ARIMA, and LSTM**.  

---

## 📂 Project Structure
- `Crop_Price_ARMA.ipynb` → Notebook for AR/ARMA-based price forecasting  
- `Crop_Price_Prediction.ipynb` → Notebook for ARIMA/LSTM and extended experiments  
- `README.md` → Project documentation  

---

## 📊 Dataset
- Dataset contains **daily prices** of agricultural commodities across different centres.  
- Columns typically include:
  - `Date`  
  - `Centre_Name`  
  - `Commodity_Name`  
  - `Season`  
  - `Price`  

⚠️ The available dataset has records **only up to 2014**. Forecasts are generated for later years using these historical values.  

---

## ⚙️ Methods Used
- **AR / ARMA / ARIMA** → Capturing time-series trends and seasonality  
- **LSTM** → Deep learning model for sequential data forecasting  

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/lokeshreddyayyaswamy/Agri_Horticulture_Crop_Price_Prediction.git
   cd Agri_Horticulture_Crop_Price_Prediction
