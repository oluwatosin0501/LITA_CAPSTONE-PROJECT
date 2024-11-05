# LITA_CAPSTONE_PROJECT
This is where I documented  my capstone project while learning Data Analysis with The Incubator Hub

### PROJECT TITLE: SALES PERFORMANCE ANALYSIS


### PROJECT OVERVIEW
This Datab Analysis project aims to generate insight into the sales performance projectover the past year.By analysing the various parametersin the data  received to seek insight to make reasonable decisions which then enable us to create visualiztion around our data from the insight gotten.

### DATA SOURCES
The primary source of data used here is Saledata.xls and this was dpwnloaded from LITA LMS.Data can be freely downloaded from online source such as kaggle,FRED,Tableau or any other repository site.


### TOOLS USED
-MICROSOFT EXCEL for Data Cleaning and Pivot Table
-SQL( STRUCTURED QUERY LANGUAGE) for Quering Data
-POWER BI for visualisation
-GITHUB for Portfolio Building

### DATA CLEANING AND PREPARATIONS
The initial phase of the Data Cleaning and preparations, i perform the following
1. Data loading and inspection
2. Handling missing varaiables
3. Removed duplicates( Data Cleaning)
4. Check blank spaces( Data Cleaning)
5. Data Formatting
   
### EXPLORATORY DATA ANALYSIS
EDA involved the exloring of the data to answer some questions about the data such as;
1. Total sales by product,region,and month.
2. Excel formular to calculate metrics such as average sales per product and total revenue by region.

### DATA ANALYSIS
This is where I used some basicc lines of code while using MYSQL WORKBENCH.I also used excel functions while using Excel.
```SQL
SELECT Region,COUNT(`CustomerName`) AS `TOTAL CUSTOMERS`
FROM `capstone project`.`sales data csv`
group by 1;






