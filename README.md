
**Restaurant Operations Analysis (SQL)**
Overview
An end-to-end SQL analysis using Snowflake to evaluate a restaurant's menu performance and customer ordering habits following a menu relaunch.

Tech Stack
- SQL (Snowflake)
- Joins, Aggregations, Subqueries, Data Casting (TRY_TO_NUMBER)

 Data Sources
- menu_items: Dish names, categories, and prices.
- order_details: Transactional logs and timestamps.

 Key Insights
- Menu Engineering: Identified Italian as the high-volume category and pinpointed price outliers across the menu.
- Operational Trends: Analyzed order date ranges and identified "heavy" orders (12+ items) to highlight kitchen pressure points.
- Spend Analysis: Joined tables to rank the Top 5 highest-spending orders and analyzed their category composition.

📈 Recommendations
- Focus marketing on high-margin Italian dishes.
- Optimize staffing for peak periods where large-item orders are most frequent.
