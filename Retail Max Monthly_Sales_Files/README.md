# Retail Max Sales Dashboard

## Project Overview

The Retail Max Sales Dashboard is a Business Intelligence project developed in Power BI to analyze retail sales performance across multiple stores, products, customers, and sales representatives.

The project demonstrates the complete analytics workflow, from importing raw CSV files and transforming data in Power Query to building a star schema data model, creating DAX measures, and designing an interactive dashboard that supports business decision-making.

---

## Business Problem

Retail organizations generate large volumes of transactional sales data every month. Without an efficient reporting solution, it becomes difficult to monitor sales performance, identify trends, compare stores, and evaluate product performance.

The objective of this project was to automate data preparation and create an interactive dashboard that enables users to quickly explore sales performance and gain actionable business insights.

---

## Project Objectives

- Import and combine multiple monthly sales datasets
- Automate data ingestion using Power BI's Folder Connector
- Clean and transform raw data using Power Query
- Build a star schema data model
- Develop DAX measures and KPIs
- Design an interactive dashboard for business users

---

## Skills Demonstrated

- Power BI Desktop
- Power Query (ETL)
- Folder Automation (Folder Connector)
- Data Cleaning & Transformation
- Data Modeling
- Star Schema Design
- DAX
- Dashboard Design
- Business Intelligence
- Data Visualization

---

## Dataset

The project uses multiple monthly sales CSV files together with lookup tables for:

- Customers
- Products
- Stores
- Sales Representatives

Instead of importing each file individually, the project uses **Power BI's Folder Connector** (folder automation) to automatically combine monthly sales files into a single dataset. New monthly data can be incorporated by simply adding a CSV file to the folder and refreshing the report.

---

# Dashboard Preview

<img width="1012" height="677" alt="image" src="https://github.com/user-attachments/assets/bc734ee5-1645-4c28-acc7-3b9d1b6c84a8" />

The dashboard provides interactive business insights through KPI cards, charts, slicers, and drill-down capabilities that allow users to explore sales performance across different dimensions.

---

# Dashboard Planning (Wireframe)

Before building the dashboard, a wireframe was created to plan the report layout, visual placement, and user experience.

<img width="1280" height="720" alt="image" src="https://github.com/user-attachments/assets/46cdbe47-a3f2-4339-95e6-1f910876a6dd" />

The wireframe served as the blueprint for designing the final dashboard.

---

# Data Model

A star schema was designed to improve report performance and simplify relationships between fact and dimension tables.

<img width="1427" height="737" alt="image" src="https://github.com/user-attachments/assets/efcb9827-3427-4dfb-8f16-cafa93b07566" />

The data model connects the sales fact table with customer, product, store, and sales representative dimension tables, enabling efficient filtering and DAX calculations.

---

## Dashboard Features

- Executive KPI Cards
- Monthly Sales Trend Analysis
- Product Performance Analysis
- Store Performance Analysis
- Sales Representative Performance
- Interactive Filters and Slicers
- Drill-down Visualizations

---

## Development Stages

This repository includes multiple versions of the Power BI project to demonstrate the development process.

| File | Purpose |
|------|---------|
| **Initial Data Prep.pbix** | Imported raw CSV data, cleaned data using Power Query, and performed data transformation. |
| **Folder connector_Model development.pbix** | Implemented folder automation, created the star schema, and developed the data model. |
| **Retailmax_Dashboard.pbix** | Final dashboard containing DAX measures, KPIs, and interactive visualizations. |

---

## Tools & Technologies

- Power BI Desktop
- Power Query
- DAX
- CSV Files
- Folder Connector
- Star Schema Modeling

---

## Key Learning Outcomes

Throughout this project I learned how to:

- Automate data ingestion using Folder Connector
- Perform ETL processes with Power Query
- Build an efficient star schema
- Create reusable DAX calculations
- Design business-focused dashboards
- Present insights through effective visualizations

---

## Author

**Ebube Arinze**

Business Intelligence | Data Analytics | Power BI
