# Atliq-Hardware-Sales-Analysis

![](atliq_hardware_image.jpg)



## Introduction

The Sales Director at Atliq Hardware in New Delhi struggles with interpreting sales data from regional managers sent via Excel sheets. The task is to streamline this process by creating a dashboard that consolidates the data and highlights actionable insights for business improvement.





## Problem statement
1. What is the revenue by zone, market, year, month, and product?
2. How does the profit & qty. sold vary by zone, market, year, month, and product? 
3. What are key insights about the sales at Atliq Hardwares?



## Skills/ concepts demonstrated:
- SQL Scripting
- Power BI's Parameters
- Data Visualizations
- MOdelling



## Modelling
![database_original_model](https://github.com/user-attachments/assets/cbb4f459-fbfc-4f94-a98b-2ea5c209872d)


The main part of the data model is a star schema, consisting of 1 fact table and 4 dimension tables. 


## Visualization:

The report comprises of 6 pages:
1. Summary:
![dashboard_1](https://github.com/user-attachments/assets/e10c0112-4d95-4a10-96c9-7475030d1cb3)

2. Profit Margin:
![dashboard_2](https://github.com/user-attachments/assets/7b9c84e2-7ab1-40e2-b067-518fa8eed94b)

3. Revenue:
![dashboard_3](https://github.com/user-attachments/assets/ee9f455b-3eb4-40cc-9b97-fd3239f488cd)

4. Profit:
![dashboard_4](https://github.com/user-attachments/assets/989e7b43-48c1-4e3a-bf56-7ccce74a9f4b)


5. Qty. Sold:
![dashboard_5](https://github.com/user-attachments/assets/db833f33-941c-4d2e-b6b8-cfa6d11b351d)


6.  Customers:
![dashboard_6](https://github.com/user-attachments/assets/5935bcea-2899-4470-8ee6-b3667cbaa1bb)



## Summary of Analysis
- Profit margin

Over the 3-year period (2018-2020), profit margins fluctuated—ranging from a high of 4.93% in January 2019 to a low of 0.49% in April 2020—, but they stayed below 5%.

Across the 3 regions, Atliq Hardware’s margins showed only slight regional variation: Central at 3.25%, North at 2.23%, and South at 2.21%.

Among the 14 cities where Atliq Hardware operates, 64% achieved profit margins between 2% and 5%, while Bengaluru and Kapur reported negative margins.


- Revenue

Over the 3-year period, while revenue (totaling ₹984.87 million) showed minor fluctuations—with an overall declining trend, peaking at ₹42.5 million in January 2018 and dipping to ₹14.7 million in 2020—the North region generated the most (₹675.59 million), followed by the Central region (₹263.72 million) and the South (₹45.56 million).
 
 
The highest revenue of ₹468.96 million came from unspecified products, and only 12 out of 200 products contributed ₹10 million or more. Delhi NCR was the top-performing market, generating ₹519.57 million, while Bengaluru contributed the least at ₹0.37 million.


- Profit

Over the 3-year period, Atliq Hardware's profits (totaling ₹24.47 million) showed a declining trend despite occasional peaks, with only 6 out of 30 months recording profits between ₹1 million and ₹2 million.
 
Most of the profit came from the North region (₹15.1 million), followed by the Central region (₹8.6 million), while the South contributed the least (₹1 million).
 
The top five profit contributors were Delhi (₹12 million), Mumbai (₹4.9 million), Ahmedabad (₹2.8 million), Bhopal (₹2.3 million), and Nagpur (₹1.4 million). In contrast, Kanpur and Bengaluru incurred losses of around ₹100,000 each.


- Qty. Sold

Over the 3-year period, Atliq Hardware's sales (totaling 2.43 million units) showed an overall decline—peaking at 93,000 units in May 2018 and dropping to 34,000 units by June 2020. Among the three regions, the North led with 1.27 million units, followed by the Central region with 0.76 million, and the South with 0.4 million. 
 
About 420,000 units came from unspecified products, while three specific products contributed between 100,000 and 300,000 units each. Delhi was the top contributor with 0.99 million units (41% of total sales), while Bengaluru had the lowest with just 413 units. 
 
Six markets contributed between 100,000 and 1 million units, and the rest contributed fewer than 100,000 units each.



## Conclusion and Recommendations:

For a more detailed post on the walkthrough, here is the portfolio post that does that :https://www.datascienceportfol.io/yole_amos/projects/0

Thanks!
