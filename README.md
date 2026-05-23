📊 End-to-End FinTech Payment & Customer Analytics Platform
📌 Project Overview
This project is an end-to-end FinTech analytics solution built using Python, MySQL, SQL, and Power BI.
The project demonstrates the complete analytics workflow starting from raw CSV datasets, followed by data processing in Python, dimensional data modeling in MySQL, SQL-based business analysis, and interactive dashboard development in Power BI.
A structured star schema warehouse model was designed using fact and dimension tables to support scalable analytics and reporting.
The project focuses on transaction analytics, customer insights, regional performance analysis, product category analysis, KPI reporting, and dashboard storytelling commonly used in financial and business intelligence environments.
🛠 Tools & Technologies Used
Python
Pandas
MySQL
SQLAlchemy
SQL
Power BI
DAX
Jupyter Notebook
Star Schema Data Modeling
🗂 Project Architecture
Raw CSV Files
        ↓
Python Data Processing (Pandas)
        ↓
MySQL Data Warehouse
        ↓
Fact & Dimension Modeling
        ↓
SQL Analytics & Reporting Views
        ↓
Power BI Dashboard & DAX Measures
📂 Repository Structure
fintech-payment-customer-analytics-platform
│
├── data_raw/
│   ├── DimAccount.csv
│   ├── DimCustomer.csv
│   ├── DimCustomerUSA.csv
│   ├── DimProductCategory.csv
│   ├── DimProductSubCategory.csv
│   └── FactTransaction.csv
│
├── screenshots/
│   ├── fintech_analytics_dashboard_overview.png
│   ├── star_schema_relationship_model.png
│   ├── date_table_dax_creation.png
│   ├── date_table_columns.png
│   ├── date_table_relationship_model.png
│   ├── primary_foreign_keys.png
│   ├── verify_foreign_keys.png
│   ├── powerbi_reporting_view_sql.png
│   ├── regional_transaction_analysis.png
│   ├── yearly_transaction_trend_analysis.png
│   ├── top_customers_analysis.png
│   └── mysql_powerbi_data_import.png
│
├── demo-video/
│   └── fintech_dashboard_demo.mp4
│
├── fintech_analytics.pbix
├── fintech_analytics_sql_project.ipynb
└── README.md
📷 Dashboard Overview

The Power BI dashboard provides interactive KPI monitoring and transaction analytics across customers, products, regions, and transaction channels.
🧠 Business Problems Solved
This project analyzes:
Transaction performance
Customer behavior
Regional transaction trends
Product category performance
Transaction channel analysis
KPI monitoring
Revenue concentration analysis
Executive reporting insights
🏗 Data Warehouse Modeling
A dimensional warehouse model was created using:
Fact Table
fact_transactions
Dimension Tables
dim_customers
dim_accounts
dim_products
dim_products_categories
dim_products_subcategories
DateTable
The warehouse follows a Star Schema structure for optimized analytics and Power BI reporting.
🔗 Star Schema Relationship Model

Key Features
One-to-many relationships
Structured dimensional warehouse
Optimized reporting model
Simplified BI analysis
Power BI relationship integration
🔑 Primary Keys & Foreign Keys
Primary and foreign key relationships were implemented to improve:
Data integrity
Relationship consistency
Query performance
Power BI modeling
Primary Key Implementation

Foreign Key Verification

📅 Date Dimension Table (DAX)
A custom DateTable was created in Power BI using DAX for time intelligence analysis.
DateTable DAX Creation

DateTable Columns

DateTable Relationship Model

Time Intelligence Features
Year
Quarter
Month
Month Number
Dynamic date filtering
Trend analysis support
🧮 SQL Analytics Performed
The project includes multiple SQL business analysis queries such as:
Regional transaction analysis
Product category performance
Customer transaction analysis
Transaction channel analysis
Yearly transaction trends
KPI aggregation
Reporting view creation
🌍 Regional Transaction Analysis

Key Insight
Colorado generated the highest transaction amount, exceeding 1 million in total transaction value.
This analysis supports:
Regional performance monitoring
Revenue concentration analysis
Geographic transaction insights
Executive KPI reporting
👥 Top Customers Analysis

Key Insight
Several high-value customers were identified across multiple regions, supporting customer segmentation and executive reporting.
This analysis can support:
VIP customer identification
Customer value segmentation
Revenue concentration analysis
Stakeholder reporting
📈 Yearly Transaction Trend Analysis

Key Insight
Transaction value showed gradual growth between 2020 and 2025 with stable yearly transaction activity.
This analysis supports:
Long-term KPI monitoring
Trend analysis
Revenue forecasting preparation
Executive reporting
⚡ SQL Reporting View for Power BI
A SQL reporting view (vw_transaction_summary) was created to simplify Power BI integration and KPI reporting.

Reporting View Benefits
Faster Power BI integration
Simplified reporting queries
KPI aggregation support
Better dashboard performance
🔄 MySQL to Power BI Integration
Data was imported directly from MySQL into Power BI using ODBC integration.

Integration Workflow
CSV Files → Python → MySQL → SQL Views → Power BI Dashboard
📊 Power BI Dashboard Features
The dashboard includes:
KPI Cards
Transaction Trends
Regional Analysis
Product Category Analysis
Interactive Slicers
Transaction Channel Insights
Dynamic Filtering
Map Visualizations
Time Intelligence Analysis
KPI Metrics
Total Transactions
Total Transaction Value
Average Transaction Amount
Regional Revenue
Product Category Performance
🎥 Dashboard Demo Video
A short interactive dashboard demo video is included in this repository.
demo-video/fintech_dashboard_demo.mp4
📚 Learning Outcomes
Through this project, I strengthened my ability to:
Build end-to-end analytics solutions
Design dimensional warehouse models
Create fact and dimension tables
Implement primary and foreign keys
Develop SQL analytics queries
Create reporting views for BI tools
Design Power BI dashboards
Build DAX measures and DateTables
Perform KPI and trend analysis
Create executive-level business reporting
🚀 Future Improvements
Future enhancements planned for this project:
Customer churn prediction
Financial forecasting
Advanced DAX calculations
Fraud detection analytics
Power BI performance optimization
Additional KPI dashboards
👨‍💻 Author
Dinesh Kumar Muthusamy
Data Analyst | BI Analyst | SQL | Power BI | Python | Data Modeling
Connect With Me
GitHub: DineshKumar748
LinkedIn: linkedin.com/in/dinesh-kumar-muthusamy-856399333/
