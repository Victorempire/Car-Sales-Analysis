# Car Sales Analysis
## Project Overview
The global automotive industry is a dynamic sector shaped by economic fluctuations, technology advancements, and evolving consumer preferences. Understanding sales trends is critical for stakeholders to optimize strategies, forecast demand, and maintain competitiveness. This project analyzes 23,906 car sales transactions recorded between January 2022 and December 2023 to uncover actionable insights into seasonal patterns, manufacturer performance, and income-driven purchasing behavior. 
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
The dataset used is sourced from Kaggle, [download here]()
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
