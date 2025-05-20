
**Amazon Global Sales Dashboard Overview**

This interactive Power BI dashboard presents a **year-wise global sales analysis** of Amazon from 2012 to 2015. The report is designed using effective data modeling and DAX functions to derive KPIs, regional insights, segment distribution, and product-level profitability.

### 🔍 **Key Features:**

* **File Format:** `.pbix` (Power BI Desktop file)
* **Time Filter:** Year slicer (2012–2015) for dynamic trend analysis
* **Main KPIs:**

  * **Sales Projection:** 2.26M
  * **Product Units Sold:** 3022
  * **KPI Value:** 31K
  * **Returns:** 368 units
* **Visual Elements:**

  * **Pie Charts:** Sales by Segment & Market
  * **Bar Charts:** Top & Bottom 5 Products by Profit, Profit by Customer
  * **Map Visualization:** Regional Sales Distribution (using Bing Maps)

### 🧮 **DAX & Data Modeling:**

* **DAX Functions Used:**

  * `CALCULATE()`, `SUM()`, `FILTER()`, `YEAR()`, `DISTINCTCOUNT()`, `RETURN()` (for KPI logic)
  * Time intelligence functions for year-wise comparison
* **Data Modeling:**

  * **Star Schema** with a central Fact table (Sales) and related Dimension tables (Product, Customer, Region, Time)
  * Relationships defined for slicers and drill-downs

### 📈 **Purpose of the Dashboard:**

This dashboard enables stakeholders to:

* Monitor global sales performance across regions and years
* Identify high- and low-performing products and customer segments
* Evaluate key metrics like returns and unit sales
* Support strategic decisions through visual insights


Screenshot / Demo
https://github.com/Mahendra7805/Amazone-sales/blob/main/Amazone%20Sales.png
