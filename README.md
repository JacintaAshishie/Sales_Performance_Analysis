# Sales_Performance_Analysis

## Table Outline
- [Project Overview](#project-overview)
- [Project Scope](#project-scope)
- [Key Performance Indicators](#key-performanceindicators)
## Project Overview
This project aims at conducting a comprehensive analysis of a retail store sales data from 2023 to 2024 to assess product performance and identify top-selling items, compare monthly sales trends across regions, and uncover customer preferences and regional patterns. This analysis provides actionable insights to inform data-driving decisions, optimize product offerings, and enhance customer retention strategies. In doing this, we will be focusing on data cleaning, analysis and visualization using Excel, SQL, and Power BI respectively.

## Project Scope:

- Explore sales data for key insights
- Identify top-selling products and regional performance
- Analyze monthly sales trends
- Develop an interactive Power BI dashboard

## Key Performance Indicators (KPIs):

- Total Sales
- Sales Growth Rate
- Top-Selling Products
- Regional Sales Performance
- Monthly Sales Trends



### Data Sources

The primary data used in this analysis is the SalesData.xlsx file, kindly provided by LITA the IncubatorHub and made available for download on CANVAS.
Alternative Data Sources

For those interested in exploring similar datasets, freely available options can be downloaded from open-source online repositories, including:

- Kaggle ((https://www.kaggle.com/code))
- FRED (Federal Reserve Economic Data, (https://fred.stlouisfed.org/))
- Other reputable data repository sites

### Tools Used
- Microsoft Excel for data cleaninng, analysis and visualization
- SQL -Structured Query Language for Quering of Data
- Power BI for data visualization
- GitHub for portfolio management

   ## Methodology:
1. Data Cleaning
2. Data Analysis (SQL queries)
3. Data Visualization (Power BI)
4. Findings and Recommendations.
5. 
## Sata Cleaning and Preparations 
In the initial stage of the data cleaning and preparations, we performed the following actions;
- Data loading and inspection
- Handling missing values
- Removing duplicates
- Data Sorting
- Data normalization
- Data transformation

  ## Exploratory Data Analysis (EDA)

  EDA involved the exploring of the data to answer queestions about the data such as;
  
- What is the Total sales Per product?
- Total Sales by region ?
- Total sales per Month?
- Average sales per product?
- Total revenue by region?
- What is the total sales for each product category?
- What is the number of sales transactions in each region?
- What is the highest-selling product by total sales value?
-The total revenue per product?
- What is the monthly sales totals for the current year?
- Find the top 5 customers by total purchase amount.
- What is the percentage of total sales contributed by each region?
- Identify products with no sales in the last quarter?


## Data Analysis
```
This is where we include some basic lines of code or queries or even some of the Excel functions and we use Pivot tables to generate some sales reports;
- Excel;
   AVERAGEIF(C:C,C:C,H:H)
   =SUMIF(C:C,C:C,H:H)---SUMIF(range, criteria, [sum_range])
  
  ```SQL
  SELECT
   Region,
   COUNT(CustomerID) AS TotalCustomers
   FROM Capstone_SalesData
   GROUP BY Region
```

## Outcomes:

- Actionable recommendations for business growth
- Improved sales forecasting
- Enhanced product portfolio management
- Data-driven decision-making


### Data Vsualization

((https://github.com/JacintaAshishie/LITA_Capstone_SalesData_Project/blob/main/CAPSTONE%20SALESDATA%20VISUALS.png))
  





