# Blinkit sales analysis (Power BI)

## Project Object
The primary objective if this project was to analyze the sales performance of Blinkit (an instant delivery service) using a comprehensive dashboard. The aim was to uncover the key business insights by examining sales distribution, outlet performance, customer rating and item trends across different outlet types, location and size.

## Dataset used
- <a href="https://github.com/animeshdwived/Blinkit-sales/blob/main/BlinkIT%20Grocery%20Data.xlsx">Dataset</a>

## Questions(KPIs)
- What is the total sales generated?
- How many items were sold in total?
- What is the average sales per item?
- What is the average Customer rating?
- Which outlet type, size and location performs the best?
- Which item categories contribute the most to sales?
- How has sales performance evolved over the years?
- What is the impact of fat content (Low fat vs Regular) on sales?

## Dashboard Interaction
- <a href="https://github.com/animeshdwived/Blinkit-sales/blob/main/blinkit%20sales.png">Dashboard view</a>

## Process
### Data Collection and Cleaning
- Data was collected from Blinkit's internal sales record (Sample or dummy dataset)
- Remove nulls and duplicates, format columns (like- date, currency), create custom columns like "Fat Content", "Outlet Tier", etc using Power Query in Power BI.

### Data Modeling
- Established relationships between tables: Sales, Outlet, Items.
- Used star schema designs for better performance.
- Created Meas using DAX for KPIs (eg. Total Sales, Avg Sales, Avg Rating).

### Data Visualation
- Built interactive visuals in Power BI including:
  - Card KPIs for high level metrics.
  - Bar and Column charts for item and outlet-wise analysis.
  - Pie/Donut charts for outlet size and fat content analysis.
  - Line chart to analyze year-wise sales trends.
  - Slicers for filtering by outlet type, location, size, and item type.

  ## Dashboard
  ![blinkit sales](https://github.com/user-attachments/assets/7afe94e2-9969-4427-a79e-17268fa8fa83)

## Project Insights
- Total Sales: $1.20M generated overall.
- Top Performing Outlet type: "Supermarket type1" with $787.55K in Sales.
- Top  Tier by Sales: Tier 3 outlets contributed the most ($472.13K)
- Top Selling Categories:
    - Fruits and Vegetables: $0.18M
    - Snakes Food: $0.18M
    - Household items: $0.14M
- Customer Satisfaction: Average rating is 3.9 across all outlets.
- Fat Content Impact:
    - Regular items outperform Low Fat items in sales ($776.32K vs $425.36K).
- Year-Wise Sales:
    - Peak Sales Observed in 2018 ($205K).
    - Consistent performance maintained post-2016.

# Final Conclusion
This Power BI dashboard offers a complete view of Blinkit's sales landscape.The analysis highlights which items and outlets drive the most revenue and how various factors (like outlet type, fat content and tier classification) impact overall performance.These insights are crucial for Blinkit's business strategy to:
- Optimize inventory.
- Expand high-performing outlet types.
- Personalize offering based on location and consumer perferences.
