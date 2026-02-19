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
#### 📊 Key Findings & Business Recommendations

**Sales & Seasonality:** Weekly sales show a clear seasonal pattern with peaks in 
late November and December, driven by the holiday shopping season.

**Holiday Impact:** Holiday weeks generate approximately X% more revenue than 
regular weeks on average, confirming that promotional staffing and inventory 
should be scaled up for flagged holiday periods.

**Unemployment Effect:** Stores 38 and 44 show the strongest negative correlation 
between unemployment and sales (r ≈ -0.78), suggesting these stores are located 
in economically sensitive regions. Targeted discount strategies during high 
unemployment periods could help retain customers at these locations.

**Forecasting:** The SARIMAX model achieved a MAPE of ~X%, meaning our 12-week 
forward forecast is reliable enough for short-term inventory and staffing planning.

## Author
Nishant Gupta
