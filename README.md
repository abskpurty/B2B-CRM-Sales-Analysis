# B2B-CRM-Sales-Analysis

About the data:
The dataset represents B2B sales pipeline data for a fictional computer hardware company. It captures detailed information on sales opportunities, including revenue, deal stage, product involved, and close dates. The dataset is supported by metadata on client accounts, products and sales teams. The dataset (CRM Sales Opportunities) was downloaded from the website of Maven Analytics.

Overview of approach:
1. Built an interactive Power BI dashboard to visualize key sales performance KPIs, including Revenue, Win Rate, Sales Cycle Length, and Sales Velocity. The dashboard supports dynamic metric selection and features visuals that update based on slicers and cross-filtering between charts.
2. Created parameter-based slicers and custom measures to calculate KPIs and apply conditional formatting.
3. Used DAX functions such as SWITCH, SELECTEDVALUE, CALCULATE, VALUES, MAXX, and ALLSELECTED to build dynamic and context-aware calculations.
4.  Implemented abbreviation DAX logic for cleaner number formatting (e.g., K for thousand, M for million) and applied appropriate suffixes based on metric type.
5.  Used Power Query to add missing dates through scaffolding, perform table joins, and correct misspelled field names for consistent and accurate reporting.

Insights:
1. GTX Pro emerges as the standout product, generating the highest revenue and closing deals quickly, while MG Special, despite a slightly stronger win rate, lags in overall contribution.
2. Regionally, the USA dominates in revenue, whereas China leads in win rate, suggesting market differences in scale versus efficiency.
3. Sales are strongest in the retail and marketing sectors, and top-performing managers like Melvin Marxen and Cara Losch demonstrate both volume and effectiveness.
4. Win rate does not vary much accross products, managers and sectors. 
