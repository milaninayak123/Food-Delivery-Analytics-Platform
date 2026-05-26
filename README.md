# Food Delivery Analytics Platform

End-to-end analytics solution built using Microsoft Fabric, SQL, and Power BI to analyze food delivery operations, restaurant performance, and customer ordering trends.

---

# Project Overview

This project demonstrates the implementation of a modern analytics architecture using Microsoft Fabric. The solution ingests raw food delivery datasets into a Lakehouse, performs SQL-based transformation and validation, models the data using a Star Schema Data Warehouse, and creates interactive Power BI dashboards for business insights.

The project focuses on building a scalable analytics workflow similar to real-world enterprise BI systems.

---

# Business Objective

The objective of this project is to:

- Store and manage raw operational datasets
- Clean and validate data using SQL
- Build a dimensional data warehouse model
- Create KPI-driven dashboards
- Generate actionable business insights

---

# Architecture Flow

```text
Raw CSV Files
    ↓
Fabric Lakehouse
    ↓
SQL Data Cleaning & Validation
    ↓
Data Warehouse (Star Schema)
    ↓
Power BI Semantic Model
    ↓
Interactive Power BI Dashboard
```

---

# Technology Stack

| Layer | Technology |
|---|---|
| Data Storage | Microsoft Fabric Lakehouse |
| Data Cleaning | SQL / T-SQL |
| Data Processing | Fabric Data Pipelines |
| Data Modeling | Data Warehouse |
| Semantic Layer | Power BI Semantic Model |
| Visualization | Power BI |

---

# Data Warehouse Model

## Fact Table
- fact_orders

## Dimension Tables
- dim_date
- dim_dish
- dim_location
- dim_restaurant

The warehouse model follows a Star Schema design for optimized analytical querying and reporting.

---

# Key Data Processing Tasks

- Data ingestion into Lakehouse
- Handling missing values
- Duplicate removal
- Data validation checks
- Referential integrity validation
- SQL-based transformations
- Star schema implementation

---

# Dashboard Insights

The Power BI dashboard provides insights into:

- Order volume trends
- Restaurant performance analysis
- City-wise order distribution
- Food category analysis
- Ratings and customer trends
- Revenue and KPI tracking

---

# Project Screenshots

## Fabric Workspace
<img width="1919" height="905" alt="image" src="https://github.com/user-attachments/assets/be29ad10-d612-4051-bec2-fca07a638a9a" />

## Semantic Model
<img width="1919" height="982" alt="image" src="https://github.com/user-attachments/assets/c7340cc6-776b-4ac9-be2a-906c746bf83a" />

## Power BI Dashboard
<img width="1372" height="725" alt="image" src="https://github.com/user-attachments/assets/98a828a2-8d45-47ba-aa98-4647985d322e" />

---

# Future Enhancements

- Real-time streaming analytics
- Python-based predictive analytics
- Customer segmentation
- Automated pipeline scheduling

---

# Author

Milani Nayak
