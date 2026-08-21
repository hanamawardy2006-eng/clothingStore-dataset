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

Business questions:

1)What is the total volume of units sold across all categories? =SUM(units_sold)

2)What is the total revenue?

3)What is the total stock quantity for each category? =SUM(stock_quantity)
.
4)What is the average prices of all items in each category? =AVERAGE(price_usd)

5)What is the average customer rating in each category? =AVERAGE(raing)

6)What is the total units sold in each season?

7)How does the average customer rating vary across different styles?

8)What is the most selling material?

 

