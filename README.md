# Coffee-sales-Power-BI-dashboard-
I build power BI sales dashboard summarizing coffee shop performance across Mar–Jul 2024. The report shows total revenue of 37,508.88 across 366 transactions (avg sale 33.1). Lattes, Americanos with milk, and cappuccinos are the top revenue drivers. Card payments dominate at 91.5%, so card processing costs and promotions tied to card use should be
 
 Project “ask” (what client requested)
      Build a Power BI dashboard to track coffee shop sales across months, days, hours, product mix and            payment types so the client can:• Monitor total and average sales,• Identify best-selling drinks and revenue by day/hour,• Compare payment mix (card vs cash), and• Make product & staffing decisions based on peaks.(Outcome delivered: interactive Power BI report / dashboard expo).

Who solved each step-by-step (roles & tasks)
Project Manager Scoping & Client Communication
Collected requirements, agreed KPIs (Total Sales, Avg Sales, Transactions, Sales by month/day/hour, Product performance, Payment type).
Delivered acceptance criteria and timeline.
Data Engineer — Data Extraction & Ingestion
Extracted sales source files (CSV / database).
Consolidated monthly tables (Mar–Jul 2024) into a staging dataset.

3 Data Analyst — Data Cleaning & Transformation
Cleaned missing/duplicate rows, standardized coffee name, cash type, date, time, and transaction id.
Created a date/time dimension and derived fields (Month, Day Of Week, Hour).
Calculated measures needed (Total Sales, Transactions count, Avg Sales).
Sample validation before modeling

4 BI Developer (Power BI) — Data Modeling & Measures
Loaded transformed data into Power BI model.
Built relationships (sales → date/time dimension).
Implemented DAX measures:  Total Sales, Transactions, Avg Sales, %_Total By Product, etc.

5  BI Developer — Visual Design & Report Build
  Created visuals shown in the  cards (Total Sales, Transactions, Avg Sales), bar charts for Sales by Month, Sales by Coffee Name, heatmaps/times (Hour/Day), and pie/stacked visuals for payment mix.
Added slicers (coffee type, cash type, month).
Formatted for readability and client brand (if requested).

QA / Tester — Validation & Story Review
Cross-checked totals (e.g., aggregate model totals vs raw CSV sums).
Checked filters/slicers, tooltip correctness, and mobile layout.

4 BI Developer (Power BI) — Data Modeling & Measures
Loaded transformed data into Power BI model.
Built relationships (sales → date/time dimension).
Implemented DAX measures:  Total Sales, Transactions, Avg Sales, %_Total By Product, etc.

5  BI Developer — Visual Design & Report Build
  Created visuals shown in the  cards (Total Sales, Transactions, Avg Sales), bar charts for Sales by Month, Sales by Coffee Name, heatmaps/times (Hour/Day), and pie/stacked visuals for payment mix.
Added slicers (coffee type, cash type, month).
Formatted for readability and client brand (if requested).

QA / Tester — Validation & Story Review
Cross-checked totals (e.g., aggregate model totals vs raw CSV sums).
Key figures & insights (from the dashboard)
Total Sales (period shown): 37,508.88.
         Transactions: 366. 
        Average Sale:33.1
   Top products (by total sales):
              Latte: 9,009.14
              Americano with Milk: 8,601.94
             Cappuccino: 7,333.14
Sales by month (period totals shown): May-2024 → 9.1K, Jun-2024 → 7.8K, Mar-2024 → 7.1K, Jul-2024 → 6.9K, Apr-2024 → 6.7K (sum = 37,508.88).

Payment mix: Card = 91.51%, Cash = 8.49% of total sales.

 Hourly/daily patterns: Report contains total sales by hour and by day; peak sales hours and best day(s) are shown in the time analysis visuals (use when planning staffing). 






