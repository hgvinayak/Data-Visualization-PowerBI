# Data-Visualization-PowerBI

🌱Project: Global Superstore Sales Analysis

📓Data set : Global Superstore - sales (Kaggle)

✨Objective: To analyse the slaes data to uncover the key insights which will help to make the business decions.


⚙⚙Steps Applied:

	1. Understand the data and identifying the key parameters which will help to take the business decisions.
	2. Get the data and Transform it, add any new columns or measures if required.
	2. Changed the column type of Discount and made it as "TRUE/FALSE"
	3. Changed the column name from profit to Gross profit. 
	3. Added new column as COGS (Cost of goods sold) = Revenue or sales  - gross profit 
	4. We added one more new column as Net profit  = Gross profit - Operating costs (shipping cost).
	5. We added a new measure i.e Average shipping cost - ship mode wise.
	6. Added a new measure called "Sales amount".
	7. Created an date column - continious one.using Calender DAX function.


	📌---We need to understand the KPI cards as mentioned below

	1. Total Revenue or Sales maount generated.
	2. What is the total profit , gross and net profit.
	3. No of unique products sold - we have distinct count.
	4. No of orders we got - used "COUNT" 
	5. Total Shipping cost 
	6. Total Quantity sold
	

	📌-----We need to have the charts to visualize the data in a deeper way.
	1. Total Sales generated by category, sub category, segment and Reigon wise
	2. Gross Profit - category wise,segment wise
	3. Total Shipping cost - category wise . 
	4. Average Shipping cost - ship mode wise.


	📌-----SLICERS Used:
	1. Date column - which is continious, so we can view the data by selecting the date range.
	2. Priority Mode - High , medium , Low
	3. Discount - True /False
	4. Market - 1,2

	📌----chart selections:
	1. We used Tree map for category and sub category - Sales
	2. We used Funnel chart to view the sales data sub category wise.
	3. We have created a new parameter for slicer - "MARKET", because both are diffrent columns.

🎁✨Conclusion:

	1. As per as sales is concerned the "Technology" product category as the highest sales and "office supplies" category is lowest.
	2. Most of the products are delivered through "standard class" shipment mode.
	3. Average shipping cost for "standard class - mode" is less and we should use a strategy to make the shipment by using this type of mode preferrably.
	4. Here we can notice that the shipping cost is almost equal to 35% of the total sales generated for "Technology" product category. So we need to focus on the shipping cost that how we can reduce this and the answer is using "standard 
	   class shiping mode- preferrably.
	5. By the Funnel chart we get to know which are the top sub categories of products having the highest sales and bottom one also.   



