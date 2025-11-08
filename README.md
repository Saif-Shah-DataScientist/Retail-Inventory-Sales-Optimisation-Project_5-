# Retail Inventory and Sales Optimization

## Project Overview
This project analyzes retail sales and inventory data to identify patterns, inefficiencies, and optimization opportunities. The goal is to help retail teams balance stock levels, reduce overstock and stockout risks, and improve overall profitability through data-driven insights.

## Objectives
- Evaluate relationships between forecasted and actual sales  
- Identify overstocked and understocked SKUs  
- Assess the impact of promotions and discounts on sales and revenue  
- Examine seasonal and weather-related demand fluctuations  
- Provide recommendations for inventory optimization and forecasting improvement  

## Dataset
- File: retail_store_inventory.csv (or equivalent)  
- Source: Kaggle – Retail Store Inventory Forecasting Dataset  
- Key Columns: Product_ID, Category, Units_Sold, Forecasted_Sales, Revenue, Discount, Weather, Stock_Turnover, Lead_Time, Promotion, Season

## Tools and Libraries
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Jupyter Notebook  

## Steps Performed
1. Data loading and inspection  
2. Data cleaning and type correction  
3. Feature engineering (e.g., calculating sales gap and stock turnover rate)  
4. Exploratory Data Analysis (EDA)  
5. Visualization of revenue, forecast errors, stock patterns, and promotions  
6. Insights and recommendations for improving inventory efficiency  

## Key Insights
- **Forecast vs Reality:** Many SKUs show demand gaps where forecasts overshoot or undershoot real sales, leading to overstock or stockout issues.  
- **Category Importance:** Electronics and a few key categories generate the most revenue but have large forecast errors, needing closer manual review.  
- **Promotion Effect:** Promotions increase units sold but don’t always raise revenue due to discounts; ROI should be monitored by product.  
- **Seasonality and Weather:** Sales patterns shift with weather and seasons — for example, grocery sales rise on rainy days, while outdoor products spike in summer.  
- **Inventory Efficiency:** Low Stock_Turnover indicates overstock, while high Stock_Turnover with low inventory signals stockout risk.

## Business Recommendations
- Improve demand forecasting by incorporating seasonality and weather data.  
- Prioritize review of high-revenue categories with volatile demand.  
- Measure ROI of promotions to ensure discounts contribute to profit.  
- Use Stock_Turnover and Lead_Time to dynamically adjust reorder points.  
- Develop dashboards to track stock efficiency and forecast accuracy in real time.

## Requirements
To install the required libraries, run:
