# Project Report: SCM - Procurement Dashboard 2024

## 1. Project Overview
This project focuses on developing a Supply Chain Management (SCM) Procurement Dashboard for the year 2024. The dashboard provides actionable insights into procurement operations, allowing for efficient tracking of purchase quantities, amounts, inventory movement, vendor performance, and overall procurement trends across the year.

The project is designed to help procurement and supply chain managers make data-driven decisions and monitor procurement KPIs in real-time.

## 2. Objectives
Track the procurement process, including pending and received purchase orders (POs).

Analyze procurement trends by month, item, vendor, and purchase status.

Optimize inventory levels and ensure accurate monitoring of stock movements.

Facilitate vendor performance analysis based on purchase quantities and amounts.

Visualize key metrics in an interactive dashboard to improve decision-making.

## 3. Data Sources
Procurement Data Table: Containing columns such as PO Date, Item, Vendor, Status (Pending/Received), Inventory In, Inventory Out, and Balance.

Date Table: Used to create temporal filters (Month, Year, Day of the Week).

## 4. Dashboard Components
### A. KPIs (Top Row Cards)
Pending Quantity: 671,295 units are currently pending.

Received Quantity: 655,121 units have been received.

Total Quantity: Combined total of 1,326,416 units.

Pending %: 50.61% of total quantity is still pending.

Total Items: 4 distinct items are being tracked.

Total Vendors: 10 vendors are engaged in procurement.

### B. Filters (Slicers)
Month Selector: Filter data by month (January, February).

Product Selector: Choose from Item-1 to Item-4.

Vendor Selector: Select specific vendors (Vendor-8, Vendor-9).

Status Selector: Filter by procurement status (Pending or Received).

### C. Visuals Breakdown
1. Purchase By Quantity (Donut Chart)
Shows procurement quantity distribution by item.

Example: Item-1 (62,566 units), Item-4 (58,712 units), etc.

2. Purchase By Amount (Donut Chart)
Displays the purchase amount in INR split by item.

Example: Item-2 has the highest purchase value of ₹184,923,085.

3. Purchase By Month (Bar Chart)
Shows monthly purchase amounts.

Highlights procurement seasonality (e.g., peak in August ₹70,513,722 and September ₹68,329,184).

4. Purchase Quantity By Vendor (Bar Chart)
Compares quantities ordered from each vendor.

Vendor-7 (28,244 units) and Vendor-5 (28,678 units) are leading.

5. Purchase Amount By Vendor (Bar Chart)
Displays purchase amount (in INR) by vendor.

Vendor-8 and Vendor-7 have higher procurement values (₹75,598,422 and ₹79,350,382 respectively).

6. Purchase Amount By Day (Bar Chart)
Shows the daily distribution of purchase amounts within a month.

E.g., peak amounts on days 31, 29, and 25.

7. Inventory Items Balance (Bar Chart)
Displays the current inventory balance by item.

Item-2 has the highest balance (13,845 units).

8. Inventory Out By Items (Bar Chart)
Reflects items moved out of inventory.

Highest movement observed for Item-1 (11,047 units).

## 5. Analysis and Insights
Balanced Procurement: Total quantities pending and received are nearly equal (~50% pending).

High-value Vendors: Vendor-8 and Vendor-7 are significant contributors to procurement by value.

Seasonal Trend: Procurement peaks during August and September, suggesting seasonal or project-based procurement.

Top Items: Item-2 and Item-3 are critical inventory items due to their high purchase values and balances.

Vendor Dependency: A few vendors contribute the majority of purchases, highlighting dependency risks.

## 6. Tools & Techniques Used
Excel Power Query: Used to clean, transform, and merge PO data with Date tables.

Pivot Tables: Created for aggregation and calculations.

Slicers: Added for interactive filtering by month, item, vendor, and status.

Charts: Used bar, donut, and KPI cards to visualize procurement metrics.

Custom Measures: Pending %, Total Balance, and Inventory KPIs computed within pivot tables.

## 7. Recommendations
Diversify Vendor Base: Reduce dependency on top vendors by onboarding alternative suppliers.

Optimize Inventory: Use the balance and inventory-out reports to fine-tune stock levels.

Monitor Seasonal Procurement: Plan procurement and cash flows around the seasonal peaks identified.

Follow-Up on Pending POs: Prioritize pending orders to reduce delays and ensure supply chain continuity.

## 8. Conclusion
The SCM Procurement Dashboard 2024 provides a comprehensive view of procurement operations, assisting the organization in streamlining purchasing, inventory, and vendor management processes. The dashboard delivers critical insights that can help drive operational efficiency and cost-effectiveness.
