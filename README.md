# 📊 FinTech Payment & Customer Analytics Platform

## 📌 Project Overview

This project is an end-to-end FinTech analytics platform built using **Python, MySQL, SQL, and Power BI**.

The solution was designed to simulate a real-world business intelligence workflow used in financial and payment analytics environments.

The project covers:

- data cleaning and preprocessing using Python
- dimensional data warehouse modeling
- star schema implementation
- SQL analytics and reporting
- Power BI dashboard development
- KPI reporting and business insight generation

The platform analyzes customer transactions, payment channels, regional performance, product categories, and customer behavior to support business decision-making.

---

# 🛠 Technologies Used

- Python
- Pandas
- MySQL
- SQLAlchemy
- Jupyter Notebook
- Power BI
- DAX
- Star Schema Data Modeling

---

# 📂 Project Workflow

Raw CSV Files → Python Data Processing → MySQL Data Warehouse → SQL Analytics → Power BI Dashboard Reporting

---

# 🗄 Data Warehouse Architecture

The project follows a dimensional modeling approach using a **star schema** architecture.

## Fact Table
- `fact_transactions`

## Dimension Tables
- `dim_customers`
- `dim_customers_usa`
- `dim_accounts`
- `dim_products`
- `dim_products_categories`
- `dim_products_subcategories`
- `DateTable`

Primary keys and foreign key relationships were implemented to improve:

- data integrity
- relationship consistency
- query performance
- Power BI relationship modeling

---

# 📊 Dashboard Features

The interactive Power BI dashboard includes:

- Total Transaction KPI Cards
- Transaction Value Analysis
- Average Transaction Metrics
- Regional Transaction Analysis
- Product Category Performance
- Payment Channel Analysis
- Interactive Slicers and Filters
- Yearly Transaction Trend Analysis
- Customer Transaction Analysis

---

# 🧠 Business Insights

The project generated several business insights, including:

- Identification of top-performing regions by transaction value
- Analysis of customer transaction behavior across regions
- Product category performance comparison
- Transaction channel performance analysis
- Year-over-year transaction trend analysis
- Executive-level KPI monitoring

---

# 📸 Dashboard Preview

![Dashboard Overview](screenshots/dashboard/fintech_analytics_dashboard_overview.png)

---

# 📸 Data Modeling Screenshots

## Star Schema Relationship Model
![Star Schema](screenshots/modeling/star_schema_relationship_model.png)

## Primary & Foreign Keys
![Primary Foreign Keys](screenshots/modeling/primary_foreign_keys.png)

## Verify Foreign Keys
![Verify Foreign Keys](screenshots/modeling/verify_foreign_keys.png)

## Power BI Relationship Model
![Relationship Model](screenshots/modeling/powerbi_relationship_model.png)

---

# 📸 Power BI & DAX Screenshots

## Date Table DAX Creation
![Date Table DAX](screenshots/powerbi/date_table_dax_creation.png)

## Date Table Columns
![Date Table Columns](screenshots/powerbi/date_table_columns.png)

## MySQL to Power BI Import
![MySQL Import](screenshots/powerbi/mysql_powerbi_data_import.png)

---

# 📸 SQL Analytics Screenshots

## Yearly Transaction Trend Analysis
![Yearly Analysis](screenshots/sql_analysis/yearly_transaction_trend_analysis.png)

## Regional Transaction Analysis
![Regional Analysis](screenshots/sql_analysis/regional_transaction_analysis.png)

## Top Customers Analysis
![Top Customers](screenshots/sql_analysis/top_customers_analysis.png)

## Power BI Reporting View SQL
![Reporting View](screenshots/sql_analysis/powerbi_reporting_view_sql.png)

---

# 📂 Repository Structure

```bash
fintech-payment-customer-analytics-platform
│
├── data_raw
├── screenshots
│   ├── dashboard
│   ├── modeling
│   ├── powerbi
│   └── sql_analysis
│
├── demo-video
├── fintech_analytics.pbix
├── fintech_analytics_sql_project.ipynb
└── README.md
🚀 Key Learning Outcomes
Through this project, I strengthened my skills in:
dimensional data modeling
SQL analytics
Power BI dashboard development
DAX calculations
business KPI reporting
data warehouse design
ETL-style workflows
end-to-end analytics project development
📌 Future Improvements
Add customer churn prediction
Implement fraud detection analysis
Add advanced DAX time intelligence
Build forecasting models
Deploy dashboard to Power BI Service
👨‍💻 Author
Dinesh Kumar Muthusamy
Data Analyst | BI Analyst
SQL | Power BI | Python | MySQL
Business Intelligence & Analytics Projects
