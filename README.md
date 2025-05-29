## Blinkit sales analysis (Power BI)

# Project Object
The primary objective if this project was to analyze the sales performance of Blinkit (an instant delivery service) using a comprehensive dashboard. The aim was to uncover the key business insights by examining sales distribution, outlet performance, customer rating and item trends across different outlet types, location and size.

# Dataset used
- <a href="https://github.com/animeshdwived/Blinkit-sales/blob/main/BlinkIT%20Grocery%20Data.xlsx">Dataset</a>

# Questions(KPIs)
- What is the total sales generated?
- How many items were sold in total?
- What is the average sales per item?
- What is the average Customer rating?
- Which outlet type, size and location performs the best?
- Which item categories contribute the most to sales?
- How has sales performance evolved over the years?
- What is the impact of fat content (Low fat vs Regular) on sales?

# Dashboard Interaction
- <a href="https://github.com/animeshdwived/Blinkit-sales/blob/main/blinkit%20sales.png">Dashboard view</a>

# Process
## Data Collection and Cleaning
- Data was collected from Blinkit's internal sales record (Sample or dummy dataset)
- Remove nulls and duplicates, format columns (like- date, currency), create custom columns like "Fat Content", "Outlet Tier", etc using Power Query in Power BI.

## Data Modeling
- Established relationships between tables: Sales, Outlet, Items.
- Used star schema designs for better performance.
- Created Meas using DAX for KPIs (eg. Total Sales, Avg Sales, Avg Rating).

## Data Visualation
- Built interactive visuals in Power BI including:
  - Card KPIs for high level metrics.
  - Bar and Column charts for item and outlet-wise analysis.
  - Pie/Donut charts for outlet size and fat content analysis.
  - Line chart to analyze year-wise sales trends.
  - Slicers for filtering by outlet type, location, size, and item type.

  # Dashboard
  ![blinkit sales](https://github.com/user-attachments/assets/7afe94e2-9969-4427-a79e-17268fa8fa83)
