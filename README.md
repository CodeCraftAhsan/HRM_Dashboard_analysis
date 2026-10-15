# HR Analytics & Workforce Intelligence Dashboard | Excel

<img width="1580" height="738" alt="HR dashboard" src="https://github.com/user-attachments/assets/09d7e554-539c-4aeb-bcad-bc68e0aceb3f" />


**An Excel-based HR analytics project that turns workforce records into an interactive dashboard for exploring headcount, compensation, employee status, and workforce distribution.**

**Tools:** Microsoft Excel · PivotTables · PivotCharts · Slicers · Data Aggregation · Dashboard Design

## Project Overview

This project analyzes **2,256 HR records** across four Bangladesh branches to help HR and management teams understand workforce composition, salary distribution, employee status, and staffing patterns. It combines an employee-level data table, supporting pivot calculations, and a visual dashboard within one Excel workbook.

The goal is to make important workforce metrics easier to explore and communicate to nontechnical stakeholders.

## Dashboard Preview

> Add a screenshot of the `Dashboard` worksheet here before publishing the repository, for example: `![HR Analytics Dashboard](images/hr-dashboard.png)`.

## Key Metrics

| Metric | Result |
|---|---:|
| HR records analyzed | 2,256 |
| Total recorded salary | 113,346,000 |
| Average recorded salary | 50,242 |
| Total recorded conveyance expense | 134,915,057 |
| Average conveyance expense | 59,803 |
| Active records | 1,617 (71.7%) |
| Records marked Left | 639 (28.3%) |
| Branches | 4 |
| Departments / functional units | 7 |

*Financial values are shown in the workbook's original units; no currency is assumed. Totals are summed across records, and should not be interpreted as annual payroll without additional context.*

## Analysis & Findings

### 1. Workforce distribution by branch

| Branch | Records | Share |
|---|---:|---:|
| Dhaka | 1,182 | 52.4% |
| Chattogram | 556 | 24.6% |
| Khulna | 343 | 15.2% |
| Rajshahi | 175 | 7.8% |

**Observation:** More than half of the records are associated with Dhaka. This concentration makes branch-level staffing comparisons especially relevant.

### 2. Employee status

- **Active:** 1,617 records (71.7%)
- **Left:** 639 records (28.3%)

**Observation:** Employee status can help describe the composition of the dataset. The percentage marked `Left` is **not a turnover rate**, because the workbook does not establish a defined turnover period or average headcount denominator.

### 3. Employment type

- **CT:** 1,200 records (53.2%)
- **FT:** 1,056 records (46.8%)

**Observation:** The dataset supports comparisons between the two employment-type codes. Their full business definitions should be confirmed before drawing policy conclusions.

### 4. Workforce age profile

| Age group | Records | Share |
|---|---:|---:|
| 25–34 | 629 | 27.9% |
| 35–44 | 621 | 27.5% |
| 45–54 | 630 | 27.9% |
| 55–65 | 376 | 16.7% |

**Observation:** Records are distributed fairly evenly across the three age bands from 25 to 54.

### 5. Department concentration

The largest functional units in the dataset are:

| Department | Records |
|---|---:|
| Medical Service: Nursing | 809 |
| Administration: Supply Chain | 524 |
| Administration: Logistic | 390 |
| Medical Service: Medical Support | 346 |

These categories can help teams prioritize deeper staffing and compensation reviews.

## Dashboard Features

- KPI summaries for salary, conveyance expenses, and employee records
- PivotTable-based calculations and comparisons
- Charts for employee trends, age profile, and top/bottom employee-level values
- Branch-level and workforce demographic breakdowns
- Excel slicers for interactive exploration
- Structured employee data maintained separately from the dashboard

## Workbook Structure

| Worksheet | Purpose |
|---|---|
| `HR_Data` | Employee-level source records, including branch, department, salary, age group, status, and employment type |
| `Pivot_calculation` | Aggregated KPIs and supporting summary calculations for charts |
| `Dashboard` | Main interactive visualization and management reporting view |

## Skills Demonstrated

**Data analysis:** Workforce segmentation, KPI calculation, aggregation, categorical comparison, and interpretation of business metrics.

**Excel:** Structured tables, PivotTables, PivotCharts, slicers, and management dashboard layout.

**Business communication:** Turning tabular HR data into concise observations that support workforce planning and further investigation.

## How to Explore the Project

1. Download `Dashboard_Hrm.xlsx` from this repository.
2. Open it in **Microsoft Excel desktop** for the best compatibility with the dashboard's interactive features.
3. Go to the `Dashboard` sheet to explore visuals and available slicers.
4. Review `Pivot_calculation` for the supporting summaries and `HR_Data` for the underlying data structure.

## Data Quality & Interpretation Notes

- The workbook contains **2,256 records**, but employee IDs are **not all unique**. Do not interpret record counts as distinct individuals without first resolving repeated IDs.
- Status proportions are descriptive, **not formally calculated attrition rates**.
- Historical joining years appear in the data; monthly joining counts do not necessarily represent current-period recruitment or active workforce trends.
- No currency label or payroll period has been assumed for salary and expense totals.
- The source includes potentially identifiable employee information. **Remove or anonymize names, email addresses, and employee IDs before uploading any workbook to a public repository**, and share only data you have permission to publish.

## Business Value

This dashboard demonstrates how Excel-based HR reporting can make it easier to:

- Compare workforce distribution across branches and departments
- Review compensation and expense patterns
- Identify segments that merit further HR investigation
- Present workforce information in a format accessible to managers

## Project Files

```text
HR-Analytics-Dashboard/
├── README.md
├── Dashboard_Hrm.xlsx
└── images/
    └── hr-dashboard.png   # Optional dashboard screenshot
```

*Portfolio project based on the supplied Excel workbook. Findings describe the available dataset and are not claims of measured business impact.*
