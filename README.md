# Nashville Housing Data Cleaning (SQL)

This project focuses on cleaning and transforming raw housing data with SQL.  
Key steps: standardizing dates, filling null property addresses, splitting fields into components, standardizing categorical values, removing duplicates, and dropping irrelevant columns.

## Example Query

```sql
-- Standardize SaleDate format
UPDATE NashvilleHousing
SET SaleDate = CAST(SaleDate AS DATE);
```
