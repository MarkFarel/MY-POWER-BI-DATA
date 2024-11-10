# Car-sales-Dashboard
---

### Overview
The Car Sales Dashboard is a dynamic and interactive Power BI solution designed for our car dealership to visualize critical KPIs, track sales trends, 
and analyze car sales performance. This dashboard provides real-time insights into key metrics, enabling the team to make informed, data-driven decisions,
monitor sales progress, and uncover growth opportunities.

### Objective

The objective of the Car Sales Dashboard project is to deliver a comprehensive, user-friendly dashboard in Power BI that displays critical KPIs such as Year-to-Date (YTD) and Month-to-Date (MTD) sales, year-over-year (YOY) growth, and average price analysis. The dashboard also provides a deep dive into sales distribution by car body style, color, and dealer region, enhancing the ability to analyze sales metrics from multiple angles.

### Data Model
The data model for the Car Sales Dashboard integrates several tables to enable versatile data analysis. Key tables and fields include:

1. **Sales Table**

- Sale_ID: Unique identifier for each sale.
- Car_Model: Model of the car sold.
- Body_Style: The body style (e.g., sedan, SUV) of the car.
- Color: Color of the car sold.
- Sale_Date: Date when the sale was completed.
- Sale_Amount: Total amount for each sale.
- Dealer_Region: Region where the sale occurred.
- Company: Company associated with the sale.
- Quantity: Number of units sold in each sale.

2. **Date Table (Calendar Table)**

- ```Date```: Contains all possible sale dates, enabling time-based analysis.
-```Year```, ```Month```, ```Week```: Fields to support YTD, MTD, and YOY analysis.
3. **Dealer Table**

- ```Dealer_ID```: Unique identifier for each dealer.
- ```Region```: Region where each dealer operates.
- ```Company```: The associated company for each dealer location.
These tables support KPIs, sales trend analysis, and detailed filtering across time periods, body styles, colors, and regions.

### Dashboard Features

**Key Performance Indicators (KPIs)**
The dashboard offers a range of KPIs to track car sales performance:

1. **Sales Overview**

- **Year-to-Date (YTD) Total Sales**: Shows the cumulative sales amount from the beginning of the year to date.
- **Month-to-Date (MTD) Total Sales**: Displays total sales within the current month.
- **Year-over-Year (YOY) Growth in Total Sales**: Calculates the percentage change in total sales compared to the same period last year.
- **Difference between YTD Sales and Previous Year-to-Date (PTYD) Sales**: Highlights the growth or decline in sales when compared to the same YTD period in the previous year.

2. **Average Price Analysis**
- **YTD Average Price**: Shows the average price of cars sold year-to-date.
- **MTD Average Price**: Displays the average sales price within the current month.
- **YOY Growth in Average Price**: Calculates the YOY change in the average price of cars sold.
- **Difference between YTD Average Price and PTYD Average Price**: Tracks the variance in average sales price compared to the previous YTD period.

3. **Cars Sold Metrics**

- **YTD Cars Sold**: Displays the total units sold year-to-date.
- **MTD Cars Sold**: Shows the total cars sold in the current month.
- **YOY Growth in Cars Sold**: Measures the percentage increase or decrease in units sold compared to last year.
- **Difference between YTD Cars Sold and PTYD Cars Sold**: Shows the change in total units sold compared to the previous YTD period.

### Business Questions Answered
The Car Sales Dashboard addresses essential business questions:

- What is the **current YTD and MTD sales performance** compared to last year?
- How are the **average prices** of cars trending over time?
  Which **car models**, **body styles**, and **colors** drive the most revenue?
- How do **dealer regions** compare in terms of total sales and units sold?
Which company is contributing the most to sales performance, and what are the growth trends?
What insights can be drawn from weekly sales trends?

### Key Insights and Findings
#### Sales Performance Highlights**

#### Average Price Analysis

#### Regional Performance

### Conclusion
The **Car Sales Dashboard** is an essential tool for understanding car sales performance across different dimensions. It provides critical insights into sales metrics, average price trends, and regional performance. By leveraging this dashboard, stakeholders can make data-driven decisions, spot trends, and optimize sales strategies.