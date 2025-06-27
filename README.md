# FUTURE_ML_01
# AI-POWERED SALES FORECASTING DASHBOARD

This project forecasts daily retail sales using historical data, Facebook Prophet for time series modeling, and Power BI for interactive dashboard visualization.

## 📂 Project Structure

- `Retail_Sales_EDA.ipynb`  
  Initial data exploration and statistical summary of the retail dataset.
  
- `Retail_Sales_Prophet_Forecast.ipynb`  
  Time series forecasting using the Prophet model with seasonal components and trend decomposition.

- `mock_kaggle.csv`  
  Original input dataset containing retail sales data.

- `sales_forecast.csv`  
  Forecasted results exported from Prophet, ready for visualization.

- `Retail_sales_Visualization.pbix`  
  Power BI dashboard showcasing forecast trends, peaks, bounds, and seasonal effects.

- `README.md`  
  This documentation file.

##  Tools Used

- **Python**: Pandas, Prophet, Matplotlib
- **Power BI**: Dashboard design and visualization
- **Jupyter Notebook**: Analysis and forecasting workflow

##  Dashboard Highlights

- Forecast trends with upper and lower bounds
- Clipped forecasts for realistic insights
- Seasonal effects (weekly, yearly)
- Slicers for interactive filtering (e.g., by time period)
- Decomposition Tree for contribution analysis

##  Goal

Help retailers anticipate sales trends and plan inventory, marketing, or staffing accordingly with forecast insights.
