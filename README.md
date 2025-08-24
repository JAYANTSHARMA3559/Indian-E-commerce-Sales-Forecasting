# Indian E-commerce Sales Forecasting

[cite_start]Forecasting Indian e-commerce sales (2019-2024) using Python (Prophet) and Power BI. [cite: 44] [cite_start]This project features an interactive dashboard with key performance indicators (KPIs) like Total Revenue, Year-over-Year (YoY) Growth, and Forecast Accuracy. [cite: 45]

### [View the Live Interactive Dashboard]([your_public_power_bi_link_here])

![Dashboard Preview]([link_to_your_dashboard_screenshot_here])

## Problem Statement

[cite_start]The Indian e-commerce market is rapidly expanding, with demand influenced by seasons, festivals, and consumer behavior. [cite: 47] [cite_start]To optimize supply chains and improve decision-making, businesses need reliable forecasting. [cite: 48] [cite_start]This project forecasts daily sales using Indian e-commerce data, combining a Python Prophet model with a Power BI dashboard for actionable insights. [cite: 49]

## Dataset

* [cite_start]**Source:** Public Indian Retail/E-commerce dataset (2019-2024) [cite: 51]
* [cite_start]**Size:** ~100,000 transactions [cite: 51]
* [cite_start]**Key Columns:** Order Date, Sales, Category, Region [cite: 52, 53, 55]

## Methods & Tools

### [cite_start]Data Preprocessing (Python - Pandas) [cite: 57]
* [cite_start]Cleaned missing and invalid values. [cite: 58]
* [cite_start]Converted the date column to the correct datetime format. [cite: 58]
* [cite_start]Aggregated individual transactions into total daily sales. [cite: 59]

### [cite_start]Forecasting Model (Python - Prophet) [cite: 60]
* [cite_start]Trained a Prophet model on the daily aggregated sales data. [cite: 61]
* [cite_start]Predicted future sales for 2024 and beyond. [cite: 62]
* [cite_start]Calculated Mean Absolute Percentage Error (MAPE) to measure model accuracy. [cite: 63]

### [cite_start]Dashboard (Power BI) [cite: 64]
* [cite_start]Designed an interactive dashboard with key KPIs: Total Revenue (₹), YoY Growth (%), and Forecast Accuracy (MAPE %). [cite: 66]
* [cite_start]Included an "Actual vs. Forecasted Sales" line chart with confidence intervals and a time-period slicer for custom analysis. [cite: 67]

## Key Insights

* [cite_start]The model achieved a high accuracy with a MAPE of less than 10%. [cite: 72]
* [cite_start]Indian e-commerce revenue showed a steady Year-over-Year growth of 3.49%. [cite: 69]
* [cite_start]The total revenue from 2019-2023 was ₹2.5bn. [cite: 70]
* [cite_start]The 2024 forecast indicates continued expansion with noticeable seasonal peaks. [cite: 71]

## How to Run the Project

1.  [cite_start]**Clone Repository** [cite: 102]
    ```bash
    git clone [https://github.com/](https://github.com/)[yourusername]/indian-sales-forecasting.git
    cd indian-sales-forecasting
    ```
2.  [cite_start]**Run Python Forecasting Notebook** [cite: 105]
    ```bash
    jupyter notebook forecasting.ipynb
    ```
3.  [cite_start]**Open Power BI Dashboard** [cite: 107]
    * [cite_start]File: `Indian_Ecommerce_Forecast.pbix` [cite: 108]
    * [cite_start]Explore the KPIs and interactive charts. [cite: 108]

## Future Improvements

* [cite_start]Add forecasting at a product or category level. [cite: 110]
* [cite_start]Deploy the dashboard online using the Power BI Service or Streamlit. [cite: 111]
* [cite_start]Incorporate external factors like holidays and macro-economic trends. [cite: 112]

## Author

* [cite_start]**Jayant Sharma** [cite: 114]
* Data Analytics Enthusiast | [cite_start]VIT Vellore [cite: 115]
* [cite_start][LinkedIn Profile](https://www.linkedin.com/in/jayant-sharma-b1a684267/) [cite: 116]
* [cite_start]jayant.sharma072004@gmail.com [cite: 117]
