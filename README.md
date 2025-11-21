# Price Insights Dashboard – India Wholesale Price Analysis & Forecasting

## 📌 Purpose
This project analyzes India’s Wholesale Price Index (WPI) data to understand:
- How commodity prices have changed over time  
- Which items show high inflation  
- Which commodities are most volatile  
- How prices behave seasonally  
- What future price trends may look like  

The goal is to provide clear and accurate **price insights and short-term forecasts** using simple analytical tools.

---

## 🛠 Tech Stack Used
This project is built using only three tools:

### **1. Excel**
- Data cleaning  
- Calculations (MoM, YoY, volatility, seasonality)  
- Pivot tables  

### **2. MySQL**
- Store cleaned time-series data  
- Run analytical SQL queries for trends, ranking, and volatility  

### **3. Power BI**
- Interactive dashboard  
- Trend analysis  
- Inflation ranking  
- Volatility charts  
- Seasonal heatmaps  
- Forecast visualization  

---

## 📊 What This Project Analyzes

### **Inflation Metrics**
- **YoY Inflation %** (Year-over-Year change)  
- **MoM Inflation %** (Month-over-Month change)  
- **Overall Inflation (2012–2023)**  

### **Volatility Metrics**
- Standard deviation of monthly prices  
- Identify stable vs. unstable commodities  

### **Seasonality**
- Find months with recurring price spikes  
- Seasonal heatmap for all major commodities  

### **Trend Analysis**
- 10+ year price trends  
- Food vs Non-food comparison  
- Cereal vs Vegetable comparison  

### **Ranking & Comparison**
- Highest inflation commodities  
- Items with biggest rise in the last 1 year  
- Commodity correlations (e.g., Wheat vs Rice, Onion vs Tomato)

---

## 🔮 Forecasting Summary
- Prepare monthly time-series for each commodity  
- Train **ARIMA** or **Prophet** forecasting model  
- Predict next **6–12 months**  
- Import forecast output into Power BI for visualization  

This helps users understand expected price movement using proven time-series models.
