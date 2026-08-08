# Enterprise Retail Intelligence Platform

<div align="center">

### An Industry-Oriented Retail Analytics & Business Intelligence Platform

Transforming raw retail transaction data into customer intelligence, sales insights, business analytics, and decision-ready dashboards.

<br>

<img src="https://img.shields.io/badge/Python-Data%20Analytics-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
<img src="https://img.shields.io/badge/Jupyter-Analytics-F37626?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter">
<img src="https://img.shields.io/badge/Pandas-Data%20Processing-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas">
<img src="https://img.shields.io/badge/NumPy-Numerical%20Analysis-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy">
<img src="https://img.shields.io/badge/SQL-Business%20Analysis-4479A1?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQL">
<img src="https://img.shields.io/badge/Power%20BI-Business%20Intelligence-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" alt="Power BI">

</div>

---

## Project Overview

**Enterprise Retail Intelligence Platform** is an ongoing end-to-end retail analytics project designed to simulate a real-world business intelligence workflow.

The platform works with online retail transaction data and progressively transforms raw transactional data into structured analytical outputs, customer intelligence, SQL-based business insights, and interactive Power BI reporting.

The project is being developed as a long-term analytics platform rather than a single academic project.

The current implementation focuses on:

- Data understanding
- Data cleaning and preparation
- Exploratory Data Analysis
- Customer analytics
- RFM customer segmentation
- SQL business analysis
- Power BI dashboard development
- Business reporting and visualization

---

## Business Objective

The primary objective of the platform is to transform raw retail transaction data into meaningful business intelligence that can support data-driven decision-making.

The project focuses on questions such as:

- Which customers are most valuable?
- Which customers purchase most frequently?
- Which customers may require retention efforts?
- What are the major purchasing patterns?
- Which products and markets perform strongly?
- How can customers be segmented based on purchasing behaviour?
- What business insights can be extracted using SQL?
- How can analytical results be converted into management-ready dashboards?

---

## Project Workflow

```text
Raw Retail Data
       |
       v
Data Understanding
       |
       v
Data Cleaning & Preparation
       |
       v
Exploratory Data Analysis
       |
       +----------------------+
       |                      |
       v                      v
Customer Analysis       Business Analysis
       |                      |
       v                      v
RFM Segmentation        SQL Analysis
       |                      |
       +----------+-----------+
                  |
                  v
             Power BI
             Reporting
                  |
                  v
        Business Intelligence
                  |
                  v
           Decision Support



           
```text

## Current Project Status

**Work in Progress**

The current development phase includes:

- Data Understanding
- Data Cleaning
- Exploratory Data Analysis
- RFM Customer Segmentation
- SQL Business Analysis
- Initial Power BI Dashboard Development

The project is **not finished yet**. Additional dashboards, advanced analytics, business reporting, and decision-support features will be added progressively.



## Analytical Modules

### 1. Data Understanding

The first stage focuses on understanding the structure, characteristics, and quality of the raw retail transaction dataset.

Key activities include:

- Dataset inspection
- Dataset dimensions
- Column identification
- Data type analysis
- Initial data profiling
- Understanding transaction-level data

Notebook:

`notebook/01_understand_data.ipynb`

---

### 2. Data Cleaning & Preparation

The raw dataset is cleaned and prepared for downstream analytics.

Key activities include:

- Missing value analysis
- Duplicate record analysis
- Data type correction
- Data validation
- Data transformation
- Handling inconsistent records
- Preparation of analytical datasets

Notebook:

`notebook/02_data_cleaning.ipynb`

Cleaned dataset:

`data/cleaned/cleaned_online_retail.csv`

---

### 3. Exploratory Data Analysis

Exploratory Data Analysis is used to identify patterns, trends, relationships, and business opportunities within the retail data.

The analysis covers:

- Revenue analysis
- Product performance
- Customer behaviour
- Transaction patterns
- Quantity analysis
- Market performance
- Sales distributions
- Business KPIs
- Numerical relationships

Notebook:

`notebook/03_exploratory_data_analysis.ipynb`

---

