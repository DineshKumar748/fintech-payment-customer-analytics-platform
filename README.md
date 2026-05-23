# 📊 End-to-End FinTech Payment & Customer Analytics Platform

## 📌 Overview

This project is an end-to-end FinTech analytics solution built using Python, MySQL, SQL, and Power BI.

The project demonstrates a complete analytics workflow from raw transactional datasets → Python ETL processing → MySQL data warehouse modeling → SQL analytics → Power BI dashboard reporting.

### 🔹 Key Focus Areas
- Payment transaction analytics
- Customer behavior analysis
- KPI reporting
- Regional performance tracking
- Product category analysis
- Executive dashboard reporting

---

# 📷 Dashboard Preview

![Dashboard](screenshots/dashboard/fintech_analytics_dashboard_overview.png)

The Power BI dashboard provides interactive KPI monitoring across customers, products, regions, and transaction channels.

---

# 🚀 Key Features

- Python ETL workflows using Pandas
- MySQL dimensional warehouse design
- Star schema data modeling
- SQL reporting views
- DAX measures & DateTable
- KPI reporting dashboards
- Interactive slicers & filters
- Regional transaction analysis
- Customer analytics
- Time intelligence reporting

---

# 🛠 Tech Stack

- Python
- Pandas
- MySQL
- SQL
- SQLAlchemy
- Power BI
- DAX
- Jupyter Notebook

---

# 🗂 Project Workflow

```text
Raw CSV Files
      ↓
Python Data Processing
      ↓
MySQL Data Warehouse
      ↓
Fact & Dimension Tables
      ↓
SQL Analytics & Reporting Views
      ↓
Power BI Dashboard
```

---

# 🏗 Star Schema Data Modeling

![Star Schema](screenshots/modeling/star_schema_relationship_model.png)

The warehouse model was designed using:
- Fact tables
- Dimension tables
- Primary & foreign key relationships
- Optimized reporting structure

### Fact Table
- fact_transactions

### Dimension Tables
- dim_customers
- dim_accounts
- dim_products
- dim_products_categories
- dim_products_subcategories
- DateTable

---

# 🔑 Primary & Foreign Keys

## Primary Key Implementation

![Primary Keys](screenshots/modeling/primary_foreign_keys.png)

## Foreign Key Verification

![Foreign Keys](screenshots/modeling/verify_foreign_keys.png)

Relationships were implemented to improve:
- Data integrity
- Query performance
- Reporting consistency
- Power BI modeling

---

# 📅 DateTable & DAX

## DateTable DAX Creation

![DateTable DAX](screenshots/powerbi/date_table_dax_creation.png)

## DateTable Columns

![DateTable Columns](screenshots/powerbi/date_table_columns.png)

### Time Intelligence Features
- Year
- Quarter
- Month
- Dynamic filtering
- Trend analysis

---

# 🧮 SQL Analytics

The project includes SQL analysis for:
- Regional performance
- Transaction trends
- Customer analysis
- Product category analysis
- KPI aggregation
- Reporting view creation

---

# 🌍 Regional Transaction Analysis

![Regional Analysis](screenshots/sql_analysis/regional_transaction_analysis.png)

### 🔍 Insight
Colorado generated the highest transaction value, exceeding 1 million in total transaction amount.

---

# 👥 Top Customers Analysis

![Top Customers](screenshots/sql_analysis/top_customers_analysis.png)

### 🔍 Insight
High-value customers were identified across multiple regions to support segmentation and executive reporting.

---

# 📈 Yearly Transaction Trends

![Yearly Trends](screenshots/sql_analysis/yearly_transaction_trend_analysis.png)

### 🔍 Insight
Transaction activity showed stable yearly growth between 2020 and 2025.

---

# ⚡ SQL Reporting View

![SQL Reporting View](screenshots/sql_analysis/powerbi_reporting_view_sql.png)

A SQL reporting view (`vw_transaction_summary`) was created for:
- Faster Power BI integration
- KPI reporting
- Simplified analytics queries
- Better dashboard performance

---

# 🔄 MySQL to Power BI Integration

![Power BI Import](screenshots/powerbi/mysql_powerbi_data_import.png)

### Integration Workflow

```text
CSV Files → Python → MySQL → SQL Views → Power BI
```

---

# 📊 Dashboard KPI Metrics

The dashboard tracks:
- Total Transactions
- Total Transaction Value
- Average Transaction Amount
- Regional Revenue
- Product Performance
- Transaction Trends

---

# 🎥 Dashboard Demo

```text
demo-video/fintech_dashboard_demo.mp4
```

---

# 📂 Repository Structure

```text
fintech-payment-customer-analytics-platform
│
├── data_raw/
├── screenshots/
│   ├── dashboard/
│   ├── modeling/
│   ├── powerbi/
│   └── sql_analysis/
│
├── demo-video/
├── fintech_analytics.pbix
├── fintech_analytics_sql_project.ipynb
└── README.md
```

---

# 📚 Learning Outcomes

This project strengthened my ability to:
- Build end-to-end analytics solutions
- Design star schema warehouses
- Develop SQL analytics queries
- Create Power BI dashboards
- Implement DAX measures
- Perform KPI reporting
- Build reporting views
- Deliver business-focused analytics

---

# 🚀 Future Improvements

Planned future enhancements:
- Customer churn prediction
- Fraud detection analytics
- Forecasting models
- Advanced DAX calculations
- Additional KPI dashboards

---

# 👨‍💻 Author

## Dinesh Kumar Muthusamy

Data Analyst | BI Analyst | SQL | Power BI | Python | Data Modeling

### Connect With Me

- GitHub: https://github.com/DineshKumar748
- LinkedIn: https://linkedin.com/in/dinesh-kumar-muthusamy-856399333/
