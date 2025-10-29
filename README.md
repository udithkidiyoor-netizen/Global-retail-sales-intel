Global Electronics Retailer: Sales and Customer Insights
Overview

This project analyzes sales, customer, and store data for a fictional global electronics retailer.
The goal is to understand how different products, regions, and customer segments contribute to overall performance.
It includes data cleaning, preparation, and analysis using SQL and Excel (Power Query and dashboards).

Table of Contents

Project Background

Data Structure

Data Preparation

Executive Summary

Key Insights

Recommendations

Resources

Tools Used

Project Background

A global retailer offers a wide range of electronic products across different countries.
This project focuses on understanding how product categories perform, what drives customer purchases, and where growth opportunities exist.
The insights are drawn from detailed sales transactions, customer demographics, product details, and store information.

The main goals are to:

Analyze revenue and profit across categories and regions

Study customer demographics and behavior

Evaluate market performance by country

Create an interactive Excel dashboard for reporting

Data Structure

The dataset contains five related tables with a total of about 62,000 records:

Table	Description
Sales	Contains transaction-level data including order date, customer, product, and quantity
Customers	Includes customer demographics such as age, gender, and location
Products	Describes product attributes including brand, category, and pricing
Stores	Contains store details such as location, size, and open date
Exchange Rates	Includes currency conversion data to standardize sales across countries
Data Preparation

Data was cleaned and transformed in Excel Power Query.
The following steps were taken:

Removed duplicates and empty records

Standardized date and currency formats

Merged all tables into a single dataset using relationships such as customer_key, store_key, and product_key

Filtered the exchange rate data to include only USD for consistent reporting

Created new calculated columns:

Revenue = Quantity × Unit Price

Total Cost = Quantity × Unit Cost

Profit = Revenue − Total Cost

Age = Difference between today’s date and the customer’s birthdate

Executive Summary

The analysis shows that desktop PCs and similar high-value products are the main drivers of sales and profit.
The computers category leads with around $19.3M in revenue and $12.28M in profit, while games and toys contribute the least.
Home appliances have the highest average order value, showing customers are willing to spend more on premium products.
The United States generates the most revenue, while France and other regions contribute less.
2019 was the strongest year for sales, followed by a noticeable decline in 2021, partly due to incomplete data and the impact of COVID-19.

Key Insights
Revenue and Product Performance

Desktop PCs and LCD HDTVs are the top-performing products.

The computers category leads overall revenue, while games and toys lag behind.

Home appliances have the highest average order value, suggesting room for premium positioning.

Market Performance

The United States contributes the largest share of total revenue.

France and other European countries show weaker performance and potential for growth.

Sales peaked in 2019 and declined in 2021 due to incomplete or disrupted data.

Customer Insights

Seniors form the largest customer group, followed by adults and young adults.

Gender distribution is nearly equal, with 51% male and 49% female customers.

The United States, United Kingdom, and Canada have the highest customer counts.

The repeat customer rate is about 53%, indicating solid customer loyalty.

Retention rates dropped after 2019, suggesting the need for better engagement strategies.

Recommendations

Focus on high-value products
Continue developing and promoting desktop PCs and HDTVs, as they generate strong revenue and profit.

Improve sales for low-value items
Use promotions, bundles, or seasonal discounts to boost demand in categories like games and toys.

Leverage customer loyalty
Introduce reward or referral programs to increase repeat purchases.

Expand into weaker markets
Focus on regions such as France with targeted marketing and local partnerships.

Address declining retention
Re-engage customers through personalized offers, communication, and product recommendations.

Resources

Data cleaning process: [link here]

SQL queries used: [link here]

Interactive Excel dashboard: [link here]


Tools Used

Microsoft Excel (Power Query, Pivot Tables, Dashboards)

SQL for data extraction and joins

GitHub for documentation and version control

Power BI (optional visualization)

Author

Udith P. Kidiyoor
M.Sc Business Analytics | Data Analytics | SQL | Excel | Power BI
GitHub: https://github.com/udithkidiyoor-netizen
