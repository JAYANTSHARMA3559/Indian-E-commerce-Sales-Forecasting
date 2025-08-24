Indian E-commerce Sales Forecasting

Forecasting Indian e-commerce sales (2019–2024) using Python (Prophet) and Power BI. Features interactive dashboards with KPIs: Total Revenue, YoY Growth, and Forecast Accuracy.

Problem Statement
The Indian e-commerce market has been rapidly expanding, with fluctuating demand influenced by seasons, festivals, and consumer behavior. Businesses need reliable forecasting to plan inventory, optimize supply chains, and improve decision-making.
This project focuses on forecasting daily and yearly sales (2019–2024) using Indian e-commerce retail data, combining Python (Prophet model) with Power BI dashboards for actionable insights.
________________________________________
Dataset
Source: Public Indian Retail/E-commerce dataset (2019–2024)
Size: ~100,000 transactions across categories and regions
Key Columns:
•	Order Date → Date of transaction
•	Sales → Revenue from order
•	Category, Region (if applicable)
________________________________________
Methods & Tools
Data Preprocessing (Python - Pandas)
•	Cleaned missing/invalid values
•	Converted date column to datetime
•	Aggregated daily sales
Forecasting Model (Python - Prophet)
•	Trained model on daily sales
•	Predicted future sales (2024 and beyond)
•	Calculated MAPE (Mean Absolute Percentage Error) for model accuracy
Dashboard (Power BI)
Designed an interactive dashboard with:
•	KPIs: Total Revenue (₹), YoY Growth (%), Forecast Accuracy (MAPE %)
•	Charts: Actual vs Forecasted Sales (line chart with confidence intervals), Yearly comparison of sales and forecasts, Time-period slicer for custom analysis
________________________________________
Key Insights
•	Indian e-commerce revenue showed steady YoY growth (3.49%).
•	Total Revenue across 2019–2023 was ₹2.5bn.
•	Forecasted 2024 sales indicate continued expansion, with seasonal peaks.
•	Forecast model achieved <10% MAPE, ensuring high accuracy.
________________________________________
Dashboard Preview
 
________________________________________
How to Run the Project
1.	Clone Repository
git clone https://github.com/yourusername/indian-sales-forecasting.git
cd indian-sales-forecasting
2.	Run Python Forecasting Notebook
jupyter notebook forecasting.ipynb
3.	Open Power BI Dashboard
File: Indian_Ecommerce_Forecast.pbix
Explore KPIs and interactive charts
________________________________________
Future Improvements
•	Add product-level or category-level forecasting
•	Deploy interactive dashboard online using Power BI Service / Streamlit
•	Incorporate external factors (festivals, holidays, macro trends)
________________________________________
Author
Jayant Sharma
Data Analytics Enthusiast | VIT Vellore
LinkedIn: https://www.linkedin.com/in/jayant-sharma-b1a684267/
Email: jayant.sharma072004@gmail.com


