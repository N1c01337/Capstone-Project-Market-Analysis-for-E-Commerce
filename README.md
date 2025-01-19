# Capstone-Project-Market-Analysis-for-E-Commerce

## _Analysing the Market_
[![Image from Gyazo](https://i.gyazo.com/c41db336d13d107df559d988b563db2e.png)](https://i.gyazo.com/c41db336d13d107df559d988b563db2e.png)
#

### Description of Dataset
2 Datasets were provided. Customer and Purchase. 
The Customer dataset provide information on customer details such as their name, gender and age. The data columns are customer_id, first_name, last_name, gender, age, country and income. It consist of 1002 rows and 7 Columns.

The Purchase dataset contains order purchases made by customers with information such as the purchased item, quantity, and ordered date. The data columns are order_id,customer_id,product_name,description,price	discount,tax,order_date,quantity,shipping_cost,shipping_date. It consists of 5001 rows and 11 Columns


### Objective
Understanding the groups that our customer fall under.
Understanding the revenue earned over the years. 
Identify purchase trends and patterns.



#### Data Transformation
* For the customer data set, the customer firstname and lastname columns were merged to form the full name column and a conditional column was added to categorize age into different groups.
* For the purchase data set, a new calculation column was added to calculate revenue earned using the price,discount,quantity,tax and shipping column.

### Observations
[![Image from Gyazo](https://i.gyazo.com/ed3038196b0896e99708bfa66f00f4e9.png)](https://i.gyazo.com/ed3038196b0896e99708bfa66f00f4e9.png)
#### Customers
* Gender: The overall ratio of Male and Females is pretty even with it skewing slightly to Males.
* Income: The average income shows that Brazil customer’s are more well off than other countries but has lower amount of customers.  
* Age Group: Majority of the customer are amongst the age of 20 - 59
* Quantity: The biggest bulk of our customer is from Columbia with Chile coming in second 



[![Image from Gyazo](https://i.gyazo.com/03c71c9256c32c60116d657f24b6444e.png)](https://i.gyazo.com/03c71c9256c32c60116d657f24b6444e.png)

#### Revenue
* Highest earning Country: The country with the highest revenue was Colombia
* Highest rise period: *The highest rise in revenue was from August 2019- October 2019 with the monthly revenue going from below $4M earned to almost $8M earned.
* Highest drop period: The highest drop in revenue was the transition from December 2022 to Jan 2023 with every country revenue dropping under 100k from millions. 


[![Image from Gyazo](https://i.gyazo.com/6cb1178f94e0d98ba0f0822d34f635d0.png)](https://i.gyazo.com/6cb1178f94e0d98ba0f0822d34f635d0.png)

#### Purchase Trend and Pattern
* Highest earning products: From the market trend and product earning it is apparent that products which function as home décor and appliances have the highest earning throughout the years.  
* Quantity Sold: The total quantity of each product sold is relatively similar with it ranging from 8.6k units to 9.6ks units. 
* Lowest earning product: Products that function as clothing and footwear have the lowest earning. 

Despite the similar amount of quantity in sales, there is a huge disparity in the earnings between the highest and lowest earning. This is likely due to the price of the products

### Recommendations base on analysis!

Introduce products designs targeting the specific age group
*	By comparing a product to its worst selling age group, we can introduce more suitable product designs for that age group hence possibly seeing an increase of sales for that product

Research on products designs for the Brazilian market
* Brazil has a lower revenue count than Mexico despite being wealthier and having more orders. This could be because they are mostly purchasing items of lower price. By releasing designs more suitable for the Brazilian market, we may see an increase in higher priced products hence increasing the revenue.

Consider raising the prices for clothing and foot wear products
* The market trend shows that there is a constant steady revenue for these products, we can try raising the price of the products to test its elasticity.  If the product has high elasticity, we will see a higher increase in the revenue.

Investigate the reasons for drop in revenue when transiting to 2023
* From the dataset visualization, it is very apparent that there is a massive decrease in sales across all branches despite it maintaining a steady revenue of over 80 million per year and  a couple of millions per month from 2019-2022. This is highly due to external or internal reasons which should be investigated.

## Connect with Me!
Interested in working with me? Send me a DM on [Linkedin!](https://www.linkedin.com/in/nico-tham/)







