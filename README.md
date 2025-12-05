# Excel-Logic-Engine-Sales-Analysis
Automating sales categorization and decision logic using nested IF, AND, OR, and SWITCH functions.
# Superstore Sales Logic Engine 📊

## Project Overview
This project transforms raw retail sales data into actionable business intelligence by automating decision-making logic. Using advanced Excel logical functions, I created a dynamic system to flag profitability, categorize shipping urgency, and identify high-value orders automatically.

## Key Features & Logic Implemented
* **Profitability Analysis:** Automated P&L flagging using `IF` to separate "Profitable" orders from "Losses."
* **Regional Segmentation:** Created a "Zone Type" (Coastal vs. Inland) using `IF` + `OR` logic to group geographic data.
* **High-Value Order Identification:** Built a "Super Order" flag using `IF` + `AND` to isolate transactions with Sales > $500 and Profit > $50.
* **Logistics Automation:** Categorized handling requirements ("Heavy", "Fragile", "Light") based on product category using `SWITCH`.

## Business Insights
* **Coastal Dominance:** Analysis revealed that Coastal regions account for ~54% of "Super Orders" (202 vs 173), suggesting higher value customers are concentrated in East/West zones.

## Tools Used
* Microsoft Excel (Logical Functions, Structured References, Data Cleaning)
