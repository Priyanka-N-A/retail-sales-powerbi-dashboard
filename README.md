# Retail Sales Performance Dashboard

## Overview
End-to-end data analytics project analyzing retail sales transactions to uncover revenue trends, customer behavior, product performance, and delivery insights.

**Tools:** Microsoft Excel | Power BI Desktop | GitHub

---

## Dataset
- **Source:** Sales Transactions Dataset
- **Records:** [2501] transactions
- **Columns:** 19 (transaction_id, customer info, 
  product, pricing, payment, delivery, returns, ratings)
- **Period:** [01-03-2026] to [04-04-2026]

---

## Data Cleaning (Excel)
- Removed duplicate transaction IDs
- Fixed date format inconsistencies in transaction_date
- Standardized text values in category, payment_method,
  delivery_status using PROPER() function
- Filled blank return_requested and coupon_used 
  with "No" (logical default)
- Added 6 helper columns: Year, Month_Name, Month_Num,
  Day_of_Week, Rating_Band, Issue_Flag

---

## Dashboard Pages

### Page 1 — Sales Overview
- Total Revenue, Orders, Avg Order Value, Avg Rating (KPIs)
- Monthly revenue trend by year (line chart)
- Revenue by product category (donut chart)
- Top performing store locations (bar chart)

---

## Key Insights
- [Category X] generates [X]% of total revenue
- Return rate is highest in [category] at [X]%
- [Customer segment] has the highest avg order value
- [Payment method] is preferred by [X]% of customers
- Revenue peaks in [month] each year

---

## Dashboard Preview
![Sales Overview]("C:\Users\Priyanka N A\Downloads\archive (1)\Screenshot 2026-04-04 181317.png")

---

## Files
| File | Description |
| data/sales_data_cleaned.xlsx | Cleaned dataset |
| dashboard/sales_dashboard.pbix | Power BI dashboard |
