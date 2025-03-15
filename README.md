##SQL Server Analysis Services (SSAS)

#### Use Internet sales “Dataware housing”
1-	Create Cube “Product Cube” that shows Product Qty over Years 
a-	Use Product Dimension to show (Product ID,ProductName) columns
b-	Use time dimension to show (CalenderYear) column 
c-	Use [fact Sales] to Show  (Qty) Measure

2-	Create Cube “Prod_Cust Cube” that shows the relation between Product, Customer over Time
a-	Use Product Dimension to show (Product ID, Product Name, Product Category) columns
b-	Use Customer Dimension to show (Customer ID, Customer Name, Product Address) columns
c-	Use time Dimension to show (Calendar Year, Calendar Quarter)  columns 
d-	Use [fact Sales] to Show  (Qty, Total price) Measures
e-	Create Calculated Measure “Sales Unite Price” 
Note: Value Expression = [Qty Total Price]/ [Qty]
f-	Create KPI Indicator  “Qty KPI ” that indicates Qty of sales should be at least 1000 unit
Note: Status Indicator appears as “Faces”
g-	Create Arabic Translation For the dimensions and measures of this cube
h-	Create Pivot table and Pivot Chart that describe the difference between QtyKPI and actual Qty . Note  “Use Microsoft Excel 2007 ”

3-	Create Cube “Sales Cube” that shows All Dimensions data in SalesDW :
a-	Show the Measures (Customer Count, Product Count, sales man Count, Channel Count, Qty, Total Price, Fact table count “Number of orders”)
b-	Create a perspective “Channel product perspective” that shows the Customer name , Channel Location , Qty Measure and the Total Price For each Qty
4-	Use “Product Cube” to Create Pivot table and Pivot Chart that describe the data in this cube. Note  “Use Microsoft Excel 2007 ”


![ssas](https://github.com/user-attachments/assets/7829eb15-9581-415e-a64e-8201c930c6f0)

![ssas1](https://github.com/user-attachments/assets/8b2f82d6-7ed3-4930-a0a2-714dcc5d7776)
