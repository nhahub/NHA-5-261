# CityVision — Smart City Intelligence & Analytics Platform

## Project Documentation

**Project Type:** Smart City Analytics / Data Analytics / Business Intelligence

**Planned Duration:** 6 weeks

**Team Size:** 6 members

**Team Leader:** آلاء أيمن رمضان إسماعيل

---

# 1. Project Proposal

## 1.1 Project Overview

**CityVision** is a Smart City Intelligence & Analytics Platform designed to integrate, analyze, and visualize urban data from multiple sectors in one unified analytical environment.

The platform focuses on six main domains:

- Traffic
- Accidents
- Weather
- Air Quality
- Transportation
- Energy

Using SQL and Python, the project performs data cleaning, transformation, integration, and exploratory analysis. Power BI is used to develop interactive dashboards that monitor key performance indicators, identify trends, compare locations, and highlight potential urban challenges.

The project also explores Predictive Analytics and Forecasting for selected indicators, such as traffic volume and energy consumption, depending on data availability and quality. Finally, the analytical findings are translated into data-driven recommendations that support more efficient, safer, and more sustainable urban management.

## 1.2 Problem Statement

Urban data is often distributed across multiple sources and managed separately by different sectors. Differences in data formats, timestamps, geographic details, and levels of granularity make it difficult to analyze the city as a connected system.

Without a unified analytical view, it is challenging to identify priority areas, understand relationships between urban factors, detect recurring patterns, and anticipate future trends.

**CityVision addresses this problem by transforming fragmented urban data into unified, reliable, and actionable insights.**

## 1.3 Project Objectives

1. Collect and prepare data related to the six selected urban domains.
2. Clean data and handle missing values, duplicates, and inconsistent formats using SQL and Python.
3. Integrate compatible datasets into a unified analytical model.
4. Perform Exploratory Data Analysis (EDA) to identify trends, patterns, and relationships.
5. Develop interactive Power BI dashboards to monitor KPIs and analyze temporal and geographic differences.
6. Build a forecasting model for at least one suitable indicator, if sufficient historical data is available.
7. Provide data-driven recommendations to support transportation efficiency, safety, energy use, and quality of life.
8. Document implementation steps, testing, and findings to support review and reproducibility.

## 1.4 Project Scope

### In Scope

- Collecting datasets from open or reliable sources.
- Analyzing Traffic, Accidents, Weather, Air Quality, Transportation, and Energy.
- Data Cleaning, Transformation, and Integration.
- SQL Queries, Python Analysis, and Data Modeling.
- KPI Development and Interactive Power BI Dashboards.
- Maps, Charts, Trends, and Cross-Domain Analysis.
- Forecasting selected indicators and evaluating model performance.
- Preparing reports, recommendations, and final documentation.

### Out of Scope

- Directly controlling traffic lights or city infrastructure.
- Deploying physical sensors or IoT devices.
- Building a fully operational, real-time city management system.
- Developing a standalone citizen mobile application.
- Executing government decisions or making physical infrastructure changes.
- Guaranteeing accurate predictions for every city event or domain.
- Using paid cloud services without a demonstrated need and team approval.

## 1.5 Expected Deliverables

- Project Proposal and Project Management Documentation.
- Raw datasets with documented sources and definitions.
- Cleaned and integrated datasets.
- SQL scripts and Python notebooks.
- Data Model and Data Dictionary.
- Interactive Power BI Dashboard (`.pbix`).
- Forecasting Model and Evaluation Report, where appropriate.
- Final Analytical Report with findings and recommendations.
- Final Presentation.

---

# 2. Project Plan

## 2.1 Project Timeline

The proposed duration is **6 weeks**. The plan assumes that the team uses existing datasets rather than building physical smart-city infrastructure.

| Week | Phase | Main Tasks | Deliverables |
|---|---|---|---|
| Week 1 | Planning & Data Discovery | Define project scope, identify data sources, document business questions, and define initial KPIs. | Project Proposal, Dataset Inventory, KPI Requirements |
| Week 2 | Data Cleaning & Integration | Inspect datasets, handle missing values and duplicates, standardize units and dates, and prepare compatible tables. | Cleaned Datasets, SQL Scripts, Data Quality Report |
| Week 3 | EDA & Data Modeling | Analyze trends and relationships, investigate temporal and geographic patterns, and design the analytical model. | Python Notebooks, Data Model, KPI Definitions |
| Week 4 | Power BI Development | Build the semantic model, DAX measures, dashboard pages, maps, and interactive filters. | Interactive Dashboard MVP |
| Week 5 | Forecasting & Recommendations | Select a suitable indicator, build a baseline forecast, evaluate model performance, and prepare recommendations. | Forecasting Notebook, Evaluation Report, Recommendations |
| Week 6 | Testing & Final Delivery | Validate data and KPIs, test dashboard interactions, finalize documentation, and prepare the presentation. | Final Dashboard, Final Report, Presentation, README |

