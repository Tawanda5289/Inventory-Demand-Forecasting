#  Inventory Demand Forecasting and Analytics Dashboard

##  Overview
This project demonstrates a data-driven approach to forecasting **retail inventory demand** using historical sales data. It combines **Prophet time-series modelling** in Python with a **Power BI dashboard** to visualise actual vs. forecasted sales and prediction intervals. The objective is to support better inventory planning, supply chain optimisation, and fulfilment efficiency.

  Select Stocks and Set Initial Capital: <br/>
  <img src="https://imgur.com/a/KPNbsIJ.png" height="80%" width="80%" alt="Future sales forecast" />
  <br /> <br />

  Analyze Portfolio Performance: <br/>
  <img src="https://imgur.com/a/TOGtNqv.png" height="80%" width="80%" alt="Store 3 weekly sales" />
  <br /> <br />

  Simulate Portfolio Changes Over Time: <br/>
  <img src="https://imgur.com/a/KY9vOL8.png" height="80%" width="80%" alt="Power Bi Results" />
</p>

---

##  Objectives
- Forecast weekly sales for a specific store and department using Prophet
- Visualise actual vs. forecasted values to evaluate model performance
- Display confidence intervals to highlight forecast uncertainty
- Generate business insights to support inventory and operations management

---

##  Tools & Technologies

| Tool        | Purpose                                 |
|-------------|------------------------------------------|
| **Python**  | Data processing and model development    |
| **Prophet** (`cmdstanpy`) | Time-series forecasting      |
| **Pandas**  | Data wrangling                           |
| **Power BI**| Visualisation and dashboard development  |
| **Jupyter Notebook** | Model development interface     |
| **DAX**     | Power BI measures (e.g., forecast error) |

---
##  Project Structure

Inventory-Forecast-Project/
│
├── data/
│ ├── train.csv # Raw historical sales
│ ├── forecast_output.csv # Prophet forecast results
│ └── actual_vs_forecast.csv # Merged actual + forecast
│
├── notebooks/
│ └── prophet_forecast.ipynb # Python forecasting model
│
├── dashboard/
│ └── ForecastDashboard.pbix # Power BI report file
│
├── report/
│ └── README.md # This file

---
##  Key Features
-  **Forecast vs. Actual Sales** with dual Y-axes comparison
-  **Forecast Confidence Bands** visualised using shaded areas
-  **Forecast Error Analysis** using custom DAX measures
-  Interactive slicing by time periods
-  Business-focused insights to support supply chain and inventory decisions

---

##  Results
- Prophet accurately captured seasonality and trend
- Confidence bands visualised to reflect model uncertainty
- A clear Power BI dashboard was built for stakeholder insights

---

##  How to Run

1. Clone or download this repository
2. Open and run `prophet_forecast.ipynb` in Jupyter to generate `forecast_output.csv`
3. Load `actual_vs_forecast.csv` into Power BI using the `.pbix` file
4. Explore interactive visuals and apply filters

---

##  Insights & Use Cases
- Supports inventory managers in determining **reorder points**
- Useful in **warehouse planning**, **retail forecasting**, and **demand analysis**
- Adaptable to multi-SKU, multi-store setups or broader logistics scenarios

---

##  Acknowledgements
- Dataset: Walmart Store Sales Forecasting (Kaggle)
- Forecasting model: [`prophet`](https://pypi.org/project/prophet/) (Stan-based, Python library)

---

> 🔗 View the full project: [Inventory-Demand-Forecasting](https://github.com/Tawanda5289/
