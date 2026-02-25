# Sales Dashboard (Power BI)

This repo is a **portfolio-ready template** for a Sales Dashboard in Power BI.

## What to upload here
- `Sales_Dashboard.pbix` (your Power BI file)
- 2–3 screenshots in `/assets` (PNG/JPG)
- (optional) A short demo video/GIF in `/assets`

## Dashboard pages (recommended)
### Page 1 — Overview
- KPI cards: Total Sales, Total Profit, Profit Margin %, Orders, AOV
- Line chart: Sales by Month
- Bar chart: Sales by Category/Sub-Category
- Slicers: Date, Region, Category

### Page 2 — Customers / Segments
- Top 10 customers by sales
- Segment filter
- Scatter: Sales vs Profit (color by segment)

## Recommended DAX measures (copy/paste)
```DAX
Total Sales = SUM(Orders[Sales])
Total Profit = SUM(Orders[Profit])
Profit Margin % = DIVIDE([Total Profit], [Total Sales])
Orders = DISTINCTCOUNT(Orders[Order ID])
AOV = DIVIDE([Total Sales], [Orders])
```

## Data
Use any public sales dataset (example: Superstore-style dataset) with columns like:
- Order Date, Order ID, Customer, Segment, Region, Category, Sub-Category, Sales, Profit

## Portfolio highlights (paste into your portfolio)
- Built interactive KPI dashboard in Power BI with drill-down and slicers.
- Designed DAX measures for sales, profit, margin, and AOV.
- Delivered insights on top categories, seasonal trends, and customer segments.