## 2.2 Milestones

| Deadline | Milestone | Completion Criteria |
|---|---|---|
| End of Week 1 | Planning Approved | Scope and data sources are agreed upon. |
| End of Week 2 | Data Ready | Datasets are prepared and pass agreed basic quality checks. |
| End of Week 3 | Analysis Ready | The data model and primary KPIs are documented. |
| End of Week 4 | Dashboard MVP | Main visuals, KPIs, and filters work. |
| End of Week 5 | Forecasting Ready | Forecast is evaluated against a baseline if the data supports forecasting. |
| End of Week 6 | Final Delivery | Testing, documentation, and presentation are completed. |

## 2.3 Required Resources

| Resource | Purpose |
|---|---|
| SQL Server or PostgreSQL | Data storage, querying, and integration |
| Python and Jupyter Notebook | Data cleaning, analysis, and forecasting |
| Power BI Desktop | Dashboard development and KPI visualization |
| Git and GitHub | Version control and team collaboration |
| Open Data Sources | Urban datasets for analysis |
| Team Members | Data engineering, analysis, BI, forecasting, testing, and coordination |

**Cloud Infrastructure:** Cloud services such as AWS are not required for the initial version. They can be considered later if a real deployment or cloud-processing requirement emerges.

---

# 3. Task Assignment & Roles

## 3.1 Team Members

1. نيرة أبو الفتوح عبد المحسن سالم
2. آلاء أيمن رمضان إسماعيل — Team Leader
3. عبد الرحمن محمد عبد العظيم قناوي
4. شهد سليمان العمروسي
5. مروة ناصر عبد الرحمن سويلم
6. ضياء محمد إبراهيم السيد

## 3.2 Responsibility Assignment

| Team Member | Primary Role | Main Responsibilities |
|---|---|---|
| آلاء أيمن رمضان إسماعيل | Team Leader & Project Coordinator | Coordinate the team, monitor deadlines and risks, facilitate decisions, review deliverables, and coordinate the final presentation. |
| نيرة أبو الفتوح عبد المحسن سالم | Data Sources & Data Quality | Find and document datasets, inspect source quality, define data dictionaries, identify missing values and duplicates, and maintain data-quality checks. |
| عبد الرحمن محمد عبد العظيم قناوي | SQL Developer & Data Integration | Develop SQL cleaning and integration scripts, define table structures and keys, document joins, and validate integration results. |
| شهد سليمان العمروسي | Python Data Analyst | Perform data preparation and EDA using Pandas and NumPy, analyze trends and relationships, and document analytical findings. |
| مروة ناصر عبد الرحمن سويلم | Power BI Developer | Build the semantic model, DAX measures, KPI cards, charts, maps, filters, and dashboard pages; validate displayed metrics. |
| ضياء محمد إبراهيم السيد | Forecasting, QA & Reporting | Develop and evaluate a baseline forecast when appropriate, support cross-checking of results, document limitations, and help prepare the final analytical report and presentation. |

### Shared Responsibilities

- All members review the project scope, KPIs, and final findings.
- Members collaborate when one task depends on another member's output.
- SQL and Python results are checked against the Power BI metrics.
- Team members document assumptions, transformations, and limitations.
- Work is stored in a shared repository with clear file names and version control.

## 3.3 Team Collaboration Rules

- Hold a weekly progress meeting to review completed tasks and blockers.
- Assign an owner and due date to every task.
- Agree on KPI definitions before dashboard development.
- Use GitHub to manage code and changes.
- Review analytical findings before including them in the final report.
- Ensure all team members understand the end-to-end project, not only their own tasks.

---

# 4. Risk Assessment & Mitigation

## 4.1 Risk Register

| Risk | Probability | Impact | Mitigation Strategy |
|---|---|---|---|
| Insufficient data for one or more domains | High | High | Identify alternative sources and reduce the scope to domains with reliable data. |
| Inconsistent data formats, units, or timestamps | High | High | Standardize schemas, dates, units, and transformation rules; document all changes. |
| Difficulty integrating datasets | High | High | Identify shared keys and validate time and location compatibility before joining data. |
| Missing values or duplicates | High | Medium | Create data-quality checks and document handling rules without hiding source limitations. |
| Poor forecasting performance | Medium | High | Compare with a simple baseline, use time-aware validation, and report limitations. |
| Dashboard development delays | Medium | Medium | Build a minimum viable dashboard early and prioritize core KPIs. |
| Differences between SQL and Power BI results | Medium | High | Compare totals and counts and test measures against defined reference cases. |
| Unexpected cloud-service costs | Low | Medium | Prefer local tools and review costs before enabling paid services. |
| Lost files or conflicting team changes | Medium | Medium | Use version control, backups, and a review process for shared changes. |
| Treating correlation as causation | Medium | High | Clearly distinguish statistical association from causation and avoid unsupported claims. |

