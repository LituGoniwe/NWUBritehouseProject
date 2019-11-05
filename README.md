# NWU Britehouse Project 2019

# Project Brief
This project requires the development of a MVC webapp which provides visualisations and insights into the superstore dataset that will be provided. Access to the system needs to be securely managed by user registration and login. 

# Architecture
The recommended approach would be to use ASP.NET  MVC

# Data
A dataset will be provided which consists of three subsets of data, namely: Orders, returns and regional managers.
The orders subset contains data pertaining to purchase orders made from across the world. The dataset records orders for a large number of products ordered along with attributes such as quantity sold, price, discount, etc.
The returns subset contains an order ID which links to an order made, along with the region it was returned to.
The regional managers subset contains the name of the regional manager, along with the region they manage.
The data will be provided in CSV format and requires the student to store the data in a NoSQL data source. The NoSQL structure should encapsulate orders, returns attached to the order as well as the regional manager pertaining to the order.

# Analysis and Visualisation
Various libraries and tools exist that allow for data visualization. There is a lot of analysis that can be done on the provided dataset, some of which includes:
• Location insights, based on:
o Country
o Region
o State
o City
o Postal Code
o Market
• Product purchases over time
• Correlation of returns with products
• Determining how often products are purchased in one region and returned in another
• Determining trends of returns over time
• Determining relationships between product purchases and location
• Determining relationship between location and category and subcategory
• Determining trends between order priority and shipping/ order date
• Determining trends between order priority and location
• Determining trends between order priority and product
• Determining relationship of economic state with Sales, profit, discount, shipping cost, quantity
• Determining roughly where products where shipped from based on shipping cost and location info
