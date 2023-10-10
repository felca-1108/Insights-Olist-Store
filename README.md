# Insights-Olist-Store

The main goal of this project is to analyze Olist Store data and then discover insights that could help business managers on decision making. 

Olist is the largest department store in Brazilian marketplaces. Olist connects small businesses from all over Brazil to channels without hassle and with a single contract. Those merchants are able to sell their products through the Olist Store and ship them directly to the customers using Olist logistics partners.

This project consists in a complete BI process, which begins with ETL process and ends with the creation of dashboards. I used Power BI to make all the analysis and dashboards.

Using public dataset of orders from 2016 to 2018 made at Olist Store, this project will provide business managers insights about the sources of revenue, costumer satisfaction, most used payment methods, among others.
For that, I used seven datasets made available in Kaggle website, https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce, as shown below:

- olist_costumers_dataset
- olist_order_items_dataset
- olist_order_payments_dataset
- olist_order_reviews_dataset
- olist_orders_dataset
- olist_products_dataset
- olist_sellers_dataset

First of all, I began with an ETL process. I extracted all these csv files, and then made some simple transformations, as dropping columns, dropping rows with no information, among others. Then I loaded all the datasets.
After loading the datasets, it was time to make the data modeling. It was used the data schema shown in Kaggle page.

Said that, all calculations and analysys were carried out and then the dashboards were made. There are three dashboards, as shown below.

- The first one shows a revenue analysis. We can look at how the revenue is distributed across product categories, for month and for costumer locations. The distribution of revenue among the months is splitted in the price of the product and the freight value.
- The second one shows an analysis of the revenue by the payment method and by the supplier. 
- The third one shows details about the costumer satisfaction. We can look at the distribution of the scores given by costumers and see how they vary by consumers locations. There's still a donut chart classifying the satisfaction as "Good" or "Bad". "Good" means a score of 4 or 5 and "Bad" means a score below 4.

All of the dashboards can be analyzed by year, that is 2016, 2017 or 2018.

I think all the goals of this project were hit, as we can get a great overview of Olist revenue sources, paymet methods, costumers, and others, and as the dashboards certainly can help the business managers to undertand the business directions. The correct use of the dashboards can also help them with decision making.

