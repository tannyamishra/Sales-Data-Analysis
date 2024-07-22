# Sales-Analysis-Dashboard

## Project Objective
The objective of this project is to create an interactive sales analysis dashboard. The dashboard provides insights into sales performance across different years, cities, distribution channels, and customers. It helps in understanding sales trends, profit margins, product performance, and customer contributions.

## Dataset
- **Size**: < 1 MB
- **Source**: Kaggle

## Tool Used
- **Power BI**: Used for creating interactive visualizations and dashboards.

## Dashboard Details

### Sales Overview
- Total Sales: 48.5M (down by 9.23% vs PY)
- Total Profit: 18.3M (down by 7.41% vs PY)
- Profit Margin: 37.8% (up by 2.00% vs PY)
- Products Sold: 21.4K (down by 7.68% vs PY)

### Sales CY vs PY by Month
- Bar chart comparing current year (CY) sales to previous year (PY) sales by month.

### Top 5 Sales by City
- Pie chart showing the top 5 cities by sales, highlighting cities like Christchurch, Waitakere, and Hamilton.

### Total Sales vs PY % by Top Products
- Bar chart displaying the percentage change in total sales vs previous year for top products.

### Sales Comparison by Channel
- Bar chart comparing total sales vs PY by distribution channels such as Distributor, Export, and Wholesale.

### Top Products' Performance
- Area chart showing the performance of top products over time.

### Sales Comparison by Customer
- Bar chart ranking customers by sales, with a comparison of their performance vs previous year.

## Report Development Techniques

1. **Data Cleaning**:
   - Utilized Power Query for data cleaning, transforming, and loading (ETL) processes.
   - Handled missing values, removed duplicates, and formatted data types to ensure consistency and accuracy.

2. **Data Modeling**:
   - Implemented a star schema with fact and dimension tables.
   - Established relationships (one-to-many) between tables to ensure proper data integration and integrity.
   - Created active and inactive relationships to manage multiple relationships between tables and switch contexts as needed.
   - Created calculated measures using DAX (Data Analysis Expressions) for advanced data calculations and analysis.

3. **DAX (Data Analysis Expressions)**:
   - Used DAX to create calculated measures for aggregating and analyzing data, such as total sales, profit margins, and percentage changes.

4. **Conditional Formatting**:
   - Applied conditional formatting to highlight key data points and trends, making the dashboard visually appealing and easier to interpret.

5. **Interactive Elements**:
   - Integrated tooltips, and icons to enhance interactivity and user experience.
   - Used slicers and filters to enable dynamic data exploration and analysis.

## Instructions for Viewing the Dashboard
1. Download the Power BI files from this repository.
2. Open the files using Power BI Desktop.
3. Explore the various visualizations and insights provided in the dashboards.

   ![image](https://github.com/user-attachments/assets/5a316789-5721-49d9-b97a-07d08c8b5677)

