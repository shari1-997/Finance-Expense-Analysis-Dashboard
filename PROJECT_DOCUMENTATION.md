# Project Documentation — Finance & Expense Analysis Dashboard

## 1. Objective

Build an end-to-end Excel financial analysis solution that converts raw transaction data into a cleaned analytical dataset, KPI summary, PivotTable analysis, and interactive dashboard.

## 2. Analytical Scope

The workbook covers:

- Revenue
- Expenses
- Budget
- Actual amounts
- Variance
- Budget status
- Net amount
- Departments
- Categories
- Business segments
- Payment methods
- Monthly trends

## 3. Dataset

The raw workbook contains **2,530 data records** before cleaning, including **30 exact duplicate rows**. After the documented cleaning process, the analytical dataset contains **2,500 transactions**.

The cleaned data spans January 2025 through June 2026 based on the transaction-month analysis.

## 4. Data Quality Review

Documented issues:

- 30 exact duplicate rows
- 15 missing departments
- 12 missing vendors
- 18 missing payment methods
- 10 missing categories
- 17 inconsistent text/capitalization values
- 12 mixed date formats
- 8 blank budget amounts
- 6 missing actual amounts
- 4 zero actual amounts

The project's Data Quality Plan records the issue count, recommended action, and reason for each issue type.

## 5. Calculated Fields

### Variance

The workbook contains a `Variance` field for budget-vs-actual analysis.

### Variance %

The workbook contains a `Variance %` field for relative budget variance analysis.

### Budget Status

Transactions are grouped into:

- No Budget
- Over Budget
- Under Budget

### Net Amount

The cleaned data uses the `Net Amount` field to represent the financial direction of transactions. Revenue contributes positively and expenses negatively.

### Transaction Month

A normalized month field supports monthly PivotTable and dashboard analysis.

## 6. KPI Results

| KPI | Result |
|---|---:|
| Total Transactions | 2,500 |
| Total Budget | $17,105,049.21 |
| Total Actual | $16,270,074.79 |
| Total Revenue | $8,199,267.79 |
| Total Expenses | $8,070,807.00 |
| Net Amount | $128,460.79 |
| Over Budget Amount | $11,251,287.72 |
| Under Budget Amount | $4,970,810.27 |

## 7. PivotTable Analysis

The final workbook includes analysis for:

- Revenue vs Expense by Month
- Expense by Category
- Actual vs Budget by Department
- Revenue by Category
- Net Amount by Business Segment
- Budget Status
- Actual Amount by Payment Method
- Revenue by Business Segment

## 8. Dashboard

The dashboard combines KPI cards, slicers, and charts into one financial overview.

### Slicers

- Transaction Month
- Department

### KPI Cards

- Total Transactions
- Total Budget
- Total Actual
- Net Amount
- Total Revenue
- Total Expenses
- Over Budget
- Under Budget

### Charts

- Monthly Revenue vs Expenses
- Expense by Category
- Actual vs Budget by Department
- Net Amount by Business Segment
- Actual Amount by Budget Status
- Revenue by Category
- Actual Amount by Payment Method
- Revenue by Business Segment

## 9. Business Insights

- Total revenue is approximately $8.20M and total expenses are approximately $8.07M.
- Net amount is $128,460.79.
- Product Sales is the largest revenue category at approximately $5.22M.
- Salaries & Benefits is the largest expense category at approximately $3.62M.
- Sales has the largest department-level budget and actual amount in the PivotTable.
- Online has the largest positive net amount among the business segments shown in the Net Amount analysis.
- Bank Transfer has the largest actual amount among the payment methods shown.

## 10. Online Excel View

[Open the dashboard in Excel for the web](https://1drv.ms/x/c/af2c5b27416c24d1/IQA4yMC_uk6GRY28I3Aj4krGASdLTOmo3L1qEoBbyEsTDRg)

## 11. Portfolio Deliverable

This project demonstrates an applied Excel workflow from raw data through cleaning, analysis, visualization, and business reporting.
