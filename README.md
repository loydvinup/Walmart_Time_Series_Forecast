# 📊 Walmart Sales Time Series Forecasting

## 📌 Project Overview
This project focuses on analyzing and forecasting Walmart's weekly sales using time series techniques. By leveraging exploratory data analysis (EDA) and machine learning models, we aim to uncover key sales trends, external factor influences, and predict future sales to optimize business strategies.

---

## 🎯 Objectives
- ✅ Perform **EDA & Outlier Detection** to clean data.
- ✅ Analyze **Unemployment, CPI, Temperature** impact on sales.
- ✅ Identify **Top & Worst Performing Stores**.
- ✅ Detect **Seasonal Trends** in sales data.
- ✅ Use **SARIMA Model** for sales forecasting.
- ✅ Predict **sales for the next 52 weeks**.

---

## 📂 Dataset Information
- **📌 Columns:** Store, Date, Weekly_Sales, Holiday_Flag, Temperature, Fuel_Price, CPI, Unemployment
- **📌 Data Source:** Walmart historical sales records

---

## 🛠️ Methodology
### 🔹 1. Data Preprocessing
- 🛠️ Handled missing values & outliers.
- 📆 Converted dates & extracted features.
- 🚀 Performed feature engineering.

### 🔹 2. Exploratory Data Analysis (EDA)
- 📊 Visualized sales trends.
- 🔗 Analyzed sales correlations with CPI, Temperature, & Unemployment.
- 🎉 Identified seasonality effects (November peak due to holiday sales).

### 🔹 3. Time Series Forecasting Model
🚀 **Implemented SARIMA Model**:
- 📏 Model Order: (0,1,0) Seasonal Order: (0,1,0,52)
- 🔮 Forecasted **next 52 weeks of sales**
- ⚖️ Evaluated model using **Mean Squared Error (MSE)**

---

## 📈 Results & Insights
✔️ Sales peak in **November due to holiday shopping**.
✔️ Negative correlation between **temperature & sales**.
✔️ **Top-performing stores** contribute ~4.31% to total sales.
✔️ **Worst-performing stores** contribute ~0.69%.
✔️ SARIMA effectively predicts sales trends.

---

## 🏁 Conclusion
This project successfully forecasts sales using time series analysis. The insights help Walmart optimize inventory, marketing, and demand planning strategies. Further tuning can improve model accuracy.

---

## 📦 Dependencies
📌 Python Libraries Used:
- 🐍 Pandas, NumPy, Matplotlib, Seaborn
- 📊 Statsmodels, Scikit-learn
- ⏳ SARIMA for time series forecasting

---

## 🚀 How to Run the Project
1️⃣ Install dependencies: `pip install -r requirements.txt`
2️⃣ Run `timeseriescspro.py` to execute forecasting.
3️⃣ Check generated plots and results.

 

