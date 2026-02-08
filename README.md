INSY 8311 – SQL JOINs & Window Functions Assignment
Student Information
Name: UMUTONI Hussina
Id: 28222
Course: Database Development with PL/SQL (INSY 8311)
Instructor: Eric Maniraguha
Assignment: SQL JOINs & Window Functions

Business Problem
Business Context

A retail company operating in multiple regions, within the Sales Department of the retail industry.

Data Challenge

The company stores customer, product, and sales transaction data but lacks analytical reporting to evaluate performance across regions and time periods. Management cannot easily identify top-selling products, customer behavior, or sales trends.

Expected Outcome

Provide actionable insights to support sales strategy decisions, product prioritization, and customer segmentation using SQL JOINs and window functions.

Success Criteria

Identify the top-performing products per region using RANK()
Calculate running monthly sales totals using SUM() OVER()
Measure period-to-period sales growth using LAG()
Segment customers into spending quartiles using NTILE(4)
Analyze sales trends using aggregate window functions

Database Schema

The database consists of three related tables:
customers
products
sales
An ER diagram is included to illustrate primary and foreign key relationships.

Part A: SQL JOINs Implementation

INNER JOIN: Retrieved valid sales transactions with customers and products
LEFT JOIN: Identified customers with no purchase history
RIGHT JOIN: Detected products with no sales activity
FULL OUTER JOIN: Compared customers and products including unmatched records
Each JOIN query includes screenshots and business interpretation.

Part B: Window Functions Implementation

Ranking Functions: Identified top products per region
Aggregate Window Functions: Calculated running totals and trends
Navigation Functions: Compared sales across periods
Distribution Functions: Segmented customers into quartiles
Screenshots and interpretations are provided for each query.

Results Analysis
Descriptive Analysis

Sales were concentrated in the East region, with laptops generating the highest revenue.

Diagnostic Analysis

Higher sales performance was driven by repeat customers and higher-value products.

Prescriptive Analysis

The company should target inactive customers with promotions and increase marketing efforts in underperforming regions.

References

Oracle SQL Documentation
Course lecture notes and tutorials

Academic Integrity Statement

“All sources were properly cited. Implementations and analysis represent original work. No AI generated content was copied without attribution or adaptation.”
