 E-commerce Customer Behavior Analysis

Project Overview

This project focuses on analyzing **customer behavior in an e-commerce platform** using **SQL and Microsoft Power BI**.
The goal of this analysis is to understand customer demographics, spending patterns, satisfaction levels, and purchasing behavior.



Objectives

* Analyze customer **spending behavior**
* Identify **customer segments** based on demographics
* Understand **customer satisfaction levels**
* Evaluate the **impact of discounts on purchases**
* Identify customers who may be **at risk of churn**



# Dataset Information

The dataset contains customer-level information including:

* Customer ID – Unique identifier for each customer
* Gender – Male / Female
* Age – Customer age
* City – Customer location
* Membership Type – Gold / Silver / Bronze
* Total Spend – Total money spent by customer
* Items Purchased – Total number of items purchased
* Average Rating – Customer rating for purchased products
* Discount Applied – Indicates whether a discount was applied
* Days Since Last Purchase – Helps identify inactive customers
* Satisfaction Level – Satisfied / Neutral / Unsatisfied



#  Data Analysis Using SQL

SQL was used to explore and analyze the dataset.

#  Key SQL Tasks

* Viewing all records from the dataset
* Segmenting customers by **gender, city, and membership**
* Analyzing **customer spending behavior**
* Calculating **average ratings and satisfaction levels**
* Identifying **discount impact on purchases**

Example Query

SQL 
SELECT Gender, COUNT(*) AS Total_Customers
FROM customer
GROUP BY Gender;



# Power BI Dashboard

An interactive dashboard was created using Microsoft Power BI to visualize customer insights.



#  Dashboard KPIs

* Total Customers
* Total Revenue
* Total Items Purchased
* Average Rating




#  Dashboard Visualizations

* Gender Distribution
* Age Group vs Total Spend
* Membership Type Analysis
* Sales by City
* Customer Satisfaction Level
* Discount Impact on Purchases
* Customer Retention Status




# Key Insights

* Customers aged **26–35 contribute the highest spending
* Gold membership customers generate the highest revenue
* Discounts increase purchase activity
* Most customers show a **satisfied experience
* Cities like **San Francisco and New York generate high sales


# Tools & Technologies Used

* SQL (MySQL) – Data exploration and analysis
* Microsoft Power BI – Data visualization and dashboard creation
* Microsoft Word – Report documentation

