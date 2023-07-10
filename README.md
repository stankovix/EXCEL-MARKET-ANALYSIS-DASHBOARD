
# **EXCEL MARKET ANALYSIS DASHBOARD**

![Logo](https://github.com/stankovix/EXCEL-MARKET-ANALYSIS-DASHBOARD/blob/main/US-Sales-Dashboard.png?raw=true)

Title: Market Analysis Project using Excel, Power Query, and Power Pivot.

Introduction:

The market analysis project aims to provide valuable insights into the company's performance, revenue trends, market share, and sales distribution. By leveraging the power of Excel, along with the capabilities of Power Query and Power Pivot, this project allows for efficient data import, cleaning, modeling, and visualization. The project involves analyzing a dataset containing information about manufacturers, sales figures, countries, and time periods. The goal is to answer key questions and present the findings through an interactive and visually appealing dashboard.

Key Objectives:

1. Determine the market share of our company (VanArsdel).

2. Identify revenue trends across all manufacturers.

3. Analyze sales distribution in the USA.

4. Explore revenue trends and year-on-year growth.




## Authors

- [@octokatherine](https://github.com/stankovix)

Thanks To:
- [@octokatherine](https://www.linkedin.com/in/obinnaiheanachor/) for the YouTube Tutorial that helped me to carry out this project.


## Installation

Kindly take note:

```bash
Make sure you are using excel 365 for easy access to all features to be able to complete the tax with ease.
```
    

## **STEPS TAKEN IN THIS PROJECT:**

To solve the market analysis project using Excel, Power Query, and Power Pivot, the steps below were taken:

Step 1: Import and Clean the Data using Power Query
- Opened Excel and navigated to the "Data" tab.
- Clicked on "Get Data" or "From Other Sources" and chose the appropriate data source (e.g., CSV, Excel file, etc.).
- Used the Power Query Editor to clean and transform the data as needed. This involved removing unnecessary columns, merging and splitting of columns, filtering rows, handling missing values, etc.
- Applied data cleaning techniques like removing duplicates, formatting data types, and creating calculated columns.

Step 2: Create a Data Model using Power Pivot
- After cleaning the data, I return to Excel and Clicked on the "Power Pivot" tab.
- Click on "Manage" to open the Power Pivot window.
- In the Power Pivot window, click on "Add to Data Model" to add the cleaned data to the data model.
- Define relationships between tables (e.g., connecting a sales table with a manufacturer table using a common key).
- Created calculated measures and columns required for the analysis (e.g., market share, revenue trend, year-on-year growth, Date).

Step 3: Answered the Questions and Created a Dashboard
1. Market Share of our Company (VanArsdel):
- Created a PivotTable and PivotChart based on the data model.
- Draged the appropriate fields (e.g., manufacturer, sales) to the respective areas (e.g., rows, values).
- Filter the manufacturer field to select only the company (VanArsdel).
- Calculated the market share by dividing the company's sales by the total sales and formated it as a percentage.

2. Revenue Trend across all Manufacturers:
- Created a PivotTable and PivotChart and based on the data model.
- Draged the appropriate fields (e.g., manufacturer, revenue, time) to the respective areas (e.g., x-axis, y-axis).
- Formated the chart as needed to visualize the revenue trend over time.

3. Sales Distribution in USA:
- Create a PivotTable and Map based on the data model.
- Draged the appropriate fields (e.g., country, sales) to the respective areas (e.g., rows, values).
- Filtered the country field to select only the USA.

4. Revenue Trend and Year-on-Year Growth:
- Created a PivotTable and PivotChart based on the data model.
- Draged the appropriate fields (e.g., time, revenue) to the respective areas (e.g., x-axis, y-axis).
- calculated the year-on-year growth by using the DAX formula or Power Pivot functions (e.g., YoY Growth = (Current Year Revenue - Previous Year Revenue) / Previous Year Revenue).

- Arranged the charts, tables, Slicers, and other visualizations on a separate sheet to create a dashboard.
- Formated the dashboard to make it visually appealing and easy to interpret.
