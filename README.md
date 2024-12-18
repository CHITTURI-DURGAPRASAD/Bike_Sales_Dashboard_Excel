# Bike Sales Dashboard

This repository contains an interactive Excel dashboard designed to analyze and visualize bike sales data. The dashboard provides insights into customer demographics, purchase behavior, and other key metrics.

Overview :-

The Excel dashboard was created as part of an Excel portfolio project. It demonstrates data analysis, transformation, and visualization techniques. The project uses a dataset containing information about bike buyers, including demographics, financial status, and purchasing habits.

Features :-

1. **Interactive Dashboard**:
   - Provides slicers and filters for dynamic analysis.
   - Displays key insights using charts, pivot tables, and conditional formatting.
2. **Data Transformation**:
   - Age categorized into groups.
   - Aggregated data using PivotTables for metrics like income averages and purchase percentages.
3. **Data Visualization**:
   - Bar charts, pie charts, and tables.
   - Interactive slicers for easy exploration.

Data Sources :-

Dataset Used : [bike_sales_data](https://docs.google.com/spreadsheets/d/1KVe5ajGaZFpWP9UJpOhxeJh4nY3sanmy/edit?usp=sharing&ouid=100014812716638492492&rtpof=true&sd=true)
The project uses the following data:
1. **bike_buyers**: The raw dataset with columns such as `Age`, `Income`, `Marital Status`, and `Purchased Bike`.
2. **Working sheet**: Intermediate sheet for data transformation (e.g., calculating age groups).
3. **Pivot_Table**: Summary tables used in the dashboard for aggregated insights.
4. **Dashboard**: Main visual output with charts and slicers.

Steps to Create the Dashboard :-

1. Data Import and Cleaning
- Imported raw data into the `bike_buyers` sheet.
- Ensured no missing values or inconsistent data types.
- Added calculated fields like `Age Group` for segmentation.

2. Data Transformation
- Used Excel formulas and functions to derive new metrics, such as:
  - **Age Group**: Categorized customers into groups (e.g., Young Adult, Middle-Age, Senior, etc.).
- Filtered and sorted data for relevant insights.

3. Pivot Tables
- Created PivotTables in the `Pivot_Table` sheet for aggregated insights:
  - Income by gender and bike purchase status.
  - Total purchases by age group.

4. Dashboard Design
- Linked PivotTables and charts in the `Dashboard` sheet.
- Used slicers for interactivity to filter by:
  - Age Group
  - Gender
  - Bike Purchase Status
- Visualized key metrics:
  - Bar charts for income and purchase trends.
  - Pie charts for demographic distribution.

How to Use :-

1. **Download the File**:
   - Clone the repository or download the `Bike_Sales_Dashboard.xlsx` file.
2. **Open in Excel**:
   - Use Microsoft Excel (2016 or later) for full functionality.
3. **Explore the Dashboard**:
   - Navigate to the `Dashboard` sheet.
   - Use slicers to filter data dynamically.
   - View insights in the charts and tables.

Publishing Notes :-

To publish or share this dashboard:
1. Export to PDF for a static view.
2. Upload to a cloud service like OneDrive for interactive sharing.
3. Publish to Power BI for enhanced interactivity.

Files in This Repository :-

- **Bike_Sales_Dashboard.xlsx**: The main Excel file with the dashboard, PivotTables, and raw data.
- **README.md**: This file.

Key Excel Features Used :-

1. **Formulas**:
   - `IF`, `AND`, and conditional logic for data transformation.
2. **PivotTables**:
   - For data aggregation and insights.
3. **Charts**:
   - Bar and pie charts for visualization.
4. **Slicers**:
   - For interactive filtering.
5. **Conditional Formatting**:
   - Highlighted key metrics.

Future Improvements :-

- Integrate additional metrics like customer lifetime value.
- Automate dashboard updates using macros or Power Query.
- Publish on Power BI for advanced interactivity.
