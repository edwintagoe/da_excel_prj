# Sales Analytics Dashboard

![Coffee Sales Dashboard](/images/fnp.PNG)

## Problem Statement: 
The e-commerce business faced challenges in:
- Tracking sales performance across various Indian festivals and occasions
- Understanding customer buying patterns during different times of the day
- Monitoring delivery performance across multiple cities
- Identifying top-performing products and categories
- Making data-driven decisions due to lack of real-time insights

##  Project Goal: 
To develop an interactive dashboard that provides real-time visibility into sales performance, customer behavior, and operational metrics, enabling stakeholders to make data-driven decisions for business growth and operational efficiency.

## Deliverable: 
Create a dashboard and answer the following key business questions to help the company
improve its sales strategy and optimize customer satisfaction:
- **Total Revenue:** Identify the overall revenue.
- **Average Order and Delivery Time:** Evaluate the time taken for orders to be delivered.
- **Monthly Sales Performance:** Examine how sales fluctuate across the months of 2023.
- **Top Products by Revenue:** Determine which products are the top revenue generators.
- **Customer Spending Analysis:** Understand how much customers are spending on average.
- **Sales Performance by Top 5 Product:** Track the sales performance of top 5 products.
- **Top 10 Cities by Number of Orders:** Find out which cities are placing the highest number of orders.
- **Order Quantity vs. Delivery Time:** Analyze if higher order quantities impact delivery times.
- **Revenue Comparison Between Occasions:** Compare revenue generated across different occasions.
- **Product Popularity by Occasion:** Identify which products are most popular during specific occasions



## Technical Implementation
### Data Architecture
- Data Source: [datasets](datasets)
- Data Model: Star Schema with following entities:
  - Orders
  - Products
  - Locations
  - Occasions

### Key Features Implemented
- **Real-time KPI Monitoring**
  - Total Orders
  - Total Revenue
  - Average Customer Spending
  - Order to Delivery Time

- **Multi-dimensional Analysis**
  - Revenue by Occasions (Festival-wise analysis)
  - Revenue by Product Categories
  - Hourly Sales Distribution
  - Geographic Order Distribution
  - Top Products Performance

- **Interactive Filters**
  - Date Range Selection
  - Occasion-based Filtering
  - Delivery Date Analysis


## Key Insights Generated
- Identified peak sales during Anniversary and Holi festivals
- Discovered Sweets as the highest revenue-generating category
- Mapped order concentration in major metropolitan areas
- Tracked hourly order patterns for operational optimization

## Business Impact
- Improved decision-making with real-time sales insights
- Enhanced inventory management based on occasion-wise demand
- Optimized delivery times across different cities
- Better understanding of customer spending patterns