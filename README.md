# Pizza_Sales_Report

![](PizzaImage.jpg)

## Introduction
This project was done for a fictional pizza place. The aim was to analyze the data and put together a report to help find opportunities to drive more sales and work more efficiently. The dataset has a year's worth of sales and contains 4 different tables in CSV format namely; Orders, Order Details, Pizzas, and Pizza Types. The data also came with a data dictionary and a project brief.

## Problem Statement
The following questions were stated in the project brief;
- What days and times do we tend to be busiest? 
- What are our best and worst selling pizzas? 
- What's our average order value? 
- How much money did we make this year? Can we identify any seasonality in the sales? 

## Power BI tools used:
- DAX
- New measures
- Power query

## Analysis
### Data Sourcing
This data was gotten from [Kaggle.com](https://www.kaggle.com/datasets/mysarahmadbhat/pizza-place-sales)

### Data Cleaning
Before loading to power query on power BI, I merged all the data from the different tables to one csv file using microsoft excel. 
In power query, I changed the data types, etc
split the "Time" column in the Orders Table by the space delimeter because it had date also.
Removed "the" and "pizza" from pizza name


