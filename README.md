# Power-BI-Sales-Project

**Requirement Gathering & Planning:**
1. Show total no of orders.
2. How many customers are there?
3. How many orders statuses are there? (Visualise order status by count of order)
4. How many orders are ordered by individual country and state? (both are display in one chart)
5.No of orders and their price by region and payment method (Dual graph)
6.How many items sold by country and their city?
7.How many paid payment by customers using different payment method over category wise?
8.Display no of orders and their payments by customers over year and month.
9.How many quantity order by category and display their order status of customers?
10.Display customers and show total discount on items and add no of items.
11. Display total quantity of order by yearly and monthly.

**Connect to Data Sources:**
Open Power BI Desktop.
Select "Get Data" to connect to Excel

**Clean and Transform Data (Power Query):**
Use the Power Query Editor to clean raw data.
Rename columns, remove irrelevant rows, change data types, and merge tables as necessary.

**Data Modeling**
Establish relationships between tables (e.g., connecting a sales table to a calendar table).
Create a Date Table (Calendar Table) for time-series analysis.

**DAX:**
Define measures and columns using DAX (Data Analysis Expressions) for calculations like Total Sales = SUM(Sales[Amount]).
count_order = COUNT(sales[cust_id])
customer = DISTINCTCOUNT(sales[E Mail])
item = COUNT(sales[item_id])

**Design Visualizations:**
Add charts (bar, line, donut) to the report canvas based on the mock-up.
Use cards for high-level KPIs.
Apply themes and formatting for a professional look.
Add filters and slicers for interactivity.

**Publish and Share:**
Save the report (.pbix file).
Publish the report to the Power BI Service.
Set up automated data refresh schedules.
Share dashboards with stakeholders and configure security.

