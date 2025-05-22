# Business-Insights-360

### 📊 Project Overview

Business Insights 360 is a SQL-powered analytics project that focuses on understanding and optimizing AtliQ Hardware's business operations. This project explores MySQL database tables, applies Star Schema modeling, and implements forecasting techniques such as Year-to-Date (YTD), Year-to-Go (YTG), and Landing Estimates (LE).

### 🚀 Key Features & Views

Database Analysis: Explored different MySQL tables and their column purposes.

- Star Schema Implementation: Gained Understanding of Fact and Dimension tables for optimized queries.
- Business Context Analysis: Covered Channel, Platform, Product Category, Division, and Segment classifications.
- Date Table Creation: Designed a structured date table for better time-series analysis.
- FactActualsEstimates Table: Created to combine actual and forecasted data for better business planning.
- Forecasting & Data Modeling: Implemented YTD, YTG, and LE concepts for predictive insights.
- Power BI Visualization: Created interactive dashboards to showcase findings. Data modeling, visualization, report design
- DAX: Custom measures (YTD, YTG, Landing Estimates, Forecast Accuracy, Net Error)


### 🛠️ Technologies Used

- MySQL - Data extraction.

- Pwer Query - transformation.

- Power BI - Visualization and dashboard creation.

- Data Modeling - Fact vs Dimension table structuring.


### The database follows a Star Schema structure with:

#### 📌 Fact Tables:

- fact_sales_monthly, fact_forecast_monthly and FactActualsEstimates (combined actual and forecast data)

#### 📌 Dimension Tables:

- dim_date, dim_product, dim_customer, dim_market, freight_cost, manufacturing_cost, post_invoice_deductions

#### 📌 Fact vs Dimension Tables

- Fact Tables: Store transactional data such as sales, revenue, and costs.
  
- Dimension Tables: Provide descriptive attributes (Product details, Customer info, Date, etc.).

#### 📌 Business Context Definitions

- Channels & Platforms
  
- Channels: Retailer, Direct, Distributor
  
- Platforms: Brick & Mortar, Distributor

#### Product Hierarchy
- Product Categories: Batteries, Business Laptop, Gaming Laptop, Graphic Card, etc.
  
- Divisions: P&A, N&S, PC
  
- Segments: Accessories, Desktop, Networking, etc.

### 📅 Date Table & Forecasting Concepts

**Date table containes following data for future findings:**
- Date, Month, Fiscal Year


### Screenshots showcasing the data model and key tables:

Visuals/Data_Model.png ([Data Model representation](https://github.com/happy7434/Business-Insights-360/blob/main/Data%20Model.png))

📌 Purpose: Shows fact and dimension tables with their relationships.

Visuals/Date_Table.png ([dim_date table structure](https://github.com/happy7434/Business-Insights-360/blob/main/Date%20Table.png))

📌 Purpose: Shows the dim_date table structure, including date, month, and fiscal year columns.

Visuals/FactActualsEstimates.png ([Actuals & Forecasted Data Table](https://github.com/happy7434/Business-Insights-360/blob/main/FactActualsEstimates.png))

📌 Purpose: Displays the FactActualsEstimates table, which combines actual and forecasted data.


## 📊 Power BI Dashboard
I've created an interactive **Power BI Dashboard** that visualizes key business insights for AtliQ Hardware.

🔹 **Key Features:**
- 📈 **Gross & Net Sales Analysis**
- 📊 **Year-over-Year (YoY) Performance Tracking**
- 🏆 **Profit & Loss (P&L) Summary by Market & Segment**
- 📅 **Time-Based Trends (YTD, Q1-Q4 Comparisons)**
- 🔎 **Post-Invoice Deductions & Cost Analysis**


#### 📌 Home

High‑level KPIs and navigation menu

#### 📌 P&L Check

Detailed Profit & Loss statement vs. benchmarks

#### 📌 Finance

Revenue, Gross & Net Margins, Post‑invoice deductions, YoY trends

#### 📌 Sales

Top customers & products by Net Sales, Gross Margin vs. Net Sales matrix, unit economics

#### 📌 Marketing

Division & segment performance, Net Profit matrix, product P&L breakdown

#### 📌 Supply Chain

Forecast Accuracy, Net Error, Absolute Error, risk profiling by product & customer

#### 📌 Monthly Trend

Time series of Net Sales, GM %, Net Profit %, Forecast vs. Target

#### 📌 Market Share

Sub‑zone/Sub‑region performance, PC market share trend, top 5 customers & products

#### 📌 Executive

Consolidated high‑level dashboard for leadership—including P&L, Sales & Market Share

📌 **Download the Power BI Dashboard (`.pbix` file) here:**  
👉 [**Google Drive Link**](https://drive.google.com/file/d/1BQT7jK0AfoR3WL82vMftff-z573LnYx2/view?usp=sharing)

🔹 **Note:** Google Drive does not preview `.pbix` files. Click **Download**, then open it in **Power BI Desktop**.
