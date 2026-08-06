
# Telco Customer Churn Analysis

AnalystLab Africa Data Analytics Internship (Batch C) — Excel task.

## Overview
This project analyzes customer churn from the IBM Telco Customer Churn dataset (7,043 customers) to identify which contract types are most at risk of losing customers.

## Dataset
- **Source:** WA_Fn-UseC_-Telco-Customer-Churn.csv
- **Rows:** 7,043 customers
- **Key fields used:** Contract type, Churn status

## Method
- Built a pivot table summarizing churn rate by contract type in Excel
- Created a bar chart to visualize the comparison
- Calculated churn rate as (customers who churned) / (total customers) per contract type

## Key Findings
| Contract Type | Customers | Churn Rate |
|---|---|---|
| Month-to-month | 3,875 | ~43% |
| One year | 1,473 | ~11% |
| Two year | 1,695 | ~3% |

**Insight:** Month-to-month customers churn at roughly 14x the rate of two-year contract customers. This suggests that longer-term contracts (or incentives to move customers toward them) could be a strong lever for reducing churn.

## Tools
Excel (Pivot Tables, Charts)

## Files
- `Telco_Churn_Analysis.xlsx` — pivot table and chart

---
*Part of the AnalystLab Africa Data Analytics Internship, Batch C*
#AnalystLabAfrica
