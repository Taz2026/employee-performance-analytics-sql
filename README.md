# employee-performance-analytics-sql

## 📌 Project Overview

This project designs a structured SQL database to track employee performance and link it to operational supply chain KPIs. The system enables leaders to evaluate employees using measurable metrics, generate appraisal-ready reports, and support transparent, data-driven promotion decisions.

By combining HR data with operational performance indicators, the database shows how analytics can align workforce performance with supply chain efficiency and business results.

## 🛠 Tools Used

* SQL – Database design, queries, and analytics
* PostgreSQL / MySQL / SQL Server – Relational database management
* DBMS Tools – Database creation and query execution
* GitHub – Version control and project documentation
* ER Diagram Tool (draw.io / Lucidchart) – Database schema visualization

## 🗂 Database Schema

The database is designed using third normal form (3NF) to ensure data integrity, reduce redundancy, and maintain efficient relationships between entities.

Key tables include:

* employees – Employee information and organizational structure
* departments – Business units within the supply chain organization
* roles – Job roles and experience levels
* performance_cycles – Evaluation periods for performance reviews
* kpi_definitions – Supply chain performance metrics and weights
* employee_kpi_results – Employee performance against KPIs
* manager_reviews – Manager evaluation scores and qualitative feedback
* promotion_recommendations – Data-driven promotion eligibility

Relationships are implemented through primary keys and foreign keys to maintain referential integrity across the system.

## ❓ Business Questions

This project answers key performance management questions such as:
* Which employees consistently exceed supply chain KPI targets?
* How do employee performance scores compare across departments?
* Which employees qualify for promotion based on measurable criteria?
* Which KPIs have the greatest impact on overall performance scores?
* How does employee performance trend across evaluation cycles?

## 🧠 Key SQL Techniques Used

The project demonstrates several important SQL skills:
* Table creation and relational schema design
* Primary and foreign key relationships
* JOIN operations for combining HR and KPI data
* Aggregate functions (SUM, AVG)
* Weighted KPI score calculations
* GROUP BY for employee-level performance summaries
* Filtering and ranking high-performing employees

These techniques help transform raw operational data into meaningful performance insights.

## 📊 Key Insights from the Analysis

The analysis reveals several important insights:
* Employees with strong performance in high-weight KPIs contribute significantly to overall performance rankings.
* KPI-based evaluation enables objective comparison across departments and roles.
* Data-driven scoring identifies top performers who consistently exceed operational targets.
* Structured analytics improves transparency and reduces subjectivity in promotion decisions.

## 📈 Supply Chain KPIs Calculated

The system evaluates employees using common operational performance indicators, including:

* On-Time Delivery Rate (%)
* Forecast Accuracy (%)
* Inventory Turnover
* Cost Savings Achieved
* Service Level Compliance

Each KPI is assigned a performance weight, allowing leaders to calculate weighted performance scores that reflect operational priorities.

## 📁 Project Structure

employee-performance-analytics-sql

```
│
├── README.md
│
├── schema
│   └── create_tables.sql
│
├── data
│   └── sample_data.sql
│
├── queries
│   ├── appraisal_report.sql
│   ├── promotion_analysis.sql
│   └── kpi_analysis.sql
│
└── erd
    └── employee_performance_erd.png

* schema/ – SQL scripts for database structure
* data/ – Sample data used for testing and analysis
* queries/ – Analytical queries answering business questions
* erd/ – Visual entity-relationship diagram of the database
