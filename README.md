# pandas-challenge-1
## Module 4 Challenge pandas-challenge-1

# Background
This module challenge focused on data analysis with Python's Pandas library. As a crucial component in various fields, such as data science, machine learning, and business intelligence, practical data analysis involves examining, cleaning, processing, and extracting useful information from large datasets. This assignment provides a hands-on opportunity to develop these skills.

In this challenge, were told to dive into a dataset from a fictional e-commerce company, exploring and analyzing data to address real-world business questions. Mission involves identifying top customers, popular product categories, calculating profits, and more. The goal is to have a practical understanding of data exploration, transformation, and analysis, preparing you for more complex data scenarios in your future career.

# Exploration and Analysis
We will explore data and analyse on many ways
-   Viewing a few Column names of the dataframe from the imported list/data
-   What describe function shows
-   Correctly identify the category with the most entries
-   For the category with the most entries, correctly identify the subcategory with the most entries
-   Correctly identify the 5 clients with the most entries in the data
-   Store the client ids of those top 5 clients in a lis
-   Display the total units (the qty column) that the client with the most entries ordered
-   Also exploring writing formated data to another file

# Data Transformation
-   Created a new column that calculates the subtotal for each line using the unit_price and the qty
-   Created a new column for shipping price. Assume a shipping price of $7 per pound for orders over 50 pounds and $10 per pound for items 50 pounds or under
-   Created a new column for the total price using the subtotal and the shipping price along with a sales tax of 9.25%
-   Created a new column for the cost of each line using unit cost, qty, and shipping price (assume the shipping cost is exactly what is charged to the client)
-   Created a new column for the profit of each line using line cost and line price

# Summary
-  Calculated the total revenue from each of the top 5 clients in Part 1. Also created a summary DataFrame showing the totals for the top 5 clients with the following information: total units purchased, total shipping price, total revenue, and total profit. Sorting by total profit, format the data and rename the columns to names suitable for presentation. Currency should be in millions of dollars. The client ID 24741 generated a total profit of over $36M which it is 12 times over other clients. If this is my business this is one of the clients to make sure their demands are prioritized.


# Appendix
- Seeked consulation from TA @Yuyang Zong on some of the calculation or understanding what exactly the question needed
- Worked with some of the classmates @Arnab Roy and @Joe Timmons





