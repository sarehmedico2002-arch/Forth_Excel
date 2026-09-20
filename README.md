# Forth_Excel
# Crystal Pools Sales Analysis

An Excel workbook analyzing a year of sales transactions for a pool supply company, including commission calculations, summary totals, and a pivot table breakdown by salesperson.

## File

- `CrystalPools.xlsx`

## Techniques used

- **Text to Columns**: used to split and clean imported transaction data
- **Sort**: transaction records sorted for easier analysis
- **Filter**: used to narrow down and inspect subsets of the data
- **IF**: calculates commission per transaction — 20% of profit for items sold over $50, 10% for items $50 or under
- **SUMIF**: totals sale price for items above $50 and items $50 or under
- **Pie Chart**: visualizes a breakdown of the sales data
- **Pivot Table**: summarizes total sale price by salesperson (Sheet2), with a grand total

## Columns

- Month, Transaction Number, Product Code, Product Description, Store Cost, Sale Price, Profit, Commission, First Name, Last Name, Sale Location
