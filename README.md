# Coffee Shop Analysis

## Tools Used: Microsoft Excel

## Introduction  
This dataset deals with transaction information related to product performance. It includes the following, product details, location details, purchase details and Transaction time.  Analysing and visualizing this dataset will provide valuable insights into product and Store location performance. 

## Problem Statement
I want to determine the product performance and identify the key factors influencing the product behaviour and propose actionable recommendation to enhance the product performance.

## Project Scope
1. Transaction Pick Periods:
- Investigate consumer behaviours during different times of the day: morning, afternoon, and evening. Analyse percentage transaction volume, and popular products during each period.
- =IF(AND(C10>=TIME(7,0,0), C10<TIME(12,0,0)), "Morning", IF(AND(C10>=TIME(12,0,0), C10<TIME(16,0,0)), "Afternoon", "Evening"))

2. Percentage Monthly Performance:
 

-	Calculate the percentage change in transactions within the month in view. Identify the time of the day when the business thrives.
3.	Product Performance:
•	Top 5 Products: Determine the best-selling products based on transaction count. Understand why these products perform well.
•	Least 6 Products: Examine the least popular products. Identify potential reasons for their lower performance.
4.	Store Location Performance:
•	Compare the performance of different store locations. Assess metrics such as total quantity sold. Identify high-performing and underperforming stores.
5.	Product Unit Price Analysis:
•	Investigate the relationship between product unit prices and sales. Determine if higher or lower prices impact transaction volume. Consider if rice adjustment can make a difference.

