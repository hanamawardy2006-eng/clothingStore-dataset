 clothingStore-dataset
A dataset with simple dashboard about a clothing store's sales...etc
What is the dataset about?
•	This dataset is about a clothing store E-commerce sales , it covers business attributes including: product categories , subcategories , ratings , units sold and product characteristics
Data cleaning:
•	This data was processed and transformed using power query
•	1)connected the file into power query
•	2)deleted all duplicates
•	3)checked each column data type
•	Category ,subcategory , style , material, size, season into text
•	Price , total revenue into currency
•	Ratings into decimal number
•	4)Trimmed unnecessary space
5)calculated new column TOTAL REVENUE
[units_sold]*[price_usd]
Business questions;:
1)What is the total volume of units sold across all categories? =SUM(units_sold)
Business Benefit: Evaluates overall sales scale and product demand, establishing a core benchmark for supply chain forecasting and warehouse capacity planning.
2)What is the total revenue?
Business Benefit: Tracks top-line financial performance and overall business growth, allowing management to evaluate market expansion and profitability goals.
3)What is the total stock quantity for each category? =SUM(stock_quantity)
Business benefit:Prevents inventory imbalances by identifying stockout risks or overstocking issues, helping optimize holding costs and stock replenishment cycles.
4)What is the average prices of all items in each category? =AVERAGE(price_usd)
Business Benefit: Helps benchmark category pricing strategies, understand product positioning (budget vs. premium), and optimize profit margins per category.
5)What is the average customer rating in each category? =AVERAGE(raing)
Business Benefit: Highlights customer satisfaction levels to identify quality issues or top-performing product lines that require product development improvements.
6)What is the total units sold in each season?
Business Benefit: Uncovers seasonal purchasing trends to optimize seasonal marketing campaigns, promotional timing, and stock clearance strategies.
7)How does the average customer rating vary across different styles?
Business Benefit: Identifies fashion trends and design preferences that resonate most with customers, guiding future fashion design and sourcing decisions.
8)What is the most selling material?
Business Benefit: Guides raw material procurement and supplier negotiations by focusing resources on high-demand fabrics that drive sales.
 

