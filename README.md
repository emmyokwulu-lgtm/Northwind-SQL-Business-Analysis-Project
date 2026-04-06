# Overview
This project illustrates an end-to-end SQL and Excel data analysis case study using a standard retail dataset 'The Northwind Database'. It demonstrates how to extract, analyse, and present business insights using structured data. The project shows real-world data analyst tasks, from querying databases to communicating business insights through visualisations.
## Objectives
The project aims to:

- Import Data into database and profile the Datasets
- Extract meaningful insights from a relational database (sqlite)
- Apply core SQL concepts to solve business problems
- Present findings using Excel visualisations

## Executive Analysis
This analysis of the Northwind retail dataset provides key insights into customer behaviour, operational efficiency, and overall business performance.

The business demonstrates a strong and active customer base, with 830 total orders generating a revenue of 1,354,458.59, indicating healthy commercial activity. However, performance is not evenly distributed across customers, products, or regions.

The business depends on a handful of big customers, but their high shipping costs is squeezing profits. To maximize earnings, the business should keep these customers loyal while working to cut freight costs and grow mid-tier customers with better cost-to-profit ratios. The busiess should negotiate better shipping rates or explore regional hubs to reduce freight costs for SAVEA, ERNSH, and QUICK
while focusing retention efforts on customers who balance high orders with reasonable freight costs (e.g., FRANK, FOLKO).


Geographically, the USA has the largest share of 13 customers, making it the business' biggest single market. Germany and France follow closely, each with 11 customers, Brazil comes next with 9 and the UK has 7 other listed countries have values less than or equal to 5.
This uneven distribution shows clear regions for expansion and strategic focus.

Regarding Products, some categories have a lot of inventory while others have very little. This shows where the business is focusing most of its investment, but it also points out areas where there may be gaps and opportunities to expand or add more variety.


Operationally, The business has problems with its data and processes. Missing region details in many countries show weak data management, which can affect shipping and how customers are grouped. Additionally, There are 21 shipments still waiting to be sent. This shows delays in the order process, and those delays could make customers unhappy.

On Supplers, the company works with many different suppliers, which lowers the risk of relying too much on any one of them. However, because the supplier base is spread out, the business may miss chances to combine suppliers and cut costs.

The business is doing well overall, but it can perform even better by  improving data quality and fixing process delays, keeping important customers loyal, and expanding into markets with growth potential.

## Dataset


The dataset used is the Northwind SQLite database, downloaded from Kaggle, which contains retail business data across multiple tables, including:
- Customers
- Orders
- OrderDetails
- Products
- Suppliers
- Categories

Northwind SQLite database

## Tools & Technologies
- SQL (SQLite Online)
- Excel (for analysis and visualisation)

## Project Workflow
1. Database Accessing
- Downloaded the Northwind .sqlite database from Kaggle

3. Data Loading
- Imported the Northwind .sqlite database into SQLite Online
- Profiled tables and relationships

5. SQL Analysis/Querying
Wrote and executed queries to answer business-focused questions
Applied concepts such as:
- Distinct
- NULL handling
- Aggregate functions (SUM, COUNT, AVG)
- GROUP BY
- HAVING
- Joins
- Aliasing

4. Data Export
-Exported query results into Excel files

6. Visualisation
- Created visuals (bar, column, line and pie charts) using Excel
- Added titles and structured sheets for clarity

