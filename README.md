# *Project Title: SuperSales Analysis*
In this analysis, I will be using Microsoft Excel to analyse, visualize and draw insights from the Superstore Dataset publicly obtained from Kaggle (https://www.kaggle.com/datasets/vivek468/superstore-dataset-final). The SuperStore dataset spans a period of Four (4) years.

------------------------------------
# *Problem Statement*
In this step, the business problem is discussed in the form of Business Objective to guide future business decisions...  
Businesss Objectives:  
* Total Sales?  
* Total Orders?  
* Total number of Customers?  
* Total number of Products?  
* Cities with the highest sales record?  
* States with the highest sales record?  
* The Ship mode in order of use?  
* Sales by Category?   
* Sales by Sub-category?
* Sales by Region? 
* The average delivery days from the date of order to ship date?  
* The most valuable customers?
* Top Selling Products?

------------------------------------
# *Data Sourcing*
This step discusses the raw form of the SuperStore dataset as follows:  
* The Superstore dataset is publicly available on Kaggle (https://www.kaggle.com/datasets/vivek468/superstore-dataset-final).  
* It consists of 21 Columns including: Row ID,	Order ID,	Order Date,	Ship Date,	Ship Mode,	Customer ID,	Customer Name,	Segment,	Country,	City,	State,	Postal Code,	Region,	Product ID,	Category,	Sub-Category,	Product Name,	Sales,	Quantity,	Discount &	Profit.
* It consists of 9,994 rows and 1 row as header-row.

------------------------------------
# *Data Transformation*
Power Query from Excel was utilized to clean and transform the data to address:  
* Duplicate values: There was no duplicate row found.
* Missing values or errors: There was none found.
* Inconsistency in datatype: Columns were formatted to appropriate datatype.
* Inconsistency in date formats: Date columns were converted from text to date.
* Removal of unnecessary data: 3 unnecsssary columns were removed; Row ID column was removed since it is the same as Excel column label. Country column was also removed since this data is based in only one country 'United States'. Postal Code column was also removed since it isn't useful for this analysis.

-------------------------------------

# *Analysis and Findings*  
1. Total Sales?
    There is a total of 2,297,201 sales carried out between 2014 and 2017. In the year 2014, there was a total of 484,247 sales; 2015 has 470,533 sales; while 2016 has 609,206 sales;        and 2017 has 733,215 sales.
2. Total Orders?
    A total of 9,994 orders was placed between the year 2014 and 2017. While 2014, 2015, 2016, 2017 each has 1,993, 2102, 2,587, 3,312 orders respectively.
3. Total number of Customers?
    There was a unique count of 793 customers.
4. Total number of Products?
    There was a total number of 1,862 unique products.
5. Cities with the highest sales record?
    ![image](https://github.com/Musabdullahi/DA-Stuffs/assets/99256919/35689e74-6c59-4414-815b-2069b0a6af62)

6. States with the highest sales record?
7. The Ship mode in order of use?
8. Sales by Category?
9. Sales by Sub-category?
10. Sales by Region?
11. The average delivery days from the date of order to ship date?
12. The most valuable customers?
13. Top Selling Products?
