# Power BI Case Study 4
## Problem Statement  
You work as a Power BI Developer in a leading software company. As a BI professional, you are asked
to explore ways in which AdventureWorks can empower business and build a report based on sales.  

## You have been asked to  
a) In Power BI Desktop, connect to AdventureWorks Sales Data.xlsx.  

b) Import DimCurrency, DimCustomer, DimDate, DimProduct, DimPromotion,
DimSalesTerritory, and FactInternetSales worksheets.  

c) Create a new relationship between the FactInternetSales table’s OrderDateKey column and
the DateKey column in DimDate. Set the cardinality as Many to One (*:1), the cross-filter
direction as Single, and make this relationship Active.  

d) Create a relationship from FactInternetSales [DueDateKey] to DimDate [DateKey].  

e) Create a relationship between FactInternetSales [ShipDateKey] and DimDate [DateKey].  

f) In Power BI Desktop, load the DimProductCategory and DimProductSubcategory data from
the AdventureWorks Product Categories.xlsx file.  

g) Delete the relationship between DimProductCategory and DimProductSubcategory.  

h) Create a Many to One (*:1) between DimProductSubcategory [CategoryKey] and
DimProductCategory [CategoryKey] and make the cross-filter direction to both.  

i) Create a Many to One (*:1) between DimProduct [ProductSubcategoryKey] and
DimProductSubcategory [SubcategoryKey] and make the cross-filter direction to both. 

j) Add a calculated column named IncomeStatus to the DimCustomer table based on
the YearlyIncome column. Income should be classified as follows:  
* Lower than 25,000: Lower Income
* Between 25,000 and 60,000: Middle Income
* Between 60,000 and 100,000: Higher Income
* 100,000 and upward: Very High Income.

k) Add a calculated column named DaysSinceFirstPurchase to the DimCustomer table to show
the number of days since a customer made the first purchase.  

l) Add a calculated column named FullName to DimCustomer, which concatenates the
FirstName and the LastName.  

m) Add a calculated column named MaleFemale to DimCustomer, which converts the values of
the Gender column to Male or Female.  

n) Add a calculated column to DimCustomer, called Relationship, which converts the value of
the MaritalStatus column to Married or Single.  

o) Add a calculated column called MainCategory to the DimProductSubcategory table, which
gets the category name from DimProductCategory.  

p) Add a calculated column called PromotionLengthDays to the DimPromotion table, which is
the difference between StartDate and EndDate.  

q) Add a calculated column called Profit to FactInternetSales, and show the difference between
UnitPrice and ProductStandardCost formatted as currency.  

r) Save the changes, and close Power BI Desktop.  
