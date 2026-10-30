# CityVision — Smart City Intelligence & Analytics Platform

CityVision integrates, analyzes, and visualizes urban data from six domains — **Traffic, Accidents, Weather, Air Quality, Transportation, and Energy** — in one unified analytical environment, turning fragmented city data into reliable, actionable insights.

**Project type:** Smart City Analytics / Data Analytics / Business Intelligence
**Duration:** 6 weeks | **Team size:** 6 members

## Problem

Urban data is spread across different sectors with different formats, timestamps, geographic details, and granularity levels. This makes it hard to see the city as a connected system, identify priority areas, detect recurring patterns, and anticipate future trends.

## Objectives

1. Collect and prepare data for the six urban domains.
2. Clean data (missing values, duplicates, inconsistent formats) with SQL and Python.
3. Integrate compatible datasets into a unified analytical model.
4. Perform Exploratory Data Analysis (EDA).
5. Build interactive Power BI dashboards for KPIs, time, and location analysis.
6. Build a forecasting model for at least one suitable indicator (e.g., traffic volume or energy consumption), evaluated against a baseline.
7. Provide data-driven recommendations.
8. Document implementation, testing, and findings for reproducibility.

## Tech Stack

- SQL Server / PostgreSQL — storage, cleaning, integration
- Python (Pandas, NumPy) and Jupyter Notebook — analysis and forecasting
- Power BI Desktop — semantic model, DAX measures, dashboards
- Git & GitHub — version control and collaboration

## Repository Structure

```text
CityVision/
├── 01_Project_Management/   Proposal, plan, roles, risks, KPIs
├── 02_Data/                 Raw and processed datasets, data dictionary
├── 03_SQL/                  Cleaning, integration, and KPI queries
├── 04_Python/               Cleaning, EDA, and forecasting notebooks
├── 05_PowerBI/              CityVision dashboard (.pbix)
├── 06_Reports/              Data quality, forecast evaluation, final report
├── CityVision_Presentation.pptx
└── README.md
```

Full project documentation: [`01_Project_Management/Project_Documentation.md`](01_Project_Management/Project_Documentation.md)

## Project Plan (6 Weeks)

| Week | Phase | Key Deliverables |
|---|---|---|
| 1 | Planning & Data Discovery | Proposal, dataset inventory, KPI requirements |
| 2 | Data Cleaning & Integration | Cleaned datasets, SQL scripts, data quality report |
| 3 | EDA & Data Modeling | Python notebooks, data model, KPI definitions |
| 4 | Power BI Development | Interactive dashboard MVP |
| 5 | Forecasting & Recommendations | Forecasting notebook, evaluation report, recommendations |
| 6 | Testing & Final Delivery | Final dashboard, report, presentation |

## Team

| Member | Role |
|---|---|
| آلاء أيمن رمضان إسماعيل | Team Leader & Project Coordinator |
| نيرة أبو الفتوح عبد المحسن سالم | Data Sources & Data Quality |
| عبد الرحمن محمد عبد العظيم قناوي | SQL Developer & Data Integration |
| شهد سليمان العمروسي | Python Data Analyst |
| مروة ناصر عبد الرحمن سويلم | Power BI Developer |
| ضياء محمد إبراهيم السيد | Forecasting, QA & Reporting |

## Out of Scope

Controlling traffic lights or infrastructure, deploying IoT sensors, a real-time operational system, a citizen mobile app, and guaranteeing predictions for every city event.

## Success Metrics

Data quality (completeness ≥ 95%, duplicates ≤ 1%), dashboard performance (load ≤ 5 s, KPI accuracy 100% on tested cases), forecasting (MAE, RMSE, MAPE vs. a baseline), and business impact (traceable, evidence-based recommendations). Targets are proposed and will be reviewed against the actual data.
