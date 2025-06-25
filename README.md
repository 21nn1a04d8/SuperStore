A superstore retail business is a large, multi-department store that sells various products,
including groceries, electronics, home goods, clothing, and more. These stores are often
designed to be a one-stop shop for customers, offering a wide range of products and services
under one roof. Superstores are typically larger than traditional retail stores and may have a
larger product selection. Superstores are often part of a larger chain and have multiple locations
in a region or country.
A new store manager needs your help to better understand his/her Data Operations Team. You
are provided with part of the sales data that a Business Intelligence Analyst encounters daily.
Design the dashboard to analyze and interpret the data to help provide valuable insights to the
store manager.
Problem Statement:
Data Extraction, Cleaning,Loading and Transformation
1. Desk representatives at the stores are not tech savvy hence they directly share the data
in the single excel file. As a Power BI Developer, read the data directly from the excel
file.
2. The data coming from the source is in raw form in the flat file; hence clean and prepare
(transform) the dataset for efficient use. Delete the empty columns and rows, change the
fields to appropriate data types and split the fields and rename the columns
appropriately.
3. Standardize the values in the column Ship mode 
4. Split the address column to City, State, Country and Pincode
Data Analysis:
Furthermore, to grow the footholds in the store and achieve an ambitious sales target,
the store manager wants to track and visualize the following metrics;
1. Create a new column ‘Sales’ or ‘Order value’ [Hint: Sales = Qty*price per qty*(1- %
Discount)]. Create a card visual displaying the total sales.
2. Similarly calculate the Sales from discounted products and display the total sales
from discounted products.
3. Since supermarkets sell bulk items, store managers want to know each order's cart
value. Create a column “Cart Value” that categorizes the order value/sales as Low,
medium, high or very high.
Cart Value,
< 1000: Low
<3500: Medium
< 10000: High
> 10000: Very High
[Hint : From Power Query editor->Add column-> Conditional column OR
DAX formula using nested IF( ) function]
Create a pie chart with Cart value as legend and Order value in Values field.
4. Separately visualize the total sales just from the low cart value category (as
mentioned, any value below 1000 can be considered as low value category).
5. Using card visual, track the total sales coming from the low cart category and
discount more than or equal to 50% to find out the contribution and cause.
BF.P.D36A

6. Find out the number of days it takes to deliver for each shipment type (refer ship
mode) so that delivery issues can be looked at on priority [Hint: No of days to deliver
can be calculated from the difference between order_date and shipping_date].
Create a column chart that shows the average number of days it takes to deliver for
each shipment type.
7. So far the store manager has managed to see the current snapshot of the sales
based on various criteria. In the Retail business, do we see a spike in sales on
special occasions like festivals? To achieve this, create a matrix visualization that
displays order date as hierarchy , sales and sales year to date.
8. Visualize the cumulative sales for each month for all the years to calculate Year on
Year Sales Growth. Calculate YoY growth.
You are expected to provide a write-up explaining the data and any insights you can gather. You
are encouraged to provide visuals and use basic statistics for this purpose.
