# Product Inventory & Consumer Demographics Analysis

## Overview
This project analyzes product inventory data and provides insights on customer demographics, specifically focusing on **gender distribution** for specific products. 

### Key Insight:
One of the key insights derived from the analysis is the **conditional probability of gender given a product inventory**. For example, given a KP481 treadmill, we can estimate the number of male and female buyers based on the product inventory data.

### Conditional Probability Example:
For the KP481 treadmill:
- If we have 1000 KP481 treadmills in stock:
  - **483 females** are likely to purchase the product based on the probability (48.33%)
  - **517 males** are likely to purchase the product based on the probability (51.67%)

This insight can help in understanding target demographics for marketing strategies and optimizing stock levels based on gender preferences.

# To identify the characteristics of the target audience for each type of treadmill offered by the company, to provide a better recommendation of the treadmills to the new customers.

# Key Features:

   - Performed descriptive analytics to create a customer profile for each AeroFit treadmill product by developing appropriate tables and charts.
   - For each AeroFit treadmill product, constructed two-way contingency tables and compute all conditional and marginal probabilities along with their insights/impact on the business.

Example :
----------------------------------------
Product |KP281	|KP481	|KP781	|All  |
---------------------------------------|
Gender				                     |
Female |	50.0	|48.33	|17.5	   |42.22|
---------------------------------------|
Male	 | 50.0	|51.67	|82.5	   |57.78|
----------------------------------------

Insights- Above table is the conditional probability of the gender given products inventory in percentage

From this table we can answer questions like out of 1000 KP481 treadmill product inventory how many females and males buy it.

we can answer it by
1) 1000*48.33/100 = 483 females will buy KP481 treadmill out of 1000 KP481 treadmills.

2) 1000 *51.67/100 = 517 males will buy KP481 treadmill out of 100 KP481 treadmills.
