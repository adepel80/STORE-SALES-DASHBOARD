

CONTEXT

To help the company A, a  fictional company headquarter in United state of America track it's sales and monitor key performance indicator over time, a concise dashboard displaying the relevant metrics was created for use by its stakeholders
This analysis detailed the effectiveness of the dashboard in helping company A achieve its goaL

OVERVIEW

This repository contains the necessary resources and documentation for conducting a comprehensive sales analysis. The goal of this analysis is to gain insights into sales performance, identify trends, and make informed business decisions based on the data

DATA

The dataset used for this analysis is located in the data directory. it was gotten from kaggle  It includes sales data spanning a specific time period, containing information such as Average profit, city, cost price, customer Id, name, discount, zip code, postal code, quantity, proft , region, revenue, RevenueX, sales, sales quantity, sales rep, sales team, segment, ship date, ship mode, state, sub category

TOOLS USED AND DATA SOURCE:

Tool: Power BI, microsoft excel

Data source : kaggle

ANALYSIS

The sales analysis process involves the following steps:

DATA CLEANING AND PREPROCESSING: 

The raw data is cleaned and formatted to ensure accurate analysis.


![power query sales](https://github.com/adepel80/STORE-SALES-DASHBOARD/assets/123180341/b3d376f8-6a12-47d3-87df-5159e4bc368f)


EXPLORATORY DATA ANALYSIS (EDA):

Basic statistics and visualizations are generated to understand the distribution of sales, trends over time,Revenue, profit, coost price,sales quantity and other relevant insights.

KPI

To help the stakeholders better understand the revenue performance, 4 key performance indicators were highlighted

•	NET PROFIT BY SEGMENT

of all segment, the consumer is having the most profit with 134,119 and Home office is having the least of the 3 segments with 60,298.

![net profit by segment sales](https://github.com/adepel80/STORE-SALES-DASHBOARD/assets/123180341/f8eb8d78-b541-4b7a-bf11-b641388b6209)

•	Sales by category with technology dominating with 36.4% and the least with 31.3% for office supply 

![sales by cat sales](https://github.com/adepel80/STORE-SALES-DASHBOARD/assets/123180341/be52e054-a141-4b6e-91df-47bb28787559)

•	Total sales of 2.3million


SALES METRIC CALCULATION: 
Key performance metrics, such as total revenue, REVENUE X, cost price, average order value, and top-selling products, are calculated.

TIME SERIES ANALYSIS: 
Time-based patterns are time intelligence was calculated, extracting the necdssary information from the order date and sales information

MODEL 

![model](https://github.com/adepel80/STORE-SALES-DASHBOARD/assets/123180341/82c0e1da-0870-4c78-9e50-d1b79ed5a7cf)


FINDINGS
Based on the analysis, several findings have been observed:

INSIGHT

1) office supply dominate the product category with 60.3% while technology has the least with just 18.45% with total sum of sales accumulated to 2,3million with just 14 quantities and just 286400 profit

2)Most sales of the product sub cat was made from Copiers with 55,617 while table is having a loss of -17,725. Technology dominated the product category with 36.45 which is just 4.1% sales above furniture while office supply is having the least with just 31.3%. The west have an average profit of 33.85  which is the highest while the central region has the least with 17.09.

3) of all segment consumer is having the most profit with 134,119 and Home office is having the least of the 3 segments with 60,298.

Seasonal spikes in sales occur during specific months, indicating potential market opportunities.
Certain products consistently outperform others in terms of sales volume and revenue.
Average order value is highest during promotional periods.

FINAL DASHBOARD

The dashboard below display the key performance indicator that meet the needs of the stakeholders and provides them with an overview of the business performance. the presence of filter for the following [Customer name, Cities, Product name, State, Sales REP] on the dashboard makes it more interactive

![Real sales dash](https://github.com/adepel80/STORE-SALES-DASHBOARD/assets/123180341/163b251f-3d0f-4fb9-9861-99f15a6de53e)


RECOMENDATION
Considering the findings, the following recommendations are made:

Allocate marketing resources to capitalize on seasonal peaks.
Further promote the top-selling products to maximize revenue.
Plan targeted promotions during periods of high average order values.
Usage
To replicate or build upon this analysis:
Navigate to the data directory and replace the sample data with your own dataset.
Use Excel, Power BI or your preferred analysis tool to run the provided analysis scripts.

Contributing
Contributions to this analysis are welcome! If you have suggestions, improvements, or bug fixes, feel free to submit a pull request.


