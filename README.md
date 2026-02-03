# Walmart Sales Forecasting & Inventory Optimization

## Project Overview
This project analyzes weekly sales data from Walmart stores to identify key factors affecting demand and forecast future sales.

## Dataset
- Rows: 6,435
- Features:
  - Store
  - Date
  - Weekly_Sales
  - Holiday_Flag
  - Temperature
  - Fuel_Price
  - CPI
  - Unemployment

## Objectives
- Analyze impact of unemployment, CPI, temperature on sales
- Identify seasonal trends
- Find top and worst performing stores
- Forecast next 12 weeks sales using predictive models

##Tools Used

Python, Pandas, NumPy, Matplotlib, Seaborn, Prophet, Scikit-learn,ARIMA

Steps Performed

Data cleaning (null values, date formatting, outliers)

Exploratory Data Analysis (seasonality, store trends)

Feature engineering (month, week, holiday flag)

Time series modeling using Prophet

Forecasting next 12 weeks

##Results

Forecast accuracy: ~87%

Detected strong seasonal sales patterns

High-performing vs low-performing stores identified

##Business Impact

Helps retail managers plan inventory, staffing, and promotions based on demand predictions.

## Key Insights
- Sales are affected by unemployment and CPI
- Holidays and seasonal patterns strongly impact demand
- Significant difference between best and worst performing stores

## Future Scope
- Deep learning forecasting
- Store-level optimization
- Real-time dashboard

## Author
Nishant Gupta
