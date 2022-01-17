# Sec_3_Pandas
Notes from intro:
that your work can finally settle an ongoing debate: whether or not it’s beneficial to discount products
The Marketing Team Lead is convinced that offering discounts is beneficial in the long run. She believes discounts improve customer acquisition, satisfaction and retention, and allows the company to grow.
The main investors in the Board are worried about offering aggressive discounts. They have pointed out how the company’s recent quarterly results showed an increase in number of orders, but a decrease in the total revenue. They prefer that the company positions itself in the quality segment, rather than competing to offer the lowest prices in the market.

How products should be classified into different categories in order to simplify reports and analysis.
What is the distribution of product prices across different categories.
How many products are being discounted.
How big are the offered discounts as a percentage of the product prices.
How seasonality and special dates (Christmas, Black Friday) affect sales.
How could data collection be improved.

Questions:
What is included in "total paid"?
What does "processing of that product" timestamp mean?
Products also contains price and promo price
does df.column_name.value_counts() gives total of unique values under length?


data type object, ought to be numeric probably: 
    orders: created date
    orderlines: unit_price and date
    products: price, promo_price and type ("a numerical code for product type")
    brands: none

Answers to questions:
How many orders are there? - 226909
How many products are there? - 10579
What period of time do these orders comprise? - 01.01.2017 until 14.03.2018
How many orders are Completed? - 46605
How should revenue be computed? total paid for completed orders

