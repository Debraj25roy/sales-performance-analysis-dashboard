# Sales Performance Analysis

## Objective
Analyze historical sales data to identify trends, seasonal patterns, and top-performing products. Build an interactive dashboard that highlights key sales metrics.

## Tools Used
- Microsoft Excel (with charts and pivot-ready summaries)
- Data can be imported into Power BI or Tableau for interactive dashboards.

## Dataset
File: `data/sales_data.csv`

Columns:
- `OrderID` – Unique order identifier  
- `OrderDate` – Date of the order  
- `Region` – Sales region (North, South, East, West)  
- `Category` – Product category (Electronics, Furniture, Clothing, Grocery)  
- `Product` – Product name  
- `Quantity` – Units sold  
- `UnitPrice` – Price per unit  
- `Discount` – Discount applied (0 to 0.15)  
- `Revenue` – Final revenue for the order after discount

## How the Analysis is Structured

1. **Raw_Data (Excel Sheet)**
   - Full transactional-level data for all orders.

2. **Monthly_Sales (Excel Sheet)**
   - Aggregated monthly revenue and quantity to identify:
     - Overall growth trend
     - Seasonality or peak months

3. **Top_Products (Excel Sheet)**
   - Total revenue and quantity by product.
   - Sorted by revenue to easily see top-performing products.

4. **Region_Sales (Excel Sheet)**
   - Total revenue and quantity by region to identify high-performing markets.

## Excel Dashboard Elements

The Excel file `Sales_Performance_Analysis.xlsx` already includes:
- A **line chart** showing *Monthly Revenue Trend*.
- A **column chart** showing *Revenue by Region*.
- Pre-aggregated sheets that you can quickly turn into Pivot Charts/Dashboards.

## Using this Data in Power BI / Tableau

1. Import `data/sales_data.csv`.
2. Create measures:
   - Total Revenue
   - Total Quantity
   - Average Revenue per Order
3. Build visuals:
   - Line chart: Revenue by Month
   - Bar chart: Revenue by Region
   - Bar chart: Top 10 Products by Revenue
   - Filters: Region, Category, Year

## Outcomes

- Identified which **products and categories** drive the highest revenue.
- Found which **regions** contribute most to total sales.
- Observed **monthly sales trend** and possible seasonality (e.g., peaks around year-end).

## How to Run

1. Open `Sales_Performance_Analysis.xlsx` in Excel.
2. Explore each sheet:
   - `Raw_Data`
   - `Monthly_Sales`
   - `Top_Products`
   - `Region_Sales`
3. Import `data/sales_data.csv` into Power BI/Tableau and create an interactive dashboard.
