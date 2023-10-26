# Pharmaceutical-Sales-and-Marketing-Analysis-and-Report
<img align="left" src=https://github.com/InemesitUmoh/Pharmaceutical-Sales-and-Marketing-Analysis-and-Report/blob/main/photos/Header%20Photo.jpg width="1000px"/>.


## Introduction
Forggith Pharmaceuticals is a pharmaceutical company that produces medical drugs which get to the consumers through their Distributors. To optimize their operations and bolster sales and marketing efforts, Forggith has established a systematic approach to data analysis to achieve their sales and marketing objectives through tracking and monitoring of key performance indicators (KPIs).

## Problem Statement
Forggith Pharmaceuticals is looking forward to some Power BI Reports to assist in guiding their strategies, tactics and operations as a company.
To help them achieve their objective, the followinng questions were answered:
* What are the top contributing classes of products to revenue?
* What classes of products are less prominent in the market?
* Which channel and sub-channels lead sales?
* What is the sales year over year change by channel and sub-channel?
* What is the performance of sales representatives and sales teams in their contribution to revenue?
* What is actual revenue in comparison to the set target?

## Data Sourcing
The data for analysis comes from the template provided by Forggith to their distributors to capture records of their sales which are then sent to Forggith on a monthly basis. The dataset consists of the monthly actual and target sales record from 2022 to 2025. The dataset between 2023 and 2025 are projected actual and target sales.
The data was provided as part of the [Foresight](https://training.foresightbi.com.ng/enrollments) Power BI Developer internship programme. 

## Data Transformation
To enhance data quality, consistency, and suitability for analysis, we performed data transformation using Power Query within Power BI. The transformation process involved the following steps:
* Appended the 2022 sales dataset to that of 2023 to 2025, since they were hosted on different workbooks.
* Promoted headers in the target dataset.
* Promoted headers in the employees table.
* Validated the data types of each column.
* Unpivoted the year columns to have a single year column in the Target dataset.
* Merged the month and year columns in the target data to form a date data type column to ensure easy time intelligence analysis, and period to period analysis.

## Data Modelling
The star schema model was implemented — all the dimension tables are connected to the fact table.
There are 5 dimension tables, 2 fact tables, and a table containing all DAX measures. The dimension tables are all joined to the fact tables in a one to many relationship.
![Data Modelling](https://github.com/InemesitUmoh/Pharmaceutical-Sales-and-Marketing-Analysis-and-Report/blob/main/photos/Data%20Model%20Relationships.PNG)

## Data Visualization
The reports below are the executive and product reports that allow the executive team to track revenue numbers to monitor alignment with the set targets to influence medium to long term strategies.
![Executive Report](https://github.com/InemesitUmoh/Pharmaceutical-Sales-and-Marketing-Analysis-and-Report/blob/main/photos/Executive%20Report.png)
 
![Product Report](https://github.com/InemesitUmoh/Pharmaceutical-Sales-and-Marketing-Analysis-and-Report/blob/main/photos/Product%20Report.png)

The report below is the salesperson report that allows the sales representatives to track their performances through-out the periods to plan their marketing activities, and also the team managers can track their teams’ performances through-out the periods to plan their teams’ activities.
![Salesperson Report](https://github.com/InemesitUmoh/Pharmaceutical-Sales-and-Marketing-Analysis-and-Report/blob/main/photos/Salesperson%20Report.png)

You can access the full interactive Power BI report [here](https://app.powerbi.com/view?r=eyJrIjoiODhhMmE5NWQtMzdmMC00ODY3LTgyM2UtY2Q2YzFiYjZiNGZjIiwidCI6IjE3YzlhZjk3LTQxNDgtNGUxNC1hMDEzLTU4YzAzOTRiZmI4NCJ9&pageName=ReportSection5784ae0dc1b09de5c440)

## Results and Insights
* For the period 2022–2025, a total actual revenue of **$11.12bn** was recorded, which is **31.52%** ahead of the target. Revenue surpassed target throughout the period, but dropped by **-9.26%** in 2025 year on year (YoY). The 2024 revenue is projected to be the company’s highest revenue.
* Products from the product classes of analgesics, antiseptics, and mood stabilizers were the top 3 most selling products.
* Pharmacy accrued more revenue than hospital with an overall contribution of **52.9%**.
* On average, the revenue and volume targets were met in the months of February, March, June, September, and November for the periods 2022–2025.
* Team Delta recorded the highest revenue of over **$3.43bn**, which is **31%** of the total revenue. Team Charlie had the highest target revenue achievement and target volume achievement of **147%** and **159%**, respectively, which includes the forecasted periods.

## Conclusions
The analysis of Forggith Pharmaceuticals sales reveals a lot of insights about sales and marketing performance for 2022 and the projected years. Based on the analysis, it can be concluded that there will be consistent revenue growth apart from 2025, where there is a dip of about **-10%**. This calls for concern to investigate before hand why that might be the case. It can also be said that products in the analgesic, antiseptic, and mood stabilizers looks really promising to bring in massive revenue in sales in both the pharmacy and hospital channels.

## Recommendations
Based on the insights from the analysis of sales and forecasted sales of Forggith Pharmaceuticals, the following recommendations were made:
* Volume of products should be increased in the months of March, June, September, and November to increase revenue.
* There should be a marketing campaign targeting the hospital channel to increase patronage. Collaborate with social media influencers and strategic partners to increase brand visibility and reach a broader audience.
* Further analysis should be conducted to understand what might likely be the cause of the dip in sales in the projected period 2025 year on year (YoY) revenue and take proactive measures to address any issues that might affect customers patronage.
* Introduce loyalty rewards to incentivize increased customer patronage.

You can read the full blog post and my thought process on [Medium](https://medium.com/@inemesitumoh/navigating-pharmaceutical-data-analysis-a-forggith-case-study-3ee00e7be5bc)

### Connect with me:
<a href="https://github.com/InemesitUmoh"><img align="left" src="https://github.com/InemesitUmoh/Pharmaceutical-Sales-and-Marketing-Analysis-and-Report/blob/main/photos/github.png" alt="Inemesit Umoh | Medium" width="21px"/></a>
<a href="https://www.linkedin.com/in/inemesitumoh/"><img align="left" src="https://github.com/InemesitUmoh/Pharmaceutical-Sales-and-Marketing-Analysis-and-Report/blob/main/photos/linkedin.png" alt="Inemesit Umoh | LinkedIn" width="21px"/></a>
<a href="https://twitter.com/InemesitUmoh95"><img align="left" src="https://github.com/InemesitUmoh/Pharmaceutical-Sales-and-Marketing-Analysis-and-Report/blob/main/photos/twitter.png" alt="Inemesit Umoh | Twitter" width="21px"/></a>
<a href="https://medium.com/@inemesitumoh"><img align="left" src="https://github.com/InemesitUmoh/Pharmaceutical-Sales-and-Marketing-Analysis-and-Report/blob/main/photos/medium.png" alt="Inemesit Umoh | Medium" width="21px"/></a>
