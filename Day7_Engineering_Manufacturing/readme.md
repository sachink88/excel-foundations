\# Day 7: Engineering \& Manufacturing Inventory Analysis



\## Overview

This folder contains the Day 7 task for the `excel-foundations` project, focusing on inventory analysis using the \*\*Engineering and Manufacturing Sample Data\*\* dataset. The goal is to demonstrate Excel skills in data analysis, visualization, and automation for manufacturing inventory management.



\## Dataset

\- \*\*File\*\*: `Engineering-and-Manufacturing-Sample-Data.xlsx`

\- \*\*Description\*\*: Contains 31 products with columns: Product ID, Name, Category (Electronics/Mechanical), Manufacturer, Price (USD), and Stock Quantity.

\- \*\*Total Inventory Value\*\*: $3,284.25

\- \*\*Categories\*\*: Electronics (39%), Mechanical (61%)



\## Tasks Completed

1\. \*\*PivotTable Analysis\*\*:

&nbsp;  - Summarized inventory value by category: Electronics ($1,284.25), Mechanical ($2,000).

&nbsp;  - Identified top 5 expensive items (e.g., Gearbox G300: $200).

2\. \*\*Charts\*\*:

&nbsp;  - Pie Chart: Category distribution.

&nbsp;  - Bar Chart: Top manufacturers by inventory value (GearTech: $780).

&nbsp;  - Line Chart: Price vs. Stock distribution.

3\. \*\*Formulas\*\*:

&nbsp;  - Total Inventory Value: `=SUMPRODUCT(E2:E32,F2:F32)` = $3,284.25

&nbsp;  - Average Price by Category: `=AVERAGEIF(C2:C32,"Electronics",E2:E32)` = $14.18

&nbsp;  - Low Stock Alerts: Conditional formatting for stock < 200 (Red), < 400 (Yellow).

4\. \*\*VLOOKUP \& Data Validation\*\*:

&nbsp;  - Product lookup by ID: `=VLOOKUP(A1,$B$2:$G$32,2,FALSE)`.

&nbsp;  - Dropdown filters for Category and Manufacturer.

5\. \*\*Dashboard\*\*:

&nbsp;  - Created `Analysis\_Dashboard.xlsx` with interactive charts and filters.

&nbsp;  - Screenshot: `inventory\_summary.png`.



\## Files

\- `Engineering-and-Manufacturing-Sample-Data.xlsx`: Raw dataset.

\- `Analysis\_Dashboard.xlsx`: Excel file with PivotTables, charts, and formulas.

\- `inventory\_summary.png`: Screenshot of the dashboard.



\## Tools Used

\- Microsoft Excel (PivotTables, Charts, VLOOKUP, Conditional Formatting, SUMPRODUCT)

\- GitHub for version control



\## Purpose

This task showcases skills in:

\- Inventory data analysis for manufacturing.

\- Advanced Excel functions for data insights.

\- Visualization for stakeholder reporting.

\- GitHub portfolio development for data analyst roles.



\## Next Steps

\- Day 8: NYC Taxi Dataset - Power Query and dynamic dashboard.

