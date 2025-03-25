
# 📦 Retail Demand Forecasting using Time Series Analysis

## 🧠 Overview

This project focuses on analyzing and forecasting product demand using historical transaction data from a UK-based online retail company. Leveraging time-series modeling, the goal is to predict **monthly demand** one month in advance — enabling better inventory planning, demand-driven stock replenishment, and operational efficiency.

---

## 📊 Dataset Information

- **Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Online+Retail)
- **Timeframe**: December 2010 – December 2011  
- **Total Records**: 541,909 transactions  
- **Main Features**:
  - `InvoiceNo`, `StockCode`, `Description`, `Quantity`, `InvoiceDate`, `UnitPrice`, `CustomerID`, `Country`

This rich dataset captures customer purchase behavior, product-level sales activity, and international trends, making it ideal for demand forecasting and behavioral analytics.

---

## 🔧 Project Workflow

### 1. 📈 Exploratory Data Analysis (EDA)
- Identified top-selling products, sales peaks, and customer trends
- Analyzed seasonal demand shifts and geographical distributions
- Visualized sales dynamics through time-series plots and bar charts

### 2. 🧹 Data Cleaning & Feature Engineering
- Removed duplicates and handled missing or inconsistent values
- Converted invoice timestamps into a usable datetime index
- Created monthly aggregation features and customer segments for analysis

### 3. 🔮 Forecasting Model Development
- Built and compared multiple time-series models including:
  - ARIMA
  - Facebook Prophet
  - Exponential Smoothing (ETS)
- Selected the most accurate model based on validation performance

### 4. 🧪 Model Validation
- Evaluated predictions using RMSE and MAE
- Tested the model's ability to accurately forecast one month ahead

---

## 📦 Outcome & Utility

The final forecasting model helps anticipate monthly product demand, reducing risks of understocking or overstocking. This approach supports:
- Smarter inventory management
- Improved customer satisfaction
- Strategic planning for high-demand periods
