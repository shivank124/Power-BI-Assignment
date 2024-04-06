## Power BI Case Study 5
## Problem Statement
You work as a Power BI Developer in a leading software company. As a BI professional, you are
asked to build a Power BI Report with the following requirements.  

## You have been asked to  
### Connect to data:
a) Open Power BI Desktop, connect to the AdventureWorksLT database, use the query
in Task 1 in the Labexercise1.SQL file, and load it in Power BI Desktop.  

b) Open Power BI Desktop, connect to the AdventureWorksLT database, use the query in Task
2 in the Labexercise1.SQL file, and load it in Power BI Desktop.  

c) Now, save the file as AdventureWorksLT sales 5.  

### Shape the data:
a) Rename Query 1 to Customers and Query 2 to Sales.  

b) Delete NameStyle and SalesPerson from the Customers table.  

c) Hide the CustomerID column from the Report view.  

d) Change the data category of the following: 
* AddressLine1 to Address
* City to City
* StateProvince to State or Province
* CountryRegion to Country/Region
* PostalCode to Postal Code
* 
e) Add a new column FullAddress, which will concatenate AddressLine1, City, StateProvince,
CountryRegion, and PostalCode.

f) In the Sales table, delete RevisionNumber and SalesOrderNumber columns.  

g) Hide CustomerID, SalesOrderID, and SalesOrderDetailID from the Report view.  

h) Add a new column called LineTotal, which multiplies OrderQty with ListPrice, and make the
format as Currency ($).  

i) Create a measure named TargetSales, which increases LineTotal in the Sales table by 2%.  

j) Then, save the file.  

### Combine the data
a) Create a new table called Sales by States by importing the States table.  

b) Get data from the Wikipedia website to import the list of states in America.  

c) Remove the last 26 rows.  

d) Remove the first 3 Rows.  

e) Set the first row as headers.  

f) Remove all the columns except the United States of America and US USA 840 columns.  

g) Change the name of the table to States with Codes.  

h) Rename the United States of America to State Name and US USA 840 to State Code Long.  

i) Merge this data with Sales by States, displaying only the State Code Long field.  

j) If the Privacy level dialog box appears, click on Organizational and then on Save.  

k) If the Information is required dialog box appears, then click on Continue.  

l) Name the new column as State Code.  

m) Click on Close and apply.  

n) Hide the states with codes in the Report view.  

o) Finally, save the file.  

### Add visualizations
a) Add a gauge chart with LineTotal in the value Properties and TargetSales in the Target value
Properties.  

b) Set the Max value of the gauge to 1460000, and name it as Target Sales.  

c) Create a pie chart with CompanyName and LineTotal; name it as Top Selling Companies,
and center-align it.  

d) Create a stacked bar chart with MainCategory and OrderQty columns; name it as Sales by
Main Category, and then, center-align it.  

e) Click on Analysis, expand the Constant Line, and click on Add. Then, set the value to 500, and
change the color to Red.  

f) Create a donut chart with MainCategory and LineTotal.  

g) Name it as Sales by Main Category, and center-align it.  

h) Create a stacked column chart and add Product, LineTotal, and MainCategory.  

i) Filter the products to display only those with sales greater than US$32,000, and then, filter
the list to display only ‘bikes’.  

j) Name it as Top Selling Bikes, and center-align it.  

k) Add a Constant Line, with the value set to 35000, and then set the color to Red.  

l) Save the report, and add a new page to the report.  

m) Create a map visual with City and LineTotal, and name it as World Sales by City.  

n) Add a map visual with State Code and SalesYTD, and rename the map to Sales by State.  

o) Finally, save the report.  
