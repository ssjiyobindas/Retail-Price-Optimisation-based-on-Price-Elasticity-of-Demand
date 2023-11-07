# Retail-Price-Optimisation-based-on-Price-Elasticity-of-Demand

In this machine learning pricing project, we implement a retail price optimization algorithm using regression trees. This is one of the first steps to building a dynamic pricing model.

# Project Description
### Tools and Techniques covered in this project

In detail, let us discuss all tools and techniques we will explore in this project.

**Price Optimization Algorithms**

Understanding customer behavior through sales data is crucial for the growth of any business. Not only it contributes to improved quality of products, but it additionally assists in determining the right price for the different products. For instance, products perceived as luxury items by the masses are sold at unreasonably high prices. In this dynamic pricing python project, we will use previous sales data to estimate the cost of different food items in a cafe. Additionally, we will explore other price optimization methods like cost-less pricing, competition-based pricing, perceived value pricing, and demand-based pricing.

**Exploratory Data Analysis**

Before the price optimization dataset is used for modeling, it must be processed. The dataset may contain redundancy that one must remove, and one must bring on all the variables of different data types on the same foot. In this project, we will work on the dataset of a burger cafe and use their three datasets related to sales, transactions, and corresponding dates. The data is stored in a PostgreSQL database hosted on Amazon RDS and psycopg2 library used to fetch the data from Postgres database to Python. We will visualize the dataset using data visualization libraries of Python: matplotlib and seaborn. Then we merge the datasets and prepare them to apply machine learning algorithms using Pandas dataframes.

**Machine Learning Algorithms**

Instead of traditional statistical methods of price estimation, this project will perform price optimization using machine learning in Python. We will use regression trees and ordinary least square method to estimate the price elasticity for different products. Furthermore, we will look at how statistical parameters like the r-squared value are interpreted for analysis. We also improve the accuracy of the models by eliminating specific variable values. Additionally, we will explore maximizing profit using the results of price elasticities evaluation.

**Application of Machine Learning for Pricing Optimization in Python Project**

Primarily, this project focuses on optimizing the prices of various items available in a burger cafe. The solution of this pricing optimization in Python project can be easily used by experts of different industries like medical, hospitality, insurance, etc. For example, an analyst can recommend changes to the prices of various services offered by a hotel depending on the previous residents’ feedback.

**FAQs for Pricing Optimization with Machine Learning**

1) How do you do Price Optimization?

One can apply different types of price optimization techniques like reducing cannibalization for inter and intra products of the same company, reducing cost drastically while playing a volume game etc.

2) What is Price Optimization Machine learning?

Price Optimization can be achieved using regression machine learning algorithms like linear regression. One can first estimate the price elasticity for each product using the past sales data and then use that coefficient for price optimization.

# Introduction to price optimization
Pricing a product is a crucial aspect in any business. A lot of thought process is out into it. There are different strategies to price different kinds of products. There are products whose sales are quite sensitive to their prices and as such a small change in their price can lead to noticeable change in their sales. While there are products whose sales are not much affected by their price - these tend to be either luxury items or necessities (like certain medicines). This notebook will focus on the former type of products.

Price elasticity of demand (Epd), or elasticity, is the degree to which the effective desire for something changes as its price changes. In general, people desire things less as those things become more expensive. However, for some products, the customer's desire could drop sharply even with a little price increase, and for other products, it could stay almost the same even with a big price increase. Economists use the term elasticity to denote this sensitivity to price increases. More precisely, price elasticity gives the percentage change in quantity demanded when there is a one percent increase in price, holding everything else constant.

Mathematically speaking, the price elasticity of demand is defined to be the percentage change in quantity demanded, q,divided by the percentage change in price, p. The formula for the price elasticity (ǫ) is: $$e = \%ΔQ/ \%ΔP$$

### Business Problem Statement
In this machine learning pricing optimization case study, we will take the data of a cafe and, based on their past sales, identify the optimal prices for their items based on the price elasticity of the items. This cafe sells burgers, coke, lemonade and coffee. As a data scientist, it is our task to figure out the optimal prices to set for these items. If the price is set too high, the sales will drop & the price is set to low, then the margins will decrease. What is the sweet spot that will give us the maximum profit?
### Dynamic Pricing Dataset

The data is contained in three CSV files.

**Cafe - Sell MetaData.csv** This file has details about sales made by the cafe.
Columns: Sell ID, Sell Category, Item ID, Item Name

**Cafe - Transaction - Store.csv** This file contains information about transactions and sale receipts of the cafe.
Columns: Calendar Date, Price, Quantity, Sell ID, Sell Category

**Cafe - DateInfo.csv** This has date information corresponding to the transactions performed.
Columns: Date, Year, Holiday, Weekend, School Break, Temperature, Outdoor

### Tools and Techniques covered in this project

In detail, let us discuss all tools and techniques we will explore in this project.

**Price Optimization Algorithms**

Understanding customer behavior through sales data is crucial for the growth of any business. Not only it contributes to improved quality of products, but it additionally assists in determining the right price for the different products. For instance, products perceived as luxury items by the masses are sold at unreasonably high prices. In this dynamic pricing python project, we will use previous sales data to estimate the cost of different food items in a cafe. Additionally, we will explore other price optimization methods like cost-less pricing, competition-based pricing, perceived value pricing, and demand-based pricing.

**Exploratory Data Analysis**

Before the price optimization dataset is used for modeling, it must be processed. The dataset may contain redundancy that one must remove, and one must bring on all the variables of different data types on the same foot. In this project, we will work on the dataset of a burger cafe and use their three datasets related to sales, transactions, and corresponding dates. The data is stored in a PostgreSQL database hosted on Amazon RDS and psycopg2 library used to fetch the data from Postgres database to Python. We will visualize the dataset using data visualization libraries of Python: matplotlib and seaborn. Then we merge the datasets and prepare them to apply machine learning algorithms using Pandas dataframes.

**Machine Learning Algorithms**

Instead of traditional statistical methods of price estimation, this project will perform price optimization using machine learning in Python. We will use regression trees and ordinary least square method to estimate the price elasticity for different products. Furthermore, we will look at how statistical parameters like the r-squared value are interpreted for analysis. We also improve the accuracy of the models by eliminating specific variable values. Additionally, we will explore maximizing profit using the results of price elasticities evaluation.

**Application of Machine Learning for Pricing Optimization in Python Project**

Primarily, this project focuses on optimizing the prices of various items available in a burger cafe. The solution of this pricing optimization in Python project can be easily used by experts of different industries like medical, hospitality, insurance, etc. For example, an analyst can recommend changes to the prices of various services offered by a hotel depending on the previous residents’ feedback.

**FAQs for Pricing Optimization with Machine Learning**

1) How do you do Price Optimization?

One can apply different types of price optimization techniques like reducing cannibalization for inter and intra products of the same company, reducing cost drastically while playing a volume game etc.

2) What is Price Optimization Machine learning?

Price Optimization can be achieved using regression machine learning algorithms like linear regression. One can first estimate the price elasticity for each product using the past sales data and then use that coefficient for price optimization.
