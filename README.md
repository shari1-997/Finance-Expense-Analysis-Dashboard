# Finance & Expense Analysis Dashboard

## Budget Performance, Revenue, Expenses & Financial Overview

An end-to-end Microsoft Excel finance analytics project built from raw financial transactions through data quality review, cleaning, calculated metrics, PivotTables, KPI reporting, interactive slicers, and a presentation-ready dashboard.

![Dashboard Preview](Finance_Expense_Analysis_Dashboard_Preview.png)

## Project Overview

This project analyzes **2,500 cleaned financial transactions** covering revenue and expense activity. It focuses on:

- Budget vs. actual performance
- Revenue and expense trends
- Department-level financial performance
- Expense category analysis
- Business segment analysis
- Budget status
- Payment method analysis
- Revenue by category and business segment
- Interactive dashboard filtering

### Workflow

**Raw Financial Data → Data Quality Review → Data Cleaning → Calculated Metrics → PivotTables → KPI Summary → Interactive Dashboard → Business Insights**

## Key KPIs

| KPI | Value |
|---|---:|
| Total Transactions | 2,500 |
| Total Budget | $17,105,049.21 |
| Total Actual | $16,270,074.79 |
| Total Revenue | $8,199,267.79 |
| Total Expenses | $8,070,807.00 |
| Net Amount | $128,460.79 |
| Over Budget Amount* | $11,251,287.72 |
| Under Budget Amount* | $4,970,810.27 |

\* These are the total actual amounts associated with transactions classified by the workbook as **Over Budget** or **Under Budget**.

## Dashboard Features

The final dashboard contains:

1. **Monthly Revenue vs Expenses**
2. **Expense by Category**
3. **Actual vs Budget by Department**
4. **Net Amount by Business Segment**
5. **Actual Amount by Budget Status**
6. **Revenue by Category**
7. **Actual Amount by Payment Method**
8. **Revenue by Business Segment**

Interactive controls:

- **Transaction Month slicer**
- **Department slicer**
- KPI cards connected to the dashboard filtering
- PivotCharts connected to the underlying PivotTables

## Data Quality & Cleaning

The raw workbook contains intentional data-quality issues for portfolio demonstration and analysis practice.

| Issue | Count |
|---|---:|
| Exact duplicate rows | 30 |
| Missing Department | 15 |
| Missing Vendor | 12 |
| Missing Payment Method | 18 |
| Missing Category | 10 |
| Inconsistent text / capitalization | 17 |
| Mixed date formats | 12 |
| Blank Budget Amount | 8 |
| Missing Actual Amount | 6 |
| Zero Actual Amount | 4 |

The cleaning workflow addresses duplicate records, missing fields, inconsistent text, date normalization, and financial-field validation before analysis.

## Calculated Metrics

The cleaned workbook contains calculated fields including:

- **Variance**
- **Variance %**
- **Budget Status**
- **Net Amount**
- **Transaction Month**

The `Net Amount` field supports the overall financial view by representing revenue positively and expenses negatively in the cleaned dataset.

## Key Business Insights

### Revenue and Expense Mix

Total revenue is **$8.20M**, while total expenses are **$8.07M**, resulting in a positive **Net Amount of $128,460.79**.

### Revenue Composition

**Product Sales** is the largest revenue category at approximately **$5.22M**, followed by **Service Revenue** at approximately **$2.10M**.

### Expense Composition

**Salaries & Benefits** is the largest expense category at approximately **$3.62M**, followed by **Rent & Facilities** at approximately **$1.21M**.

### Department Performance

The **Sales** department has the highest recorded budget and actual amount in the department PivotTable, with approximately **$4.41M budget** and **$4.40M actual**.

### Business Segment Net Amount

The business-segment analysis shows positive net amounts for **Online** and **Services**, while **Corporate, Retail, and Wholesale** have negative net amounts in the workbook's Net Amount analysis.

### Payment Methods

**Bank Transfer** has the highest recorded actual amount among the payment methods shown in the dashboard.

## Workbook Structure

### `Finance_Expense_Analysis_Clean_Data.xlsx`

Contains:

- `Clean Financial Data`
- `Dashboard`
- `PivotTables`
- `KPI Summary`
- `Data Quality Plan`

### `Finance_Expense_Raw_Data.xlsx`

Contains:

- `Raw Financial Data`
- `Data Quality Plan`
- `Data Dictionary`

## Data Dictionary

| Field | Description | Data Type |
|---|---|---|
| Transaction ID | Unique transaction identifier | Text |
| Transaction Date | Date of financial transaction | Date |
| Transaction Type | Revenue or Expense | Text |
| Department | Responsible department | Text |
| Category | Revenue or expense category | Text |
| Business Segment | Business segment | Text |
| Location | Business/transaction location | Text |
| Vendor | Supplier or counterparty | Text |
| Payment Method | Payment method used | Text |
| Budget Amount | Allocated budget for the transaction's category/month | Currency |
| Actual Amount | Actual transaction amount | Currency |

## View the Excel Dashboard Online

You can open the Excel workbook in Excel for the web here:

**[View Finance & Expense Analysis Dashboard Online](https://1drv.ms/x/c/af2c5b27416c24d1/IQA4yMC_uk6GRY28I3Aj4krGASdLTOmo3L1qEoBbyEsTDRg)**

## How to Use

1. Download and open `Finance_Expense_Analysis_Clean_Data.xlsx`.
2. Go to the **Dashboard** sheet.
3. Use the **Transaction Month** slicer to filter the reporting period.
4. Use the **Department** slicer to filter departmental results.
5. Review the KPI cards and PivotCharts after filtering.
6. Use `Raw Financial Data` from the separate raw workbook when reviewing the original source records.

## Portfolio Purpose

This project demonstrates practical Excel skills for data analysis and business reporting, including:

- Data cleaning
- Data validation
- Excel formulas
- Date normalization
- Variance analysis
- Budget analysis
- PivotTables
- PivotCharts
- KPI reporting
- Slicers
- Dashboard design
- Business insights
- Financial data analysis

## Files

- `Finance_Expense_Analysis_Clean_Data.xlsx` — cleaned analysis workbook and final dashboard
- `Finance_Expense_Raw_Data.xlsx` — original raw dataset, data quality plan, and data dictionary
- `Finance_Expense_Analysis_Dashboard_Preview.png` — dashboard preview image
- `PROJECT_DOCUMENTATION.md` — detailed project documentation
- `DATA_DICTIONARY.md` — field definitions
- `DATA_QUALITY.md` — documented data-quality issues
- `BUSINESS_INSIGHTS.md` — dashboard insights
- `LICENSE` — MIT License
- `CONTRIBUTING.md` — contribution guidelines
- `CODE_OF_CONDUCT.md` — community standards
- `SECURITY.md` — security/reporting guidance

## Dataset Note

The dataset is a **fictional portfolio dataset** created for demonstration, analysis practice, and dashboard development. It does not represent real company financial records.

## License

This project is released under the MIT License. See `LICENSE` for details.
