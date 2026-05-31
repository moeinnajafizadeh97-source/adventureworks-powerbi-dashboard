# AdventureWorks Sales & Operations Dashboard (Power BI)

## Overview
A 10-page interactive Power BI dashboard built on the AdventureWorks dataset,
covering sales, finance, HR, and product operations across 6 countries (2011–2014).

## Dashboard Pages
1. **Introduction** — Navigation homepage with page shortcuts
2. **Accounts Information** — Hierarchical account display with 7 account types
3. **Percent of Profit** — Profit trends over time and by country (42%–46% range)
4. **Order Quantity by Category** — Time series across Bikes, Accessories, Clothing
5. **Sales by Category** — Treemap showing product hierarchy and subcategory volumes
6. **Sales Scatter Chart** — Order quantity vs sales amount by city across 6 countries
7. **Sales Map** — Geographic pie charts showing sales distribution by region (2011–2014)
8. **Customer Information** — Demographics by age, gender, birth month, purchase behaviour
9. **Customer Income Analysis** — Average income by age/gender, yearly income distribution
10. **Employee Information** — 296 employees across departments, reseller sales vs $95.71M quota

## Key Metrics
- Total reseller sales: $80.45M (against $95.71M quota)
- 6 countries: Australia, Canada, France, Germany, UK, United States
- 296 employees across 11 departments
- US highest profit margin: 53.95%
- Road Bikes top product: 39K units sold

## Technical Details
- 20+ table star schema data model
- DAX measures for profit margins, sales quotas, and reseller performance
- Power Query (M) transformations and custom calculated columns
- Age partitioning and gender-based segmentation via DAX
- Geographic map visuals, treemaps, scatter charts, and cross-filtering
- Navigation homepage with page shortcuts

## Files
- `AdventureWorks_PowerBi.pbix` — Power BI project file (open with Power BI Desktop)
- `AdventureWorks_PowerBi.pdf` — PDF export of all dashboard pages

## Tech Stack
- Power BI Desktop
- DAX (Data Analysis Expressions)
- Power Query (M)
- AdventureWorks Dataset
