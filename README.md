# *Project Title: SuperSales Analysis*
In this project, I will be using Microsoft Excel to analyse, visualize and draw insights from the Superstore Dataset publicly obtained from Kaggle (https://www.kaggle.com/datasets/vivek468/superstore-dataset-final). The SuperStore dataset spans a period of Four (4) years.

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
![image](https://github.com/Musabdullahi/DA-Stuffs/assets/99256919/84775fde-9640-4a74-aa4c-79f7adb3207c)
1. Total Sales?  
    There is a total of 2,297,201 sales carried out between 2014 and 2017. In the year 2014, there was a total of 484,247 sales; 2015 has 470,533 sales; while 2016 has 609,206 sales;        and 2017 has 733,215 sales.
    Monthly sales deduction shows that sales are usually high towards the end of the year around Q3 and Q4.
3. Total Orders?  
    A total of 9,994 orders was placed between the year 2014 and 2017. While 2014, 2015, 2016, 2017 each has 1,993, 2102, 2,587, 3,312 orders respectively.
4. Total number of Customers?  
    There was a unique count of 793 customers.
5. Total number of Products?  
    There was a total number of 1,862 unique products.
6. Cities with the highest sales record?  
    In this analysis, New York City has emerged as the leading market, boasting an impressive sales figure of about 256,400 transactions, presenting a significant opportunity for            targeted marketing potential.
7. States with the highest sales record?  
    California has emerged as the top-selling state, recording an impressive 458,000 transactions. This data highlights a valuable chance for focused marketing in the state to tap into      its potential for boosted sales.
8. The Ship mode in order of use?  
![image](https://github.com/Musabdullahi/DA-Stuffs/assets/99256919/9f5dc4c2-b3a0-4c90-bbbf-610c9fb92aba)  
   The order of ship mode usage is as follows: 'Standard class' takes the lead due to its affordability, followed by 'Second class' and 'First class,' with 'Same day' being the least       utilized mode.
10. Sales by Category?
11. Sales by Sub-category?
12. Sales by Region?
13. The average delivery days from the date of order to ship date?
14. The most valuable customers?
15. Top Selling Products?
