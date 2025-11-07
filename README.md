# dmart-sales-trends
# PowerBI Project ( DMart Retail Product Price & Discount Analysis )

**Project Overview**

This project provides an analytical view of DMart’s retail product pricing, discounts, brand performance, and category distribution. A Power BI dashboard was created to help understand overall product value, total discounts, product category mix, and brand-wise contribution. The dashboard assists retail teams in making data‑driven decisions related to pricing, promotions, and inventory planning.

**Dataset Description**

- Name : Product Title
- Brand : Brand name Of product 
- Price : Original Price Of Product 
- Discountedprice : After Discount Price
-Subcategory : Product Sub-type 
- Quantity : Sold Quantity
- Breadcrumbs : Hierarchy Path  

**Key Matrics**

Based on the dashboard data, the dataset includes:
- 805 Total Brands
- 4005 Total Products
- 26 Product Categories
- 522K Total Discount Amount
- 8050M Total Product Value

**Key Insights**

1.	Compare Which Product Categories Contributes The Most Discount Value 
 Purpose : Find Which category Gives The Highest Total Discount( Greater Than 50k)

 •	This Chart Compares Categories By Sum Of Discount amount

 •	Highest discounts are seen in Home & Kitchen (130K) and Personal Care (103K)

 •	Grocery and Specials categories also have notable discount contribution

3.	Which Category Has The Most Products In Dmart   
 Purpose : Find Which Category Has The Most Or Least Products – Not Discount

 •	This Chart Shows Categories again, but Based on Number of Productss ( Count of Name )

 •	Personal Care and Packaged Food categories hold the highest product counts (~1K each).

5.	Which Brand Has The Most Products in Dmart 
 Purpose : Identify the Top 10 Brands with the Products 
 
 •	Zeel is the top brand with 33 products 
 
 •	Zerobonics (14 products) and Yoga Bar (10 products) follow.
 
**DAX Measures Used**

Below are some commonly used( DAX measures based on dashboard fields:
•	Total Price = SUM(DMart[Price])

•	Total Brand = DISTINCTCOUNT(DMart[Brand])

•	Total Discount = SUM(DMart[Discount Amount])

•	Total Product = DISTINCTCOUNT(DMart[Name]) 

•	Total Categories = DISTINCTCOUNT(DMart[Category])

**Conditional Formatting Used**

Conditional formatting applied in Power BI:
•	Bar charts & category visuals: Green color formatting to highlight highest values.
•	Brand-wise count chart: Bars colored to emphasize top-performing brands.
•	Card visuals: Threshold‑based formatting for KPIs:
•	High values displayed in bold and large font.
•	Neutral background theme used for readability.

**Conclusion**

The analysis reveals DMart’s strong focus on Personal Care, Packaged Foods, and Home & Kitchen categories. The dashboard highlights top discount categories, brand contributions, and overall product distribution. Power BI visualizations and DAX measures provide a clear and interactive understanding of pricing and discount patterns, supporting effective retail decision-making.


