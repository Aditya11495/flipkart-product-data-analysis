# Project Overview

This project is a real-world Data Analyst case study focused on analyzing e-commerce product data to uncover revenue trends, discount strategies, pricing patterns, and category-level performance.
The objective is to simulate a business scenario where management wants insights into sales performance, pricing effectiveness, and category contribution.

# Business Problem

An e-commerce company wants to answer the following:

Which product categories generate the highest revenue?

Are heavy discounts impacting profitability?

What is the overall pricing distribution?

How are product ratings distributed?

Which categories rely most on discount-based sales?

This project provides data-driven insights to support business decision-making.

# Tech Stack

Python

Pandas

NumPy

Matplotlib

 # Dataset Features

Product ID

Category

Sub-category

Brand

Selling Price

Actual Price (MRP)

Average Rating

Seller

Stock Status

Crawled Date

# Data Cleaning Process


Removed unnecessary columns (e.g., index column)

Handled missing values using business logic:

Missing ratings treated as “Not Rated” (filled with 0)

Missing brand and seller filled with “Unknown”

Missing actual price replaced with selling price (assumed no discount)

Converted price columns to numeric format

Created new derived metrics



# Key KPIs Created

Total Revenue

Average Selling Price

Discount Amount

Discount Percentage

Revenue by Category

Average Discount by Category



**Visualizations Performed**


Revenue by Category (Bar Chart)

Average Discount % by Category

Selling Price Distribution (Histogram)

Rating Distribution

Discount % vs Selling Price (Scatter Plot)


# Key Insights

Identified top revenue-generating categories.

Observed relationship between high discount percentages and pricing levels.

Analyzed product rating distribution across dataset.

Highlighted categories relying heavily on discount strategies.



# Business Recommendations

Optimize discount strategy in categories with high revenue but excessive discounting.

Focus on promoting high-rated products to increase conversion.

Monitor pricing structure to maintain competitive positioning without reducing margins excessively.

