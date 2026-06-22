# Advanced E-Commerce Analytics Pipeline (Python ➔ SQL ➔ Excel)

## Project Objective
This repository showcases an end-to-end data analytics and business intelligence pipeline utilizing a 20,000-row transactional e-commerce dataset. The project demonstrates a production-grade enterprise workflow: leveraging Python for data generation and programmatic styling, SQL for relational database modeling, and Excel for stakeholder-facing executive reporting.

## Project Architecture & Data Flow
The project functions as a unified pipeline where data streams sequentially across tools:

[ Raw Transaction Engine ] 
            │
            ▼
[ Python Data Pipeline ] ────► Synthesizes 20k rows & executes data cleaning
            │            ────► Performs mathematical RFM behavior scoring
            │
            ▼ (DataFrame Ingestion)
[ Relational SQLite DB ] ────► Houses data in a centralized 'sales' table
            │            ────► Runs complex groupings, aggregates, & CTEs
            │
            ▼ (Programmatic ETL Extraction)
[ Openpyxl Sheet Automation ] ──► Dynamically injects KPIs & Matplotlib charts
                          ──► Generates 'ecommerce_data_dashboard.xlsx'

## Strategic Business Insights Uncovered
* **High-Value Customer Retention:** Our behavioral RFM model successfully isolated a high-performing **Champions (VIP)** segment. Conversely, it flagged an **At-Risk** group of historically high-spending users who haven't purchased recently, signaling an immediate need for automated win-back email campaigns.
* **Product Line Optimization:** The **Electronics** vertical dominates total store revenue, driven heavily by high-ticket items like Laptops and Smartwatches.
* **Payment Stream Efficiency:** Credit Cards represent the primary checkout channel (~40% of orders), highlighting an opportunity to offer micro-incentives for alternative low-fee channels like UPI.

## Technical Milestones Completed
1. **Advanced Analytics Modeling:** Conducted a behavioral customer segmentation framework using Recency, Frequency, and Monetary (RFM) quintile scoring models.
2. **Relational Database Engineering:** Migrated flat-file frames into a live SQLite instance; engineered modular Common Table Expressions (CTEs) and statistical `NTILE()` window ranking operations directly in SQL code.
3. **Programmatic BI Automation:** Wrote an automation script using `openpyxl` to build an executive-ready spreadsheet completely via code—removing the need for manual cell formatting.

## Core Toolkit
* **Languages:** Python (v3), SQL (SQLite dialect)
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, SQLite3, Openpyxl
* **Environments:** Google Colab, Microsoft Excel

## How to Review This Project
1. Open the `ecommerce_sales_pipeline.ipynb` file above to view the documented code execution, database queries, and analytical visual plots.
2. Download `ecommerce_data_dashboard.xlsx` to interact with the finalized corporate financial dashboard and automated layouts directly in Microsoft Excel.