Key Business Questions Solved
List of unique countries where customers are located [Q1](https://github.com/emmyokwulu-lgtm/Northwind-SQL-Business-Analysis-Project/blob/029b795342d19a0f204dbdb4ed65fa597703fadc/Excel%20Files/Question%201.xlsx)

All customers who do not have a region assigned [Q2](https://github.com/emmyokwulu-lgtm/Northwind-SQL-Business-Analysis-Project/blob/029b795342d19a0f204dbdb4ed65fa597703fadc/Excel%20Files/Question%202.xlsx)

Total number of orders placed [Q3](https://github.com/emmyokwulu-lgtm/Northwind-SQL-Business-Analysis-Project/blob/029b795342d19a0f204dbdb4ed65fa597703fadc/Excel%20Files/Question%203.xlsx)

Total revenue using the Order Details table [Q4](https://github.com/emmyokwulu-lgtm/Northwind-SQL-Business-Analysis-Project/blob/029b795342d19a0f204dbdb4ed65fa597703fadc/Excel%20Files/Question%204.xlsx)

Total number of products in each category [Q5](https://github.com/emmyokwulu-lgtm/Northwind-SQL-Business-Analysis-Project/blob/029b795342d19a0f204dbdb4ed65fa597703fadc/Excel%20Files/Question%205.xlsx)

Customers who have placed more than 10 orders [Q6](https://github.com/emmyokwulu-lgtm/Northwind-SQL-Business-Analysis-Project/blob/029b795342d19a0f204dbdb4ed65fa597703fadc/Excel%20Files/Question%206.xlsx)

Average freight cost per customer [Q7](https://github.com/emmyokwulu-lgtm/Northwind-SQL-Business-Analysis-Project/blob/029b795342d19a0f204dbdb4ed65fa597703fadc/Excel%20Files/Question%207.xlsx)

Suppliers who supply more than 5 products [Q8](https://github.com/emmyokwulu-lgtm/Northwind-SQL-Business-Analysis-Project/blob/029b795342d19a0f204dbdb4ed65fa597703fadc/Excel%20Files/Question%208.xlsx)

Countries that have more than 5 customers [Q9](https://github.com/emmyokwulu-lgtm/Northwind-SQL-Business-Analysis-Project/blob/029b795342d19a0f204dbdb4ed65fa597703fadc/Excel%20Files/Question%209.xlsx)

Total number of orders that have not been shipped yet [Q10](https://github.com/emmyokwulu-lgtm/Northwind-SQL-Business-Analysis-Project/blob/029b795342d19a0f204dbdb4ed65fa597703fadc/Excel%20Files/Question%2010.xlsx)

## Key Skills Demonstrated
- SQL querying and Database interaction
- Data cleaning and Validation
- Business-oriented Data analysis
- Data aggregation and Summarisation
- Insight generation and Reporting
- Data visualisation and Storytelling

## Global distribution of Customer base
👉 “The customer base is globally distributed but heavily concentrated in Europe, indicating a strong core market with opportunities for geographic expansion.”

- SQL QUERY


![image alt](https://github.com/emmyokwulu-lgtm/Northwind-SQL-Business-Analysis-Project/blob/029b795342d19a0f204dbdb4ed65fa597703fadc/Images/Query-1.JPG)

![image alt](https://github.com/emmyokwulu-lgtm/Northwind-SQL-Business-Analysis-Project/blob/029b795342d19a0f204dbdb4ed65fa597703fadc/Images/TB-1.JPG)

![image alt](https://github.com/emmyokwulu-lgtm/Northwind-SQL-Business-Analysis-Project/blob/029b795342d19a0f204dbdb4ed65fa597703fadc/Images/TB1-VIS.JPG)

## Incomplete customer data
👉 “Customer data shows widespread missing region information across multiple countries, highlighting a systemic data quality issue that could impact operations and decision-making.”

- SQL QUERY


![image alt](https://github.com/emmyokwulu-lgtm/Northwind-SQL-Business-Analysis-Project/blob/029b795342d19a0f204dbdb4ed65fa597703fadc/Images/Query-2.JPG)

![image alt](https://github.com/emmyokwulu-lgtm/Northwind-SQL-Business-Analysis-Project/blob/029b795342d19a0f204dbdb4ed65fa597703fadc/Images/TB2.JPG)

![image alt](https://github.com/emmyokwulu-lgtm/Northwind-SQL-Business-Analysis-Project/blob/029b795342d19a0f204dbdb4ed65fa597703fadc/Images/TB2-VIS.JPG)

## Order Volume Overview
👉 “The company has handled 830 orders, reflecting strong customer activity and providing a solid foundation for deeper performance and revenue analysis.”

- SQL QUERY


![image alt](https://github.com/emmyokwulu-lgtm/Northwind-SQL-Business-Analysis-Project/blob/029b795342d19a0f204dbdb4ed65fa597703fadc/Images/Query-3.JPG)

![image alt](https://github.com/emmyokwulu-lgtm/Northwind-SQL-Business-Analysis-Project/blob/029b795342d19a0f204dbdb4ed65fa597703fadc/Images/TB-3.JPG)

## Total revenue generated
👉 “The business generated a total revenue of 1,354,458.59, highlighting overall performance while reflecting the impact of pricing and discount strategies.”

- SQL QUERY


![image alt](https://github.com/emmyokwulu-lgtm/Northwind-SQL-Business-Analysis-Project/blob/029b795342d19a0f204dbdb4ed65fa597703fadc/Images/Q4.JPG)

![image alt](https://github.com/emmyokwulu-lgtm/Northwind-SQL-Business-Analysis-Project/blob/029b795342d19a0f204dbdb4ed65fa597703fadc/Images/TB4.JPG)

![image alt](https://github.com/emmyokwulu-lgtm/Northwind-SQL-Business-Analysis-Project/blob/029b795342d19a0f204dbdb4ed65fa597703fadc/Images/TB4-VIS.JPG)

## Product Performance
👉 “Product distribution is uneven across categories, with a few categories dominating inventory, indicating focused investment areas and potential gaps for expansion.”

- SQL QUERY


![image alt](https://github.com/emmyokwulu-lgtm/Northwind-SQL-Business-Analysis-Project/blob/029b795342d19a0f204dbdb4ed65fa597703fadc/Images/Q5.JPG)

![image alt](https://github.com/emmyokwulu-lgtm/Northwind-SQL-Business-Analysis-Project/blob/029b795342d19a0f204dbdb4ed65fa597703fadc/Images/TB5.JPG)

![image alt](https://github.com/emmyokwulu-lgtm/Northwind-SQL-Business-Analysis-Project/blob/029b795342d19a0f204dbdb4ed65fa597703fadc/Images/TB5-VIS.JPG)

## High-Value Customers
👉 “A small group of repeat customers drives a large share of orders, highlighting key accounts for retention and opportunities to increase order frequency among mid-tier customers.”

- SQL QUERY


![image alt](https://github.com/emmyokwulu-lgtm/Northwind-SQL-Business-Analysis-Project/blob/029b795342d19a0f204dbdb4ed65fa597703fadc/Images/Q6.JPG)

![image alt](https://github.com/emmyokwulu-lgtm/Northwind-SQL-Business-Analysis-Project/blob/029b795342d19a0f204dbdb4ed65fa597703fadc/Images/TB6.JPG)

![image alt](https://github.com/emmyokwulu-lgtm/Northwind-SQL-Business-Analysis-Project/blob/029b795342d19a0f204dbdb4ed65fa597703fadc/Images/TB6-VIS.JPG)


## Average Order Value
👉 “Freight costs are unevenly distributed, with a small group of customers driving a large share of shipping expenses, while most customers maintain relatively low average costs.”

- SQL QUERY
![image alt](https://github.com/emmyokwulu-lgtm/Northwind-SQL-Business-Analysis-Project/blob/029b795342d19a0f204dbdb4ed65fa597703fadc/Images/Q7.JPG)

![image alt](https://github.com/emmyokwulu-lgtm/Northwind-SQL-Business-Analysis-Project/blob/029b795342d19a0f204dbdb4ed65fa597703fadc/Images/TB7.JPG)

![image alt](https://github.com/emmyokwulu-lgtm/Northwind-SQL-Business-Analysis-Project/blob/029b795342d19a0f204dbdb4ed65fa597703fadc/Images/TB7-VIS.JPG)

## Suppliers with Multiple Products
👉 “No supplier dominates product supply, indicating a diversified supplier base with reduced risk but potential opportunities for strategic supplier consolidation”.


- SQL QUERY

![image alt](https://github.com/emmyokwulu-lgtm/Northwind-SQL-Business-Analysis-Project/blob/029b795342d19a0f204dbdb4ed65fa597703fadc/Images/Q8.JPG)

![image alt](https://github.com/emmyokwulu-lgtm/Northwind-SQL-Business-Analysis-Project/blob/029b795342d19a0f204dbdb4ed65fa597703fadc/Images/TB8.JPG)

![image alt](https://github.com/emmyokwulu-lgtm/Northwind-SQL-Business-Analysis-Project/blob/029b795342d19a0f204dbdb4ed65fa597703fadc/Images/TB8-VIS.JPG)


## Countries with High Customer Base
👉 “Customer distribution is concentrated in a few key markets, with USA leading, indicating strong expansion opportunities and clear priority regions for growth.”

- SQL QUERY

![image alt](https://github.com/emmyokwulu-lgtm/Northwind-SQL-Business-Analysis-Project/blob/029b795342d19a0f204dbdb4ed65fa597703fadc/Images/Q9.JPG)

![image alt](https://github.com/emmyokwulu-lgtm/Northwind-SQL-Business-Analysis-Project/blob/029b795342d19a0f204dbdb4ed65fa597703fadc/Images/TB9.JPG)

![image alt](https://github.com/emmyokwulu-lgtm/Northwind-SQL-Business-Analysis-Project/blob/029b795342d19a0f204dbdb4ed65fa597703fadc/Images/TB9-VIS.JPG)


## Delayed or unshipped Orders
👉 “21 pending shipments highlight potential fulfilment delays, signalling the need for improved operational efficiency and order tracking.”

- SQL QUERY

![image alt](https://github.com/emmyokwulu-lgtm/Northwind-SQL-Business-Analysis-Project/blob/029b795342d19a0f204dbdb4ed65fa597703fadc/Images/Q10.JPG)


![image alt](https://github.com/emmyokwulu-lgtm/Northwind-SQL-Business-Analysis-Project/blob/029b795342d19a0f204dbdb4ed65fa597703fadc/Images/TB10.JPG)

## Purpose
This project was designed to demonstrate practical SQL and Excel data analysis skills required for entry-level data analyst roles. It showcases the ability to work with real datasets, generate insights, and present findings in a clear and structured manner.

## Author
Okwulu Emmanuel

Data Analyst | Sales Operator












