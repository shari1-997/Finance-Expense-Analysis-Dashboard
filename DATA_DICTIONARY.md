# Data Dictionary

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

The cleaned workbook additionally contains:

| Field | Purpose |
|---|---|
| Variance | Budget-versus-actual difference |
| Variance % | Relative variance measure |
| Budget Status | No Budget / Over Budget / Under Budget |
| Net Amount | Financial direction used for the net financial view |
| Transaction Month | Normalized month for time-based analysis |
