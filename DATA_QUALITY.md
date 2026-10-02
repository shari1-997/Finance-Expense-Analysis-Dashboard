# Data Quality Documentation

The raw dataset intentionally contains data-quality issues so the project demonstrates a realistic cleaning workflow.

| Issue | Count | Recommended Action | Reason |
|---|---:|---|---|
| Exact duplicate rows | 30 | Remove duplicates | Duplicate transaction records |
| Missing Department | 15 | Recover / validate | Required for departmental analysis |
| Missing Vendor | 12 | Recover / standardize | Required for vendor analysis |
| Missing Payment Method | 18 | Standardize / use Unknown if unrecoverable | Payment analysis field |
| Missing Category | 10 | Recover using transaction type / mapping | Required for category analysis |
| Inconsistent text / capitalization | 17 | Standardize text | Consistent PivotTable grouping |
| Mixed date formats | 12 | Convert to real Excel dates | Consistent time analysis |
| Blank Budget Amount | 8 | Recover from category/month budget logic | Budget variance analysis |
| Missing Actual Amount | 6 | Flag/remove | Actual amount is required |
| Zero Actual Amount | 4 | Flag/remove | No financial activity |

## Cleaned Dataset

The raw workbook contains 2,530 data records before cleaning, including 30 exact duplicates. The cleaned analytical workbook contains 2,500 transactions.

## Quality Objective

The goal is to ensure that the final dataset supports consistent:

- PivotTable grouping
- Budget analysis
- Revenue/expense analysis
- Monthly reporting
- Department analysis
- Dashboard filtering