## Customer Intelligence

### RFM Customer Segmentation

The platform uses **RFM Analysis** to understand customer purchasing behaviour and customer value.

RFM represents:

- **Recency** — How recently a customer made a purchase
- **Frequency** — How frequently a customer makes purchases
- **Monetary** — How much revenue a customer generates

RFM analysis is used to create meaningful customer segments that can support:

- Customer prioritization
- Customer retention
- Targeted marketing
- Loyalty strategies
- Customer value analysis
- Retention and churn analysis

Notebook:

`notebook/04_rfm_customer_segmentation.ipynb`

Generated analytical output:

`data/analytics/rfm_customer_segments.csv`

---

## SQL Business Analysis

SQL is used as an additional analytical layer for performing business-oriented analysis on structured retail data.

The SQL workflow focuses on:

- Customer analysis
- Product analysis
- Revenue analysis
- Transaction analysis
- Business KPIs
- Aggregations
- Filtering
- Grouping
- Business-oriented analytical queries

Notebook:

`notebook/05_sql_business_analysis.ipynb`

Database:

`notebook/retail.db`

---

## Power BI Business Intelligence

Power BI is used to convert analytical outputs into interactive business intelligence dashboards.

The dashboard layer focuses on:

- Business KPIs
- Customer insights
- Sales performance
- Product performance
- Revenue analysis
- Interactive visualizations
- Business reporting
- Management-level analysis

The Power BI layer is currently under active development, with additional dashboards planned as the analytical platform expands.

Power BI project:

`Powerbi/Enterprise_Retail_Intelligence_Dashboard.pbix`

---

## Technology Stack

| Category | Technology |
|---|---|
| Programming | Python |
| Data Analysis | Pandas |
| Numerical Computing | NumPy |
| Analysis Environment | Jupyter Notebook |
| Database | SQLite |
| Query Language | SQL |
| Business Intelligence | Power BI |
| Data Storage | CSV |
| Version Control | Git |
| Repository | GitHub |

---

## Project Structure

```text
ENTERPRISE_RETAIL_INTELLIGENCE_PLATFORM/
│
├── data/
│   ├── analytics/
│   │   └── rfm_customer_segments.csv
│   │
│   ├── cleaned/
│   │   └── cleaned_online_retail.csv
│   │
│   └── raw/
│       └── online_retail_data.csv
│
├── notebook/
│   ├── 01_understand_data.ipynb
│   ├── 02_data_cleaning.ipynb
│   ├── 03_exploratory_data_analysis.ipynb
│   ├── 04_rfm_customer_segmentation.ipynb
│   ├── 05_sql_business_analysis.ipynb
│   └── retail.db
│
├── Powerbi/
│   └── Enterprise_Retail_Intelligence_Dashboard.pbix
│
├── Reports/
│
├── SQL/
│
├── src/
│
├── Visuals/
│
├── .gitignore
├── README.md
└── requirements.txt

---

## Key Analytical Capabilities

The current platform demonstrates practical implementation of:

- Data Understanding
- Data Cleaning
- Data Transformation
- Exploratory Data Analysis
- Customer Analytics
- RFM Customer Segmentation
- SQL Business Analysis
- Business KPI Analysis
- Data Visualization
- Business Intelligence
- Dashboard Development

---

## Business Value

The platform follows a complete analytics pipeline designed to convert raw transactional data into actionable business intelligence.

```text
Raw Data
   |
   v
Data Cleaning
   |
   v
Exploratory Analysis
   |
   v
Customer Intelligence
   |
   v
RFM Segmentation
   |
   v
SQL Business Analysis
   |
   v
Power BI Reporting
   |
   v
Business Insights
   |
   v
Decision Support

---

## Author

### Ishu Sharma

**Aspiring Data Analyst | Python | SQL | Power BI | Business Intelligence**

Core areas of focus:

- Python
- SQL
- Power BI
- Excel
- Data Analytics
- Business Intelligence
- Customer Analytics
- Data Visualization
- Business Problem Solving

---

## License

This project is developed for portfolio, learning, and demonstration purposes.