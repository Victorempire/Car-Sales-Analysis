# Car Sales Analysis
## Project Overview
The global automotive industry is a dynamic sector shaped by economic fluctuations, technology advancements, and evolving consumer preferences. Understanding sales trends is critical for stakeholders to optimize strategies, forecast demand, and maintain competitiveness. This project analyzes 23,906 car sales transactions recorded between January 2022 and December 2023 to uncover actionable insights into seasonal patterns, manufacturer performance, and income-driven purchasing behavior. [Dynamic Dashboard Display here](//www.linkedin.com/posts/victor-onyedikachi-9b7672262_analyzing-a-car-sales-report-using-microsoft-activity-7293428466786463744-nEhy?utm_source=share&utm_medium=member_android&rcm=ACoAAECGshsB0EB1GojtKT3bLcTgrn34EI4lKjY)
## Problem Statement
This Project aims to analyze car sales trends using time series analysis, identifying key sales patterns across different time periods, market segments and forecasting and Correlation Analysis. The specific challenges addressed in this analysis include:
- Sales Trends and Seasonality :
Identifying sales variations by month, quarter, and year to understand peak and low-demand periods.
Analyzing sales differences between weekends and weekdays to optimize marketing and operational strategies.
Determining average sales performance over time.
- Market Analysis :
Identifying the top 10 best-selling car models and manufacturers.
Highlighting the bottom 10 manufacturers in terms of sales to understand industry challenges.
Evaluating customer income distribution and its impact on car purchases over different years.
- Forecasting and Correlation Analysis :
Predicting car sales for the next three years to assist manufacturers and dealerships in planning inventory and production.
Analyzing the correlation between car sales and customer annual income to assess purchasing power and demand trends.
By addressing these challenges, this analysis provides valuable insights for automotive industry stakeholders, helping them refine their sales strategies, optimize inventory management, and anticipate future market trends.
## Dataset Overview:
The analysis leverages the Car Sales Analysis dataset from Kaggle,which include
1. Car Id: Unique identifier for each transaction.
2. Date: Sale transaction date.
3. Customer Name: Name of the customer purchasing the car.
4. Gender: Buyer’s gender (Male, Female).
5. Annual Income: Customer Annual Income 
6. Dealer Name: Name of the car dealership.
7. Company: Car manufacturer (e.g., Chevrolet, Dodge).
8. Model: Specific car model (e.g., Diamante, Prizm).
9. Engine: Engine type (e.g., Double Overhead Camshaft, Overhead Camshaft).
10. Transmission: Transmission type (Auto, Manual).
11. Color: Color of the car exterior.
12. Price: Listed price of the car for sales
13. Dealer No: Dealer identification Number associated with the sales
14. Dealer Region: Geographical Region of the Car Dealer.

## Methodology
### Tools  
I primarily utilized Microsoft Excel for Data Analysis, Visualization, and Forecasting Using forecast sheet on Excel 
### Data Collection  
The dataset used is sourced from Kaggle, [download here](https://www.kaggle.com/datasets/missionjee/car-sales-report)
### Data Preprocessing 
Before conducting analysis, the dataset undergoes the following preprocessing steps:  
### Data Cleaning
The following columns were Changed to the appropriate Data-type:
1. Car ID: Text
2. Customer Name: Text
3.  Gender: Text
4. Annual Income: Whole Number
5. Sales price: Whole Number
6. Changed the following columns name to a more precise name: company to Manufacturer
7. Annual income to Customer Annual income.
## Data Analysis
## Time Series Analysis Dashboard

![Time](https://github.com/user-attachments/assets/7c03dea5-06c4-4988-8003-7f06f21348a8)

## Market Analysis Dashboard

![mrk](https://github.com/user-attachments/assets/1f77d26f-a3a9-4af7-a376-e4220dbbd4d7)

## Forecast Analysis Dashboard

![Forecast](https://github.com/user-attachments/assets/a1fef455-dbaf-429d-b6dd-d7ca67d7a9ea)

## FINDINGS AND ANALYSIS
## The Time series Analysis Dashboard
-	The Line Chart indicate that in 2022, September, November and December collectively contributed 44.15% of Total Sales, and in 2023, the same months Collectively Generated 42.37 % of Total Sales. This implies that the months represent the peak period. The line chart also shows that in 2022, January, February and march had the lowest demand, Contributing 12.40% of Total Sales. Similarly in 2023 January, February and march recorded the lowest demand, Contributing 12.61% of Total Sales.
-	Weekday makes up 80.16% of Total Sales, which implies that Customers prefer purchasing during business days.
-	The fourth Quarter Generated the highest Sales, accounting for 38.08% in 2022 and 36.08% in 2023, However despite this overall performance, sales in October were relatively low.
-	There was a significant 10.54% increase in Total sales in 2023 exceeding the threshold for above -average sales compared to the preceding year, 2022, indicating a Positive growth.

## Market Analysis Dashboard 
-	The Top 10 Manufacturers Generated a significant 42.99% of Total Sales, indicating that Customers Prefer Car from these manufacturers.
-	 Bottom 10 Manufacturers collectively generated 14.62% of Total Profit indicating that these manufacturers are less preferred by customers.
-	The Top 10 car model collectively contributed only 16.16% of Total Sales. While other model accounted for 83.84%. This suggest that, despite being classified as the Top 10 their overall sales Performance is relatively low.
## Forecasting and Correlation Analysis
-	The forecast indicate a strong initial growth as sales increased from $300.34M (2022) to $371.19M (2023), reflecting a 23.59% growth rate, But there was a significant growth rate decline over time (19.09% in 2024,16.03% in 2025, and 13.81% in 2026) indicating market stabilization.
- The positive correlation indicate a relationship between car sales and customer annual income across region. Which means income is a major sales driver. 
      
# RECOMMENDATIONS
## Sales Strategy Optimization
- Since September, November, and December account for a significant portion of sales, manufacturers and dealerships should increase marketing efforts, promotional discounts, and inventory during these months.
-	 Implement targeted promotions or financing incentives in January, February, and March to stimulate demand during slow months.
-	Since 80.16% of sales occur on weekdays, dealerships should ensure extended business hours, special weekday promotions, and streamlined purchasing processes.
## Market Positioning
-	Since the top 10 manufacturers generate nearly 43% of sales, dealerships should prioritize stocking vehicles from these brands to align with customer demand.
-	Identify the challenges affecting sales of the bottom 10 manufacturers (e.g., pricing, features, reliability) and strategize on repositioning these brands through better marketing or competitive pricing.
-	Increase Awareness for Top-Selling Models, Despite being top sellers, these models only account for 16.16% of total sales. Expanding marketing campaigns, increasing dealership incentives, and refining product messaging could help boost their market share.

## Forecasting and Inventory Planning
-	With sales projected to continue growing but at a decreasing rate (23.59% in 2023 down to 13.81% in 2026), manufacturers should adjust production levels accordingly to avoid overstocking or supply shortages.
-	 Dealerships should stock more vehicles that align with projected sales trends and adjust procurement based on forecasted demand.
-	Given the positive correlation between customer income and sales, dealerships and manufacturers should introduce flexible financing options or tiered pricing strategies to cater to different income segments.
-	Since income levels drive car sales, dealerships should focus on regions with higher-income customers by tailoring advertisements and product availability to match purchasing power.


