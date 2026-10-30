<div align="center">

  <h1>🌆 CityVision</h1>
  <h3>Smart City Intelligence & Analytics Platform</h3>

  <p>
    <strong>Integrating, Analyzing, and Visualizing Multi-Domain Urban Data for Smart Decision Making</strong>
  </p>

  <!-- Badges Stack -->
  <p>
    <img src="https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
    <img src="https://img.shields.io/badge/SQL%20Server-Database-CC292B?style=for-the-badge&logo=microsoft-sql-server&logoColor=white" alt="SQL Server" />
    <img src="https://img.shields.io/badge/Power%20BI-Analytics-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" alt="Power BI" />
    <img src="https://img.shields.io/badge/Git-Version%20Control-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
  </p>

  <p>
    <img src="https://img.shields.io/badge/Type-Smart%20City%20%2F%20Data%20Analytics-blue?style=flat-square" alt="Type" />
    <img src="https://img.shields.io/badge/Duration-6%20Weeks-orange?style=flat-square" alt="Duration" />
    <img src="https://img.shields.io/badge/Team%20Size-6%20Members-brightgreen?style=flat-square" alt="Team Size" />
  </p>

</div>

---

## 🎯 Executive Summary

**CityVision** is a Smart City Intelligence & Analytics Platform that integrates, analyzes, and visualizes urban data from six key domains in one unified analytical environment:

<div align="center">

| 🚗 **Traffic** | 🚨 **Accidents** | 🌤️ **Weather** | 🍃 **Air Quality** | 🚌 **Transportation** | ⚡ **Energy** |
| :---: | :---: | :---: | :---: | :---: | :---: |

</div>

By bridging disparate urban datasets, **CityVision** transforms fragmented municipal raw data into reliable, real-time actionable insights for city planners, engineers, and policymakers.

---

## ⚠️ The Problem

Urban data is traditionally **siloed across different municipal sectors** with varying formats, recording timestamps, geographic details, and granularity levels. 

> 🚨 **Core Challenge:** City leadership cannot view the city as a unified, connected ecosystem, making it difficult to pinpoint high-priority infrastructure zones, identify recurring spatial-temporal patterns, or forecast future utility and transport demands.

---

## 🚀 Key Objectives

- [x] **Multi-Source Ingestion:** Collect and clean open-source datasets across all 6 core urban domains.
- [x] **ETL & Data Hygiene:** Standardize schema, impute missing values, and handle duplicates using **SQL** and **Python**.
- [x] **Unified Modeling:** Architect a relational Star-Schema model connecting all six domains seamlessly.
- [x] **Exploratory Data Analysis:** Conduct deep-dive spatial, temporal, and multivariate correlation analysis.
- [x] **Executive Dashboards:** Build high-impact interactive **Power BI** dashboards for instant KPI monitoring and geographic drill-downs.
- [x] **Predictive Modeling:** Train time-series forecasting models (evaluated via MAE, RMSE, and MAPE vs. baseline) for key indicators like traffic volume and energy loads.
- [x] **Strategic Recommendations:** Formulate data-backed policy and operational recommendations.

---

## 🛠️ Tech Stack & Architecture

| Layer | Tools & Technologies |
| :--- | :--- |
| **Data Storage & Integration** | `Microsoft SQL Server` / `PostgreSQL` |
| **Data Processing & Analytics** | `Python 3.10+`, `Pandas`, `NumPy`, `Jupyter Notebooks` |
| **Business Intelligence** | `Power BI Desktop`, `DAX`, `Power Query` |
| **Version Control & Docs** | `Git`, `GitHub`, `Markdown` |

---

## 📂 Repository Structure

```text
CityVision/
├── 📁 01_Project_Management/   # Proposal, execution plans, role matrices, risk logs
├── 📁 02_Data/                 # Raw & cleaned datasets, schema dictionaries
├── 📁 03_SQL/                  # ETL scripts, cleaning queries, KPI views
├── 📁 04_Python/               # Processing, EDA notebooks, time-series forecasting
├── 📁 05_PowerBI/              # Interactive dashboard files (.pbix)
├── 📁 06_Reports/              # Data Quality Reports, Forecast evaluations, Final Documentation
├── 📊 CityVision_Presentation.pptx
└── 📄 README.md
```
---
📖 For full technical documentation, see
[`01_Project_Management/Project_Documentation.md`](01_Project_Management/Project_Documentation.md)

## 📅 6-Week Execution Roadmap

| Week | Phase | Focus Area & Key Deliverables |
| :---: | :--- | :--- |
| **Week 1** | **Planning & Discovery** | Project Charter, Dataset Inventory, KPI Mapping |
| **Week 2** | **Cleaning & Integration** | SQL ETL Scripts, Data Standardization & Quality Report |
| **Week 3** | **EDA & Data Modeling** | Jupyter Analytics Notebooks, Star Schema Architecture |
| **Week 4** | **Power BI Development** | Dynamic DAX Metrics, Geospatial Maps & Dashboard MVP |
| **Week 5** | **Forecasting & Insights** | Time-Series Analytics, Evaluation Report & Policy Brief |
| **Week 6** | **Testing & Delivery** | SQL vs Power BI QA, Final Technical Documentation & Presentation |

---

## 👥 The CityVision Team

| Member | Role |
| :--- | :--- |
| **آلاء أيمن رمضان الصعيدي** | Team Leader & Project Coordinator |
| **نيرة أبو الفتوح عبد المحسن سالم** | Data Sources & Data Quality |
| **عبد الرحمن محمد عبد العظيم قناوي** | SQL Developer & Data Integration |
| **شهد سليمان العمروسي** | Python Data Analyst |
| **مروة ناصر عبد الرحمن سويلم** | Power BI Developer |
| **ضياء محمد إبراهيم السيد**| Forecasting, QA & Reporting |
## 🚫 Out of Scope

To maintain project rigor within the 6-week timeframe, the following are explicitly out of scope:
- Live physical traffic signal actuation or IoT hardware deployment.
- Production real-time streaming pipelines (e.g., Kafka / Flink).
- End-user mobile app development.

---

## 📈 Success & Performance Metrics

- **Data Integrity:** Completeness ≥ 95%, Duplicate records ≤ 1%.
- **Dashboard Performance:** Full page load time ≤ 5 seconds, 100% accuracy on tested DAX aggregations.
- **Forecasting Precision:** Model performance benchmarked and superior to naive baselines via MAE, RMSE, and MAPE.
- **Actionability:** All operational insights directly mapped to verified quantitative findings.
