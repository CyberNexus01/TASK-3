Pizza Sales Data Analysis

Overview

This document explains the analysis of our pizza sales data. We looked at the data to understand how sales are doing, what customers like, and important numbers about our business. This helps us make smarter choices.

Dataset Description

The data is organized into four main tables:

pizza: This table has information about each pizza, like its ID, type, size, and price.
pizza_types: This table tells us about the different kinds of pizzas we offer, including their names, categories, and what's in them.
orders: This table keeps track of customer orders, including the order number, date, and time.
order_details: This table connects orders to the ordered pizzas, and how many of each pizza were included.

Analysis Performed

The SQL code we used (in the file "Pizza_Sales.sql") does these things:

Order Analysis:
    Finds the total number of orders.
    Calculates the average number of pizzas ordered each day.
    Shows when orders happen throughout the day.
Revenue Analysis:
    Calculates the total money made from pizza sales.
    Finds the 3 best-selling pizzas (by money made).
    Calculates how much money each pizza type brings in.
    Shows how money has come in over time.
    Finds the 3 best-selling pizzas in each category.
Product Analysis:
    Find the most expensive pizza.
    Finds the most common pizza size.
    Lists the 5 most popular pizzas (by number ordered).
    Shows how many pizzas were ordered from each category.
    Shows how many different pizzas we have in each category.

Key Insights

This analysis helps us understand:

How well we're selling (total orders, total money).
What customers prefer (popular pizzas and sizes).
How our business works (when orders come in).
What makes us the most money (best-selling items and categories)?

Files Included

Pizza_Sales.sql: This is the code we used to analyze the data.

How to Use

1.  Run the code ("Pizza_Sales.sql") on the database with the pizza sales data.
2.  Look at the results to see the numbers and information.
3.  Use this information to make decisions about our menu, marketing, and how we run things.
