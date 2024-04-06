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
