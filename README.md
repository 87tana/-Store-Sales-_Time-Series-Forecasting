# Time Series Forecasting, A case study on store sales

<p align="center">
    <img width="400" src="aaa2ac7acafcacaf65cb5768272a55da.gif" alt="Material Bread logo">
</p>


## **Introduction**

This project involves analyzing and predicting sales for a store within Favorita Corporation, a leading supermarket retailer in Ecuador. The objective is to provide actionable insights to store management for effective inventory management and sales strategies. By leveraging sales forecasting techniques and utilizing extensive historical data, the project aims to support Favorita Corporation in optimizing operations and driving higher sales.


## **Goal**

The goal is on developing a reliable model using historical sales data across various products and locations.


## Buisness Understanding:

The objective of this project is to enhance sales performance by studying long-term sales trend, understanding the impact of previous events on sales, identifying potential solutions, and determining the appropriate course of action. The research explores multiple regression approaches to generate predictions.

## Hypothesis Testing 

The sales of stores are influenced by various factors, including oil price, day of the week, season, promotions, and external influences. To investigate these factors, I perform exploratory data analysis (EDA) on each factor and select a specific feature to formulate a hypothesis. Subsequently, I apply A/B testing to evaluate the validity of my hypothesis.


H0 - There is no significant correlation between oil price and increase sales

H1 - There is significant correlation between oil price and increase sales

## Objectives:

- Which dates have the lowest and highest sales for each year?
- Did the earthquake impact sales?
- Are certain groups of stores selling more products? (Cluster, city, state, type)
- Are sales affected by promotions, oil prices and holidays?
- What analysis can we get from the date and its extractable features?
- What is the RMSLE, RMSE, MSLE, MSE from the ML model?


## File Describtion: 

**The project comprises six CSV files, including:**

- **Train**: historical sales data for each product and store combination


- **Test**: future sales data for each product and store combination


- **Store**: store-specific metadata including location and type


- **Transactions**: transactional data for each store and day


- **Holidays and Events**: data on national and religious holidays, as well as other special events


- **Daily Oil Price**: data on the daily price of oil


## Performance Metric Used:

 Evaluated results using regression metrics MSE, RMSE, etc
