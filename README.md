# Personal-Project_EWD2
This was initially a excel project but i did it in python

Business Context:.
----------
"Office Supplier Retailer Co. (OSX) is a supplier of office equipment and consumables in Asia and Oceania. Recently, OSX has appointed a new COO who is looking to aggressively improve business performance. You are a manager tasked to drive this initiative and have decided to look into optimising OSX business processes by analysing sales at an Order level. 

The data storage team has fulfilled your request and collected sales records for the past 4 years. There is a lot of data! How will you extract the insights you need to make a recommendation to the new COO?"


Business Problem:.
------
Even though OSX sales have increased over time, company's profit book has been stagnant over the years
		
Business Objective:.
------
Increase annual profitability of OSX business
		

Data Objectives:.
-------
1. Analyze OSX company profit books and identify areas of business which have been consistently underperforming (i.e. loss making)
2. Identify drivers of profit for the OSX company
3. Analyze the reason behind low profit margins for specific areas of OSX business
4. Recommend next set of plans to increase annual profits for the company


Instructions:.
------
-	As a manager you have brainstormed with your working team to create a list of hypotheses to test using the mind map framework to achieve the business objectives
-	As next step you need to test the below listed hypotheses based on OSX historical data and answer questions to achieve the data objectives
-	Provide recommendations based on hypothesis results around hpw OSX can increase annual profitability
------------------------------------------------------------------------------------------------------------------


A) Location based hypotheses:
------
1. South East Asian(SEA) based countries are less profitable than the East Asian countries with similar sales volume?
2. Top 5 countries in SEA contributes close to 90% of the total sales in SEA?
3. Major SEA based countries with high sales volume (from hypothesis #2) have consistently been loss making in the past four years, in turn reducing overall SEA profitability?
4. Profitable SEA countries are not generating enough sales to impact overall SEA region's profitability?

Hints: 
- Calcualte profit margin at aggregated level by inserting a pivot column field 
profit margin = total Profit / total Sales			

- Create pivot table to compare profit levels for different regions and countries; Also identify countries with high sales volume using a pareto chart						
- Focus on regions and countries which has high sales volume but lower profits	

-------------------------------------------------------------------------------------------------------------------

B) Product based Hypotheses:.
----------
5. Amongst all product categories, "Office furnitures" and "Technology" product categories drives majority of total annual sales in SEA?

6. Within the "Office furnitures" and "Technology" based product categories, there are products which are consistently loss making in SEA region?

7. Countries like Philippines, Thailand and Vietnam are loss making because profitable products across other countries are making huge losses in these three countries?

Hints:		
- Create pivot at product category and sub category levels to analyze sales and profit margin					
- Create another pivot to analyze profit margins at product and country level for SEA	

-------------------------------------------------------------------------------------------------------------------

C) Customer level Hypotheses:.
-----
8. Returning customers are finding ways to get higher discount in turn reducing profit margins for the company?

9. Customer demand for various products orders are seasonal and depends on specific day of the week?

-------------------------------------------------------------------------------------------------------------------

D) Cost based hypotheses:.
-------
10. Higher percentage of discounts offered on products is leading to reduced profit?

11. East Asian countries are highly profitable compared to SEA countries because the discount per order for SEA based countries are significantly high compared to East Asian countries?

12. Reducing the discounts on products will lead to a significant decline in sales volume?

Hints:									
- Create pivot table at order ID level to analyze discounts and profits offered on each order. Use excel CORREL function and scatter plot to see the correlation between profits and discounts, i.e. will higher discounts reduce profits?										
- Create another pivot table at country level to see the profitability and discounts offered; And also create pivot tables to see discounts offered by region and product										
- Mesaure correlation between discount and sales using a pivot table and CORREL excel function	
