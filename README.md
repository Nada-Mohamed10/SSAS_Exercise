## SQL Server Analysis Services (SSAS)

#### Use Internet sales “Dataware housing”
1- 	Create Cube “Product Cube” that shows Product Qty over Years 
-	Use Product Dimension to show (Product ID,ProductName) columns
-	Use time dimension to show (CalenderYear) column
-	Use [fact Sales] to Show  (Qty) Measure
  
2- 	Create Cube “Prod_Cust Cube” that shows the relation between Product, Customer over Time
- Use Product Dimension to show (Product ID, Product Name, Product Category) columns
- Use Customer Dimension to show (Customer ID, Customer Name, Product Address) columns
- Use time Dimension to show (Calendar Year, Calendar Quarter)  columns
- Use [fact Sales] to Show  (Qty, Total price) Measures
- 	Create Calculated Measure “Sales Unite Price” 
Note: Value Expression = [Qty Total Price]/ [Qty]
- Create KPI Indicator  “Qty KPI ” that indicates Qty of sales should be at least 1000 unit
Note: Status Indicator appears as “Faces”
- Create Arabic Translation For the dimensions and measures of this cube
- Create Pivot table and Pivot Chart that describe the difference between QtyKPI and actual Qty . Note  “Use Microsoft Excel 2007 ”

3- Create Cube “Sales Cube” that shows All Dimensions data in SalesDW :
- Show the Measures (Customer Count, Product Count, sales man Count, Channel Count, Qty, Total Price, Fact table count “Number of orders”)
- Create a perspective “Channel product perspective” that shows the Customer name , Channel Location , Qty Measure and the Total Price For each Qty
- Use “Product Cube” to Create Pivot table and Pivot Chart that describe the data in this cube. Note  “Use Microsoft Excel 2007 ”


![ssas](https://github.com/user-attachments/assets/7829eb15-9581-415e-a64e-8201c930c6f0)

![ssas1](https://github.com/user-attachments/assets/8b2f82d6-7ed3-4930-a0a2-714dcc5d7776)
