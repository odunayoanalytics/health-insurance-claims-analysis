# 🏥 Health Insurance Claims Performance & Denial Analysis

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?logo=powerbi&logoColor=black)
![Excel](https://img.shields.io/badge/Microsoft%20Excel-Data%20Preparation-217346?logo=microsoftexcel&logoColor=white)
![Power Query](https://img.shields.io/badge/Power%20Query-Data%20Transformation-5B8C5A)
![DAX](https://img.shields.io/badge/DAX-Data%20Modelling-blue)

## 📊 Project Overview

This project analyses health insurance claims data using Microsoft Power BI to evaluate claims performance, denial patterns, and financial exposure.

The objective is to transform claims data into actionable insights that support claims management, financial monitoring, and evidence-based decision-making.

## 🎯 Business Objectives

- Evaluate overall claims portfolio performance.
- Measure approval, denial, and pending rates.
- Analyse claims volume and value over time.
- Compare denial rates across provider specialties, claim types, and submission methods.
- Quantify the financial value of denied claims.
- Develop recommendations to improve claims monitoring.

## 🗂️ Dataset Overview

- **Records:** 4,500 claims
- **Columns:** 17
- **Period:** 9 July 2022 – 8 July 2024

The dataset includes claim dates, claim amounts, claim status, claim types, provider specialties, submission methods, and patient-related attributes.

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| Microsoft Excel | Initial data review |
| Power Query | Data cleaning and transformation |
| Power BI | Interactive dashboard development |
| DAX | KPI calculations and analytical measures |
| Date table | Time-based analysis |

## ⚙️ Methodology

1. **Data inspection:** Reviewed dataset structure, column types, and completeness.
2. **Data preparation:** Validated data types and transformed fields in Power Query.
3. **Feature engineering:** Created date-related helper columns and age groups.
4. **Data modelling:** Created a dedicated date table and established a relationship with the claims table.
5. **DAX measures:** Calculated claims volume, claim value, status counts, rates, and denied claim value.
6. **Visualisation:** Developed three dashboard pages for performance, denial analysis, and business recommendations.

## 📐 Key Performance Indicators

- Total Claims
- Total Claim Amount
- Average Claim Amount
- Approval Rate
- Denial Rate
- Pending Rate
- Denied Claim Amount
- Denied Amount as a Percentage of Total Claim Value

## 📈 Key Findings

| Metric | Result |
|---|---:|
| Total claims | 4,500 |
| Total claim value | Approximately $22.56 million |
| Approval rate | 33.8% |
| Denial rate | 33.6% |
| Pending rate | 32.6% |
| Denied claim value | Approximately $7.55 million |
| Denied amount as a share of total claim value | Approximately 33.5% |

### 🔍 Denial Patterns

- General Practice denial rate: **35.5%**
- Orthopedics denial rate: **30.3%**
- Online submission denial rate: **35.9%**
- Phone submission denial rate: **31.8%**

These differences identify areas for further investigation but do not establish the causes of claim denials.

## 🖥️ Dashboard Preview

### 1. Executive Claims Performance

![Executive Claims Performance](Dashboard%20Screenshot%201.png)

Overview of claims volume, financial value, claim outcomes, and trends.

### 2. Denial & Financial Analysis

![Denial and Financial Analysis](Dashboard%20Screenshot%202.png)

Comparison of denial rates by provider specialty, claim type, and submission method, alongside financial exposure.

### 3. Business Insights & Recommendations

![Business Insights and Recommendations](Dashboard%20Screenshot%203.png)

Summary of findings, limitations, and proposed business actions.

## 💡 Business Recommendations

1. **Investigate denials:** Review denied claims to determine whether documentation, eligibility, coding, or policy requirements contributed to the outcomes.
2. **Monitor pending claims:** Establish follow-up procedures and regularly review outstanding claims.
3. **Review financial exposure:** Assess denied claim values and investigate cases that may qualify for correction or appeal.
4. **Monitor performance:** Use recurring reports to track claims outcomes and changes in denial rates.
5. **Improve future analysis:** Capture denial reasons and processing times to support root-cause analysis.

## ⚠️ Limitations

- Detailed denial reasons are unavailable.
- Processing durations are not available.
- Observed patterns do not prove causation.
- July 2024 is a partial month.
- The original dataset source and licence should be verified before redistribution.

## 📁 Project Files

📊 **[View or download the Power BI dashboard](Health%20Insurance%20Claims%20Dashboard.pbix)**

📄 **[Read the project case study](Health_Insurance_Claims_Case_Study_Word.docx)**

🖼️ **[View dashboard screenshot 1](Dashboard%20Screenshot%201.png)** · **[View screenshot 2](Dashboard%20Screenshot%202.png)** · **[View screenshot 3](Dashboard%20Screenshot%203.png)**

## 👩‍💻 About the Author

**Odunayo Analytics**

Data Analytics | Healthcare Analytics | Insurance Claims Analysis
