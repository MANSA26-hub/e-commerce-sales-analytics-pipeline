# Corporate E-Commerce Analytics Ecosystem (Python ➔ SQL ➔ Excel ➔ Power BI)

## Project Objective
This repository showcases an end-to-end production-grade enterprise data intelligence pipeline utilizing a 20,000-row transactional e-commerce dataset. The ecosystem establishes a full-stack engineering workflow: leveraging Python for algorithmic synthesis, SQL for relational data modeling, Excel for static financial audits, and Power BI for interactive executive-level application reporting.

## Project Architecture & Core Data Flow
Data moves sequentially across tools to maximize storage performance and presentation layout:

[ Raw Transaction Engine ] 
            │
            ▼
[ Python Processing Engine ] ──► Synthesizes 20k rows & handles data cleaning
            │                ──► Calculates mathematical behavioral RFM scoring
            │
            ▼ (DataFrame Ingestion)
[ Relational SQLite DB ]     ──► Centralizes tables & optimizes structured frames
            │                ──► Executes complex groupings, aggregates, & SQL CTEs
            │
            ▼ (Programmatic Pipeline Export)
[ Openpyxl Sheet Automation ] ──► Generates 'ecommerce_data_dashboard.xlsx'
            │                 ──► Auto-injects KPI metrics & formatting layers
            │
            ▼ (Direct Data Layer Ingestion)
[ Power BI Desktop App ]      ──► Renders enterprise-ready dashboard applications
                              ──► Enables interactive timeline filtering

## Interactive Power BI Application Dashboard
Below is the live operational dashboard layout rendered from our processed pipeline data:

![Power BI Dashboard Layout](powerbi_dashboard_preview.png)

## Strategic Business Insights Uncovered
* **High-Value Customer Retention:** Our behavioral RFM model successfully isolated a high-performing **Champions (VIP)** segment. Conversely, it flagged an **At-Risk** group of historically high-spending users who haven't purchased recently, signaling an immediate need for automated win-back email campaigns.
* **Product Line Optimization:** The **Electronics** vertical dominates total store revenue, driven heavily by high-ticket items like Laptops and Smartwatches.
* **Payment Stream Efficiency:** Credit Cards represent the primary checkout channel (~40% of orders), highlighting an opportunity to offer micro-incentives for alternative low-fee channels like UPI.

## Tool Execution Matrix
* **Python (Data Engineering):** Automates data logic pipelines and packages backend frames using Pandas, NumPy, and Openpyxl.
* **SQL (Database Modeling):** Executes relational indexing schemas via SQLite using advanced Common Table Expressions (CTEs) and `NTILE()` window partitions.
* **Excel (Financial Delivery):** Outputs stylized workbook files with auto-aligned grid configurations for finance department ledger audits.
* **Power BI (Business Intelligence):** Builds dynamic data applications containing custom visual filters, card modules, and timeline seasonality plots.

## How to Review This Project
1. Open the `ecommerce_sales_pipeline.ipynb` file above to view the documented code execution and SQL query blocks.
2. Download `ecommerce_data_dashboard.xlsx` to review the automated spreadsheet deliverable layout directly in Excel.
3. Download and open `ecommerce_executive_dashboard.pbix` inside Power BI Desktop to interact with the live business filters.


