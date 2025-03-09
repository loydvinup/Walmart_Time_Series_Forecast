# 🎯 Walmart Sales Forecasting

## 📌 Project Overview
This project focuses on analyzing Walmart's weekly sales data to identify key trends and forecast future sales using time series forecasting and machine learning models. The dataset contains sales information from multiple Walmart outlets along with economic indicators such as unemployment rate, consumer price index (CPI), fuel prices, temperature, and holiday markers. 

---

## 🎯 Objectives
✅ **Exploratory Data Analysis (EDA)**
   - 📊 Identify relationships between sales and economic factors.
   - 📈 Detect seasonal sales trends and their causes.
   - 🌡️ Examine the impact of unemployment, temperature, and CPI on sales.
   - 🏆 Rank stores based on their performance.

✅ **Data Preprocessing**
   - 🔍 Handle missing values and outliers.
   - 🏗️ Perform feature engineering.
   - 🔢 Normalize and encode categorical variables.

✅ **Sales Forecasting**
   - 🔮 Build predictive models to forecast sales for the next 12 weeks.
   - ⚖️ Compare different machine learning models.

---

## 📂 Dataset Information
- **📌 Total Rows:** 6435
- **📌 Columns:** Store, Date, Weekly_Sales, Holiday_Flag, Temperature, Fuel_Price, CPI, Unemployment
- **📌 Data Source:** Walmart historical sales records

---

## 🛠️ Methodology
### 🔹 1. Data Cleaning & Preprocessing
- 🛠️ Handled missing values in CPI and Unemployment.
- 🔄 Merged different datasets (stores, features, and sales data).
- 📆 Converted date values to datetime format and extracted year, month, and week.
- 🚨 Detected and removed outliers using Z-score.

### 🔹 2. Exploratory Data Analysis (EDA)
- 📊 Monthly and weekly sales trends visualization.
- 🔗 Correlation analysis between sales and external factors.
- 🎉 Impact analysis of holidays on sales.

### 🔹 3. Machine Learning Models for Forecasting
🚀 **Implemented Models:**
- 📏 Linear Regression
- 🌲 Random Forest Regressor
- 🤝 K-Nearest Neighbors (KNN) Regressor
- ⚡ XGBoost Regressor
- 🤖 Deep Neural Network (DNN)

### 🔹 4. Model Evaluation
✅ Models were evaluated using metrics like:
  - 📉 Mean Absolute Error (MAE)
  - 🧮 Mean Squared Error (MSE)
  - 📏 Root Mean Squared Error (RMSE)
  - 📊 R-squared score (R²)
- 📊 Model accuracy comparison through visualization.

---

## 📈 Results & Insights
✔️ Sales show clear seasonal trends, with peaks during holiday seasons.
✔️ Unemployment and CPI significantly impact sales in certain stores.
✔️ XGBoost and Random Forest performed the best for sales forecasting.
✔️ Deep Learning models also performed well but required more training time.

---

## 🏁 Conclusion
This project successfully explored Walmart's sales trends and built predictive models for future sales. The insights derived can help optimize inventory, improve store performance, and refine business strategies.

---

## 📦 Dependencies
📌 Python Libraries Used:
- 🐍 Pandas, NumPy, Matplotlib, Seaborn
- 🔢 Scikit-learn, Statsmodels, XGBoost
- 🤖 TensorFlow/Keras

---

## 🚀 How to Run the Project
1️⃣ Install the required dependencies: `pip install -r requirements.txt`
2️⃣ Run `walmart_time_series_forecast.py` to execute the complete workflow.
3️⃣ Check the `plots/` folder for visualizations and the `models/` folder for trained models.

---

## 📞 Contact
For any queries, reach out to **📧 support@intellipaat.com** or call **📞 +91-7022374614** (India) / **📞 1-800-216-8930** (US Toll-Free).

