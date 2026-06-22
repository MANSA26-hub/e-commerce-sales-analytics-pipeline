# e-commerce-sales-analysis-python
An end-to-end e-commerce data analytics project using Python to track retail KPIs, map monthly sales trends, and build an advanced RFM customer segmentation model.
# Advanced E-Commerce Sales Performance & Customer Segmentation

## Project Objective
This project analyzes a dataset containing 20,000 retail transactions to uncover consumer buying behavior, optimize inventory categories, track monthly revenue trends, and identify top-performing products. Additionally, it implements an advanced RFM (Recency, Frequency, Monetary) framework to segment the customer base for targeted marketing.

## Tech Stack
* **Language:** Python 3
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
* **Environment:** Google Colab / Jupyter Notebooks
* ## Interactive Excel Dashboard

In addition to the Python-based analysis, an interactive Excel dashboard was developed to provide a visual summary of key business metrics and enable easy exploration of sales performance.

### Dashboard Features

* KPI cards displaying Total Revenue, Total Orders, Average Order Value (AOV), and Units Sold.
* Interactive slicers for filtering insights by category, payment method, and time period.
* Monthly sales trend visualizations to monitor business growth and seasonality.
* Category-wise performance analysis to identify top-performing product segments.
* Product-level insights highlighting the highest revenue-generating items.
* User-friendly layout designed for quick decision-making and executive reporting.

### Dashboard File

* **e commerce data dash board.xlsx** – Interactive Excel dashboard containing business KPIs, charts, and slicers for dynamic analysis.
* **Dashboard Screenshots** – Visual previews of the dashboard included in this repository for easy review without downloading the Excel file.


## Key Analysis Steps Completed
1. **Data Inspection & Integrity:** Checked schema shapes, verified data types, and confirmed zero missing or duplicate values.
2. **Descriptive Aggregations:** Calculated fundamental business metrics including Total Revenue, Total Volume, and Average Order Value (AOV).
3. **Categorical & Timeline Segmentation:** Grouped performance data by specific verticals, consumer payment methods, and mapped a month-over-month sales timeline.
4. **Advanced Customer Segmentation (RFM Analysis):** Categorized customers into behavioral segments (Champions, Loyal, At Risk, Lost) using scoring metrics to optimize retention strategies.

## Strategic Insights & Recommendations
* **High-Value VIPs:** Our **Champions (VIP)** segment contains our most valuable users who buy frequently and spend the highest amounts. *Recommendation: Launch an exclusive early-access rewards program to maximize lifetime value.*
* **Retention Alert:** The **At Risk** segment consists of historically high-spending customers who have not made a purchase recently. *Recommendation: Deploy targeted email discounts and personalized product recommendations to incentivize their next purchase.*
* **Product Drivers:** The **Electronics** category drives the highest revenue, led specifically by sales of **Laptops** and **Smartphones**.

## How to Run the Project
1. Clone this repository: `git clone https://github.com`
2. Open the `ecommerce_sales_analysis.ipynb` file in Google Colab or Jupyter Notebook.
3. Run the cells sequentially to see the statistical analysis and visualizations.
4. Open e commerce data dash board.xlsx using Microsoft Excel (Excel 2016 or later recommended) to explore the interactive dashboard and filter insights using slicers.
