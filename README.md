# Global Electronics Retailer: Sales and Customer Insights

## Overview  
This project analyzes sales, customer, and store data for a fictional global electronics retailer.  
The goal is to understand how different products, regions, and customer segments contribute to overall performance.  
It includes data cleaning, preparation, and analysis using SQL and Excel (Power Query and dashboards).

---

## Table of Contents
1. [Project Background](#project-background)  
2. [Data Structure](#data-structure)  
3. [Data Preparation](#data-preparation)  
4. [Executive Summary](#executive-summary)  
5. [Key Insights](#key-insights)  
6. [Recommendations](#recommendations)  
7. [Resources](#resources)  
8. [Tools Used](#tools-used)

---

## Project Background  
A global retailer offers a wide range of electronic products across different countries.  
This project focuses on understanding how product categories perform, what drives customer purchases, and where growth opportunities exist.  
The insights are drawn from detailed sales transactions, customer demographics, product details, and store information.

**Main objectives:**
- Analyze revenue and profit across categories and regions  
- Study customer demographics and behavior  
- Evaluate market performance by country  
- Create an interactive Excel dashboard for reporting  

---

## Data Structure  
The dataset contains five related tables with a total of about **62,000 records**:

| Table | Description |
|--------|-------------|
| **Sales** | Transaction-level data including order date, customer, product, and quantity |
| **Customers** | Customer demographics such as age, gender, and location |
| **Products** | Product attributes including brand, category, and pricing |
| **Stores** | Store details such as location, size, and open date |
| **Exchange Rates** | Currency conversion data to standardize sales across countries |

---

## Data Preparation  
Data was cleaned and transformed in **Excel Power Query**.  
Key steps included:

- Removing duplicates and empty records  
- Standardizing date and currency formats  
- Merging all tables using keys like `customer_key`, `store_key`, and `product_key`  
- Filtering exchange rates to include only USD for consistent reporting  
- Creating calculated columns:
  - **Revenue** = Quantity × Unit Price  
  - **Total Cost** = Quantity × Unit Cost  
  - **Profit** = Revenue − Total Cost  
  - **Age** = TODAY() − Birthday  

---

## Executive Summary  
The analysis shows that desktop PCs and other high-value products are the main drivers of sales and profit.  
The **Computers** category leads with around **$19.3M in revenue** and **$12.28M in profit**, while **Games and Toys** contribute the least.  
Home appliances have the highest average order value, showing customers are willing to spend more on premium products.  
The **United States** generates the most revenue, while **France** and other regions contribute less.  
**2019** was the strongest sales year, followed by a decline in 2021 due to incomplete data and the pandemic impact.

---

## Key Insights  

### Revenue and Product Performance  
- Desktop PCs and LCD HDTVs are the top-performing products.  
- The **Computers** category leads overall revenue; **Games and Toys** lag behind.  
- Home appliances have the highest average order value, suggesting a premium positioning opportunity.  

### Market Performance  
- The **United States** contributes the largest share of total revenue.  
- **France** and other European countries show lower sales potential.  
- Sales peaked in **2019**, declining in **2021** due to incomplete or disrupted data.  

### Customer Insights  
- **Seniors** form the largest customer group, followed by adults and young adults.  
- Gender distribution is nearly equal: **51% male**, **49% female**.  
- The U.S., U.K., and Canada have the highest customer counts.  
- **Repeat Customer Rate:** 53%, showing solid loyalty.  
- **Retention Rate:** Peaked at 89.45% in 2019, then declined after 2020.  

---

## Recommendations  

1. **Focus on high-value products**  
   Continue developing and promoting desktop PCs and HDTVs, as they drive strong revenue and profit.  

2. **Boost sales for low-value items**  
   Use promotions, bundles, or discounts to increase sales in categories like games and toys.  

3. **Leverage customer loyalty**  
   Introduce loyalty or referral programs to increase repeat purchases.  

4. **Expand into weaker markets**  
   Focus on France and similar regions with targeted campaigns and partnerships.  

5. **Improve customer retention**  
   Use personalized marketing and engagement strategies to rebuild post-2019 retention levels.  

---

## Tools Used  
- Microsoft Excel (Power Query, Pivot Tables, Dashboards)  
- SQL (data extraction and joins)  
- GitHub (version control and documentation)  
- Power BI (optional visualization)

---

## Author  
**Udith P. Kidiyoor**  
M.Sc Business Analytics | Data Analytics | SQL | Excel | Power BI  
GitHub: [https://github.com/udithkidiyoor-netizen](https://github.com/udithkidiyoor-netizen)
