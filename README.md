
# 🏥 Healthcare Claims & Revenue Intelligence
### Snowflake | SQL | Power BI | Healthcare Analytics | Denial Intelligence

## 📌 Project Overview

The **Healthcare Claims & Revenue Intelligence Dashboard** is an end-to-end healthcare analytics project that combines Snowflake SQL and Power BI to analyze US healthcare insurance claims, financial performance, denial patterns, and payer-level trends.

The project demonstrates how healthcare claims data can be transformed into actionable business insights using Snowflake for data warehousing and SQL-based analysis, and Power BI for interactive reporting and visualization.

It focuses on claim volumes, approved amounts, denial rates, payer performance, and provider specialty trends to support operational efficiency and data-driven decision-making.

## 🎯 Business Objectives

- Analyze healthcare insurance claim volumes and financial performance.
- Monitor approved, denied, pending, and partially paid claims.
- Identify recurring claim denial categories and trends.
- Evaluate denial rates across different insurance payer types.
- Analyze approved claim amounts and payer performance.
- Identify provider specialties contributing to higher denial volumes.
- Develop interactive dashboards for healthcare business reporting.

## 🏗️ Project Architecture & Workflow

```text
Healthcare Claims Dataset (CSV)
             |
             ▼
      Snowflake Database
             |
             ▼
       SQL Analysis
             |
             ▼
  Data Cleaning & Validation
             |
             ▼
       Power BI
             |
             ▼
 Interactive Analytics Dashboard
             |
             ▼
     Business Insights
```

## 🛠️ Technology Stack

| Technology | Purpose |
|---|---|
| Snowflake | Cloud data warehousing and data management |
| Snowflake SQL | Data extraction, transformation and analytical queries |
| Power BI | Interactive dashboard development |
| Power Query | Data cleaning and transformation |
| DAX | KPI calculations and analytical measures |
| Excel / CSV | Dataset preparation and validation |
| Data Modeling | Relationships and analytical structure |

## 📊 Dashboard Overview

The dashboard consists of two interactive analytical pages.

### 1. Executive Summary

Provides a high-level overview of healthcare claims performance and financial outcomes.

**Key Performance Indicators:**
- Total Claims
- Total Claim Amount
- Total Approved Amount
- Overall Denial Rate

**Visualizations:**
- Claim distribution by outcome.
- Quarterly denial rate trends.
- Total approved amount by payer type.
- Interactive payer type and denial category slicers.

### 2. Denial Intelligence – Root Cause & Payer Analysis

Provides detailed insights into claim denials, payer performance, and provider specialty trends.

**Key Analysis Areas:**
- Denial rate by payer type.
- Denial count by denial category.
- Denial distribution by provider specialty.
- Payer-wise denial amounts across denial categories.
- Comparison of denial patterns across healthcare insurance payers.

**Denial Categories:**
- Authorization Missing
- Bundling
- Coding Error
- Duplicate Claims
- Eligibility
- Medical Necessity
- Timely Filing

## 📈 Key Business Questions

1. What percentage of submitted claims are denied?
2. Which payer types contribute the highest approved claim amounts?
3. Which denial categories account for the highest number of rejected claims?
4. Which provider specialties experience higher denial volumes?
5. How do denial rates change across quarters?
6. Which denial reasons have the greatest financial impact?
7. Where should claims operations focus their improvement efforts?

## 🔍 SQL & Snowflake Analytics

Snowflake SQL can be used to perform healthcare claims analysis, including:

- Aggregating claim amounts by payer type.
- Calculating claim denial percentages.
- Identifying top denial categories.
- Detecting duplicate claims and data quality issues.
- Analyzing quarterly claim trends.
- Ranking providers based on denial volumes.
- Creating reusable analytical queries and views.

## 💡 Analytical Skills Demonstrated

- Snowflake Data Warehousing
- Snowflake SQL
- Healthcare Claims Analytics
- Data Cleaning & Transformation
- Data Validation & Quality Checks
- Data Modeling
- KPI Development
- Financial Performance Analysis
- Denial Trend Analysis
- Root Cause Analysis
- Power BI Dashboard Development
- DAX & Data Visualization

## 🚀 Business Value

This project demonstrates how healthcare claims analytics can help organizations:

- Identify recurring claim denial patterns.
- Improve claims processing quality.
- Monitor payer-level financial performance.
- Highlight potential coding and authorization issues.
- Identify opportunities to reduce claim rework.
- Improve operational reporting and decision-making.

## 📁 Project Structure

```text
Healthcare-Claims-Revenue-Intelligence/
│
├── README.md
│
├── Dataset/
│   └── healthcare_claims.csv
│
├── Snowflake_SQL/
│   ├── database_setup.sql
│   ├── data_loading.sql
│   ├── data_cleaning.sql
│   └── claims_analysis.sql
│
├── PowerBI/
│   └── Healthcare_Claims_Analysis.pbix
│
└── Screenshots/
    ├── Executive_Summary.png
    └── Denial_Insights.png
```

*Note: Adjust the folder structure to match the actual files uploaded to your repository.*

## 👨‍💻 Author

**Syed Atifur Rab**

Data Analyst | Healthcare Analytics | Business Intelligence

**Technical Skills:** Snowflake | SQL | Python | Power BI | Tableau | Excel

**Domain Expertise:** US Healthcare Insurance | Claims Analytics | Denial Analysis | Financial Reporting

---

⭐ If you find this project useful, feel free to explore the dashboard and share your feedback.

**Disclaimer:** This is an independent portfolio project and is not an official Aetna product or an endorsement by Aetna. No confidential or proprietary company information is presented.
