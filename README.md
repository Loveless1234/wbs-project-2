# Project objectives 
## Introduction
In this project, the complexity of these tasks, especially is data cleaning section, will require  to use Python with panads, matplot and seaborn, rather than SQL.

The company has high hopes put into the possibilities that come with Data Analysis, and they are especially hopeful that our work can finally settle an ongoing debate: whether or not it’s beneficial to discount products.

* The Marketing Team Lead is convinced that offering discounts is beneficial in the long run. She believes discounts improve customer acquisition, satisfaction and retention, and allows the company to grow.

*  The main investors in the Board are worried about offering aggressive discounts. They have pointed out how the company’s recent quarterly results showed an increase in number of orders, but a decrease in the total revenue. They prefer that the company positions itself in the quality segment, rather than competing to offer the lowest prices in the market.

## 1. clean  the data
It seems like the data extraction process has corrupted some numbers
* Remove duplicate rows
* Deal with products with two dots in the price
* Check for other weird numbers
* Deal with missing values
* Change prices to numeric
* Clean the rest of the DataFrames
## 2. Acess data quality 
Information across different tables should match
* Exclude unwanted orders
* Exclude orders with unknown products
* Explore the revenue from different tables
* Become confident about your dataset

## 3. Answer business questions
This is what management asked.
* How products should be classified into different categories in order to simplify reports and analysis.

* What is the distribution of product prices across different categories.
* How many products are being discounted.
* How big are the offered discounts as a percentage of the product prices.
* How seasonality and special dates (Christmas, Black Friday) affect sales.
* How could data collection be improved.

##  4. Analyze discounts
Provide clarity and context in a company debate: are discounts beneficial?
* Analyzing discounts means looking at which products have been sold
* Discounts are defined as the difference between orderlines.unit_price and products.price. 

## 5. Conclusion
* Limited data
* Missing and corrupted values
* No aggressive discounts in general