These ratings are initial estimates and are updated after the datasets and final technical design are selected.

## 4.2 Risk Response Strategies

- **Avoid:** Remove unnecessary features that could delay delivery.
- **Mitigate:** Reduce the likelihood or impact of a risk through preventive actions.
- **Transfer:** Transfer contractual risks to a service provider when an applicable agreement exists.
- **Accept:** Accept low-impact risks while documenting and monitoring them.

## 4.3 Risk Monitoring

The team leader coordinates a weekly risk review. For each risk, the team records:

- **Risk Owner:** The person responsible for monitoring the risk.
- **Probability and Impact:** The estimated likelihood and consequence.
- **Mitigation Action:** The planned preventive or corrective action.
- **Status:** Open, in progress, mitigated, or closed.
- **Escalation:** When the issue needs a team decision or scope adjustment.

---

# 5. KPIs — Project Success Metrics

CityVision measures success across four dimensions: data quality, dashboard performance, predictive analytics, and business value. The targets below are **proposed project targets**, not measured results, and are reviewed after inspecting the actual datasets and testing the system.

## 5.1 Data Quality KPIs

| KPI | Definition | Proposed Target |
|---|---|---|
| Data Completeness | Percentage of non-missing values in required fields | ≥ 95% |
| Duplicate Rate | Percentage of duplicate records based on documented duplicate rules | ≤ 1% |
| Integration Success Rate | Percentage of eligible records successfully linked | ≥ 95% |
| Validation Pass Rate | Percentage of data-quality tests passed | ≥ 95% |

Missing values and duplicates are measured using clearly documented rules. Valid records are not deleted simply to meet a target.

## 5.2 Dashboard & Technical KPIs

| KPI | Measurement | Proposed Target |
|---|---|---|
| Dashboard Load Time | Time to load the main dashboard page in the test environment | ≤ 5 seconds |
| Filter Response Time | Time for visuals to update after a filter change | ≤ 3 seconds |
| KPI Accuracy | Agreement between Power BI measures and SQL reference results | 100% for tested cases |
| Functional Test Pass Rate | Percentage of dashboard functional tests passed | ≥ 95% |
| Service Availability | Percentage of time a deployed service is available during a defined period | Set if deployment is implemented |

Load and response times depend on data volume, hardware, and deployment method, so they are measured during testing rather than assumed.

## 5.3 Predictive Analytics KPIs

The initial forecasting target is one suitable indicator, such as traffic volume, provided that sufficient historical data is available.

| KPI | Purpose |
|---|---|
| MAE — Mean Absolute Error | Measures average absolute prediction error. |
| RMSE — Root Mean Squared Error | Gives greater weight to larger errors. |
| MAPE — Mean Absolute Percentage Error | Measures relative error when actual values make the metric appropriate. |
| Baseline Improvement | Compares the selected model with a simple baseline forecast. |
| Forecast Coverage | Measures the periods for which valid forecasts can be produced. |

Time-aware training and testing splits are used to avoid future-data leakage. A final accuracy target is only set after evaluating the data and comparing model results with a baseline.

## 5.4 Business Impact KPIs

| KPI | Measurement |
|---|---|
| Critical Areas Identified | Number of areas prioritized using documented criteria |
| Actionable Insights | Number of findings linked to a specific, practical recommendation |
| Cross-Domain Insights | Number of data-supported findings involving multiple domains |
| Recommendation Traceability | Percentage of recommendations linked to documented analytical evidence |
| Domain Coverage | Percentage of selected domains represented by agreed dashboard metrics |

Identifying an opportunity for improvement does not prove that a real-world outcome has improved. Demonstrating an actual reduction in traffic, accidents, or energy consumption would require implementing an intervention and comparing suitable before-and-after data.

## 5.5 Project Success Criteria

CityVision is considered ready for delivery when:

- The project scope and data sources are documented and agreed upon.
- Data preparation and integration steps are reproducible and documented.
- The agreed data-quality checks have been completed.
- SQL scripts and Python notebooks are available for review.
- The Power BI dashboard supports the agreed core KPIs and filters.
- KPI results have been validated against reference calculations.
- A forecasting model has been evaluated against a baseline when the data supports forecasting.
- The final report, recommendations, documentation, and presentation are complete.
