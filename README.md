# Restaurant Operations Analysis (SQL)
## Project Overview 
The Taste of the World Café recently debuted a new menu featuring diverse international offerings and generous portions. As a Data Analyst, the goal of this project is to evaluate the initial performance of this new menu by digging into customer order data. By extracting insights from menu and transaction records, this analysis identifies high-performing dishes, pinpointing underperforming items, and uncovering the spending habits of the café’s top customers. These findings serve to provide actionable recommendations for menu optimization and improved operational efficiency.

## Data set
-<a href<="https://mavenanalytics.io/data-playground/restaurant-orders">Data set</a>


## Objectives
1. Menu Inventory Exploration
- The first phase focuses on understanding the breadth and pricing structure of the café's offerings.
- Determine the total number of items available on the new menu.
- Identify the price extremes (least and most expensive items).
- Analyze specific cuisine types, such as Italian dishes, to understand their prevalence and pricing.
- Evaluate the distribution of dishes across categories and calculate the average price point for each.

2. Order Pattern Analysis
- The second phase examines the volume and scale of customer transactions over time.
- Establish the timeframe of the dataset to understand the period of analysis.
- Quantify total order volume and the total number of individual items sold.
- Identify "bulk" behavior by finding orders with the highest item counts.
- Calculate the frequency of large-scale orders (e.g., orders containing more than 12 items).

3. Customer Behavior & Financial Insights
- The final phase merges menu data with order details to uncover financial performance and customer preferences.
- Identify the most and least popular menu items and their respective categories.
- Rank the top 5 highest-spending orders to understand premium customer behavior.
- Perform a deep dive into the highest-spend transactions to uncover patterns (e.g., specific item combinations or category preferences).
- Synthesize findings to provide data-driven insights on how customers are reacting to the new menu.

## Key Steps
- Data Preparation & Cleaning: Importing datasets, handling null values, and standardizing date/time formats.
- Exploratory Data Analysis (EDA): Aggregating price and quantity metrics to understand menu composition and order volume.
- Table Joins & Integration: Merging the menu and order tables to link dish details with customer transactions.
- Behavioral & Financial Modeling: Ranking items by popularity and calculating total revenue per order to identify high-value patterns.

## Key Insights
- Menu Size: 32 unique items across 4 categories.
- Price Range: Items range from $5.00 up to $19.95.
- Top Category: Italian is the most frequent category with 9 dishes.
- Order Volume: Total of 5,370 unique orders analyzed.
- High-Value Orders: Identified 23 orders containing more than 12 items.
- Top Spend: The single highest order (ID 440) totaled $192.15.

## Recommendations and conclusion
Recommendations
- Focus marketing on high-margin Italian dishes.
- Optimize staffing for peak periods where large-item orders are most frequent.
  
Conclusion
The analysis of the Taste of the World Café’s new menu highlights a healthy distribution of offerings, with a strong focus on Italian cuisine which currently anchors the menu. The data reveals a significant volume of transactions and a clear presence of high-value, large-scale orders that drive substantial revenue. By leveraging these insights, the café can refine its operational strategy—specifically by prioritizing top-performing categories and adjusting resources to accommodate peak order sizes—to ensure the long-term profitability and success of the new menu launch.

