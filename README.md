# Commercial Sales & Territory Profitability Dashboard

![Executive Dashboard Demo](CommercialSalesPerformanceTerritoryMarginoptimization-Excel2026-09-2722-01-38-ezgif.com-speed%20(2).gif)

## Project Overview
An interactive executive reporting dashboard built in Microsoft Excel to evaluate regional sales performance, product profitability, and representative revenue contributions across multi-year cycles.

The dashboard integrates dynamic KPI tracking with real-time cross-filtering across geography, fiscal years, and product categories without breaking underlying calculations.

---

## Key Performance Indicators (Baseline)
* **Total Revenue:** $41,44,055.00
* **Total Profit:** $14,37,318.00
* **Profit Margin:** 34.68%
* **Total Quantity:** 10,895 units

---

## Core Visualizations & Analytics
* **Revenue & Profit by Territory:** Direct comparison of gross turnover against net margins across East, North, South, and West regions.
* **Sales by Product Category:** High-volume evaluation across Electronics, Furniture, and Office Supplies.
* **Monthly Revenue Trend:** Multi-year timeline tracking seasonal peaks and cyclical fluctuations.
* **Revenue by Sales Representative:** Rep performance rankings highlighting revenue leaders (Joran, Taylor, Sam, Morgan, Alex).

---

## Architecture & Data Flow
The workbook follows a standard four-tier analytical architecture:
1. `Raw Data`: Source transaction logging and granular attributes.
2. `Cleaned Data`: Standardized date hierarchies, formatted currency fields, and validated categorical entries.
3. `Pivot Analysis`: Decoupled aggregation layers powering chart series and slicer pipelines.
4. `Executive Dashboard`: Polished visualization interface designed with zero grid clutter and locked slicer layouts.

---

## Technical Features Demonstrated
* Dynamic PivotTables and cross-filtering Pivot Slicers.
* Multi-axis chart design and custom numeric formatting.
* Data integrity pipelines separating raw ingestion from analytical presentation.
