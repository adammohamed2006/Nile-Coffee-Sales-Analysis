# Nile Coffee | Sales Analysis and Demand Forecasting

An Excel-based analysis of monthly sales and demand forecasting for three coffee products: **Nile Espresso**, **Cairo House Blend**, and **Nile Cold Brew**.

## Project overview

This workbook combines a monthly product dataset, PivotTables, a dashboard, and demand forecasting calculations. It was developed as an academic data analysis project to explore product sales patterns and compare forecasting approaches.

## Tools and methods

- Microsoft Excel
- PivotTables and dashboard charts
- `SUMIFS` and spreadsheet formulas
- Simple moving averages
- Linear trend forecasting
- Comparison against previous company forecasts

## Workbook structure

| Worksheet | Purpose |
| --- | --- |
| `Raw_Dataset` | Monthly product-level sales, forecasts, defects, labour, capacity, costs and prices |
| `PivotTables` | Summaries of actual monthly sales across products |
| `Dashboard` | Visual analysis of sales and related business metrics |
| `Demand Forecasting` | Product-specific moving-average and linear-trend calculations, six-month outlooks, and forecast comparisons |

## Questions explored

1. How do actual monthly sales differ across the three products?
2. What sales patterns are visible over the observed months?
3. What demand levels do moving-average and linear-trend methods forecast?
4. How do these forecasts compare with the previous company forecasts?

## How to view the project

1. Download `Nile_coffee_dataset.xlsx` from this repository.
2. Open it in Microsoft Excel for the best support for PivotTables and embedded charts.
3. Start with the `Dashboard` sheet, then explore `PivotTables` and `Demand Forecasting`.

## Dashboard preview

Add a screenshot to `images/dashboard.png` and then uncomment this line:

<!-- ![Nile Coffee sales dashboard](images/dashboard.png) -->

## Notes

- This is an academic portfolio project, not a claim of employment by a company named Nile Coffee.
- The workbook includes a field labeled `Profit` that calculates *selling price minus production cost per unit*; it should not be interpreted as total period profit without adjusting for sales quantities and other costs.
- Excel may need to refresh PivotTables or recalculate formulas when opened in a new environment.
