# SQL_Mart_analysis
The project aims to understand the top performing branches and products, and customer behaviour from Walmart sales data 

# purpose of the project
Gain insight into the sales data of Walmart to understand the different factors that affect sales of the different branches, by answering the list of analysis questions.

# about data 
This dataset contains sales transactions from a three different branches of Walmart,The data contains 17 columns and 1000 rows

|Column|	|Description|	|Data Type|
|-|-|-|
1. |invoice_id|	|Invoice of the sales made|	|VARCHAR(30)|
2. |branch|	|Branch at which sales were made|	|VARCHAR(5)|
3. |city|	|The location of the branch|	|VARCHAR(30)|
4. |customer_type|	|The type of the customer|	|VARCHAR(30)|
5. |gender|	|Gender of the customer making purchase|	|VARCHAR(10)|
6. |product_line|	|Product line of the product solf|	|VARCHAR(100)|
7. |unit_price|	|The price of each product|	|DECIMAL(10, 2)|
8. |quantity|	|The amount of the product sold|	|INT|
9. |VAT|	|The amount of tax on the purchase|	|FLOAT(6, 4)|
10. |total|	|The total cost of the purchase|	|DECIMAL(10, 2)|
11. |date|	|The date on which the purchase was made|	|DATE|
12. |time|	|The time at which the purchase was made|	|TIMESTAMP|
13. |payment|	|The total amount paid|	|DECIMAL(10, 2)|
14. |cogs|	|Cost Of Goods sold|	|DECIMAL(10, 2)|
15. |gross_margin_percentage|	|Gross margin percentage|	|FLOAT(11, 9)|
16. |gross_income|	|Gross Income|	|DECIMAL(10, 2)|
17. |rating|	|Rating|	|FLOAT(2, 1)|


# Analysis list
1. product_analysis:Conduct analysis on the data to understand the different product lines, the products lines performing best and the product lines that need to be improved.
2. Sales Analysis: help use measure the effectiveness of each sales strategy the business applies and what modificatoins are needed to gain more sales.
3.  Customer Analysis: This analysis aims to uncover the different customers segments, purchase trends and the profitability of each customer segment.

# Approach used:
- Features addition:
  1. Add a new column named time_of_day to give insight of sales in the Morning, Afternoon and Evening.
  2. Add a new column named day_name that contains the extracted days of the week on which the given transaction took place (Mon, Tue, Wed, Thur, Fri).
  3. Add a new column named month_name that contains the extracted months of the year on which the given transaction took place (Jan, Feb, Mar).

# list of questions:

- General question:
  1. How many unique cities does the data have?
  2. In which city is each branch?

- **product**:
  1. How many unique product lines does the data have?
  2. What is the most common payment method?
  3. What is the most selling product line?
  4. What is the total revenue by month?
  5. What month had the largest COGS?
  6. What product line had the largest revenue?
  7. What is the city with the largest revenue?
  8. What product line had the largest VAT?
  9. Fetch each product line and add a column to those product line showing "Good", "Bad". Good if its greater than average sales
  10. Which branch sold more products than average product sold?
  11. What is the most common product line by gender?
  12. What is the average rating of each product line?


- **Sales**:
  1.   Number of sales made in each time of the day per weekday
  2.   Which of the customer types brings the most revenue?
  3.   Which city has the largest tax percent/ VAT (Value Added Tax)?
  4.   Which customer type pays the most in VAT?

- **Customer**:
  1. How many unique customer types does the data have?
  2. How many unique payment methods does the data have?
  3. What is the most common customer type?
  4. Which customer type buys the most?
  5. What is the gender of most of the customers?
  6. What is the gender distribution per branch?
  7. Which time of the day do customers give most ratings?
  8. Which time of the day do customers give most ratings per branch?
  9. Which day fo the week has the best avg ratings?
  10. Which day of the week has the best average ratings per branch?
  









  
