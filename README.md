# 🌾 Agri-Commodity Price Forecasting

This project focuses on forecasting agricultural commodity prices using time-series analysis.  
We use a cleaned dataset (`Cleaned_Dataset.csv`) that contains daily price information for multiple commodities and centres across India, up to the year **2014**.  

---

## 📂 Dataset
- **File:** `Cleaned_Dataset.csv`  
- **Columns:**
  - `Date` → Daily record of prices (till 2014)  
  - `Centre_Name` → Market/Centre name  
  - `Commodity_Name` → Name of the commodity (e.g., Onion, Potato, Pulses)  
  - `Season` → Season information  
  - `Price` → Recorded price  

---

## ⚙️ Methods Used
- **AR / ARIMA Models** → Statistical forecasting methods for trend and seasonality  
- **LSTM** → Deep learning model for sequential data forecasting  

The models are trained on historical data (till 2014) and can forecast prices for upcoming years.

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/<your-repo-name>.git
   cd <your-repo-name>
