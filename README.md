# Fanbian Stores Sales Report 
## Introduction 
The Fanbian Store Sales Report was analyzed using Microsoft Power BI, Excel and Powerpoint. 

## Dataset
The dataset is a sales report of 49 states across the United States of America gotten from Microsoft's website. You can download the raw data here: https://learn.microsoft.com/en-us/power-bi/create-reports/sample-financial-download 

The data has 22 columns and over 5000 rows. The columns include Row ID, Order ID, Order Date, Ship Date, Ship Mode, Customer ID, Customer Name, Segment, Country, City, State, Postal Code, Region, Product ID, Category, Sub-Category, Product Name, Sales, Quantity, Discount, Profit, and Profit Margin. 

<img width="1247" alt="Screenshot 2023-02-24 at 12 59 12" src="https://user-images.githubusercontent.com/123817356/221173497-5e685502-ed33-4e5f-ade2-0e93d2169934.png">

## Data Cleaning:
1. I removed blanks and duplicates in excel, 
2. Uploaded to power BI,
3. Grouped the columns into Dimension table(Customer, Products, Location and Order Info) and Fact Table. 
4. Customer included the customer information: Customer ID, Customer Name and Segment, with Customer ID as the primary key); 
5. Location included: Postal Code, City, State, Region, and Country, with Postal Code as the Primary Key;
6. Order info included: Order ID and SHip Mode, with Order ID as the primary key; 
7. Products included: Category, Sub-Category,  Product ID and Product Name, with the product name as the primary key. 
8. Fact table included all numerical columns. 
NB: The primary keys are the smallest indivisible values in the dimension table; they connect with the fact table to build a model.  

![image](https://user-images.githubusercontent.com/123817356/223383131-3e20320c-e7e3-4c80-98c2-c660ae352944.png)

## Data Analysis 
To analyze the Fanbian sales Report, I answered the following questions:
1. The sum of sales per category
2. The states with the highest sales 
3. The amount of profit per category 
4. and the states with the highest profit.

## Data Visualization
We created a four-page dashboard showing the homepage, overview, sales, and profit pages. 

![Homepage](https://user-images.githubusercontent.com/123817356/221175445-9fbb2cbf-3343-47c4-8230-dc61cec6e142.jpg)

![sales](https://user-images.githubusercontent.com/123817356/221175584-1b786e3c-9bb4-42f4-bff3-c4ccb6a0b2fa.jpg)

### Interpretation

**The sum of Sales per category**

It was represented on the dashboard as the Sum of Sales by Category. The doughnut chart above shows that the Technology category had the highest sales, accounting for 47% of total sales. 

**The states with the highest sales**

It was represented as Top 10 Sales by State on the dashboard. It can be seen that North Carolina, followed by New York and California, has the highest sales. 


![profit](https://user-images.githubusercontent.com/123817356/221175649-f4928f55-b35e-4921-87aa-d940b56e8468.jpg)

### Interpretation

**The amount of profit per category**

It was represented as the Sum of Profit by Category on the dashboard. We can see in the image above that Office supplies, although having the lowest percentage of sales, had the highest profit.

**The states with the highest profit**

It was represented as the Top 10 Profit by State on the dashboard. The analysis shows North Carolina, which had the highest sales, ran at a loss, ranking number 10. 

![overview](https://user-images.githubusercontent.com/123817356/221176777-affdf041-6002-4783-b9b8-e00115c49608.jpg)

### Insight and Recommendation
The analysis above shows that making sales and making a profit are very different concepts. We recommend states and categories where sales are high, but profit is negative to reevaluate their strategy. 
