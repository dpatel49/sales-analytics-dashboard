# Brazilian E-Commerce Sales Analytics Dashboard

## Project Overview
End-to-end sales analytics dashboard built on the 
Olist Brazilian E-Commerce dataset (96,478 orders, 
R$15.84M revenue). Includes Power BI dashboard, 
Tableau visualizations, Excel pivot reports and 
AI-powered revenue forecasting.

---

## Tools & Technologies
| Tool | Purpose |
|------|---------|
| Power BI | Main dashboard & AI forecasting |
| Tableau Public | Secondary visualization |
| Excel | Pivot tables & KPI reports |
| DAX | Calculated measures & columns |
| Claude AI | Business insights & reports |

---

## Dataset
- **Source:** Olist Brazilian E-Commerce (Kaggle)
- **Size:** 96,478 orders | 9 CSV files
- **Period:** January 2017 – August 2018
- **Tables used:** Orders, Order Items, Products,
  Customers, Payments, Category Translation

---

## Dashboard Pages

### Page 1 — Revenue Overview
- Total Revenue: R$15.84M
- Total Orders: 96,478
- Average Order Value: R$140.64
- Monthly revenue bar chart
- Revenue trend line chart
- Date range slicer

### Page 2 — Product & Category Analysis
- Top 10 categories treemap (English names)
- Revenue by category bar chart
- State slicer for filtering

### Page 3 — AI Forecast
- 6-month revenue forecast
- 95% confidence interval
- Seasonal pattern analysis
- Built using Power BI Analytics pane

### Page 4 — Logistics & Delivery Map
- Brazil state map with revenue bubbles
- Average delivery days by state
- Late delivery count KPI
- Top states with worst delivery time

### Page 5 — Executive Summary
- MoM Revenue Growth %
- Late Delivery Rate %
- Top performing state
- Top product category
- Business recommendations

---

## Tableau Dashboard
3 interactive worksheets:
- Revenue by Month (bar chart)
- Top 10 Categories (horizontal bar)
- Freight vs Price (scatter plot — 98,666 data points)

---

## Excel Report
4 sheets:
- Raw Data (112,650 rows)
- Monthly Revenue pivot table
- Top Categories pivot table  
- Freight Analysis pivot table
- Logistics KPIs summary sheet

---

## Key Business Findings

1. **Revenue Growth:** R$15.84M total revenue with 
   10x growth from Jan 2017 to Jan 2018 peak

2. **Top Category:** Health & beauty is #1 revenue 
   driver followed by watches & gifts

3. **Delivery Crisis:** Northern states (RR, AP, AM) 
   show 25-30 day delivery times vs 10 days in SP

4. **Seasonality:** Strong Q4 revenue spike every year.
   January records highest monthly revenue consistently

5. **Geography:** 70% revenue concentrated in SP, RJ, MG.
   Northern Brazil is untapped market opportunity

---

## Business Recommendations

### For Project Managers
- Invest in northern Brazil logistics infrastructure
- Double health & beauty inventory before Q4
- Target: reduce late deliveries by 40%

### For Logistics Analysts  
- Partner with local couriers in RR, AP, AM states
- Open regional distribution center in Manaus
- Implement real-time delivery tracking

### For Business Leadership
- Launch marketing in underserved northern states
- Focus product expansion on top 3 categories
- Use seasonal forecast for Q4 budget planning

---

## Project Structure
sales-analytics-dashboard/
│
├── sales_dashboard.pbix          ← Power BI file
├── sales_summary.xlsx            ← Excel report
├── Sales_Dashboard_Presentation  ← PowerPoint slides
├── README.md                     ← This file
│
└── screenshots/
├── page1_revenue_overview.png
├── page2_category_analysis.png
├── page3_ai_forecast.png
├── page4_logistics_map.png
├── page5_executive_summary.png
└── tableau_dashboard.png
