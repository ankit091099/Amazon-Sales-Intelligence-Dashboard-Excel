# Amazon Intelligence Dashboard (Excel)

## Overview
An Excel dashboard built from 100 raw Amazon sales transactions across multiple regions, products and customer profiles. It shows how products and regions perform and helps explore customer trends and fulfillment efficiency.

## Objectives
- Clean and standardize raw sales data
- Use XLOOKUP to connect customer details
- Summarize revenue, fulfillment and cancellations with Pivot Tables
- Build an interactive dashboard with slicers and KPI cards

## Tools & Techniques
- Pivot Tables and Pivot Charts
- Functions: SUM, COUNT, AVERAGE, IF, TEXT, IFERROR
- XLOOKUP (Customer ID → Customer Name from a Customer Master sheet)
- Date grouping, filters and custom columns
- Conditional formatting and slicers

## Project Steps
1. **Data cleaning:** fixed date formats, removed extra spaces and blanks, standardized Region, Payment Method and Delivery Status, tagged cancelled orders.
2. **Pivot Tables:** total sales by Region and Product Category, order count by Delivery Status, average delivery time, filters for Payment Method and Category.
3. **XLOOKUP and calculated columns:** customer name lookup and a Delivery Performance column (Fast / Slow) using IF and IFERROR.
4. **KPIs:** cancellation rate by region, effective sales (delivered orders only), total revenue, % of fast deliveries, top 3 regions, highest-selling product.
5. **Dashboard design:** slicers on the left, pivot charts in the center, KPI cards on the right, with a month filter.

## Files
| File | Description |
|------|-------------|
| `My_Excel_Mini_Project.xlsx` | Excel workbook with data, pivots and dashboard |
| `My_Excel_Mini-Project.pdf` | PDF presentation of the project |
| `My_Excel_Mini-Project.pptx` | PowerPoint presentation |

## Key Insights
(Add 3 to 4 findings from your dashboard here, for example: top region by revenue, % of fast deliveries, cancellation rate.)

## Dashboard Preview
![Dashboard](dashboard.png)
