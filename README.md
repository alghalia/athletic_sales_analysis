# Athletic_sales_analysis
Analyze sales data to gain insights into which cities in the U.S. have sold the most athletic wear. 


## Project Overview

This project involves analyzing sales data for athletic products from two CSV files: `athletic_sales_2020.csv` and `athletic_sales_2021.csv`. The main objectives of the analysis are to:

1. Combine sales data from both years.
2. Perform various groupby and pivot table operations to derive insights.
3. Determine specific details such as the day with the highest sales and the top-selling retailers.

## Data Files

- `athletic_sales_2020.csv`: Contains sales data for the year 2020.
- `athletic_sales_2021.csv`: Contains sales data for the year 2021.

## Analysis Steps

### 1. Load and Inspect Data
- Load the CSV files into Pandas DataFrames.
- Check for null values and ensure that the columns have consistent data types.
- Convert the `invoice_date` column to a datetime datatype for easier manipulation and analysis.

### 2. Combine Data
- Combine the data from both years into a single DataFrame using the `concat` method.

### 3. Groupby and Pivot Table Operations
- Determine the total number of products sold for each region, state, and city.
- Determine the total sales for the products sold for each retailer, region, state, and city.
- Identify the retailer with the most sales of women's athletic footwear.
- Determine the day with the most sales of women's athletic footwear.
- Resample the sales data into daily and weekly bins to analyze trends over time.

### 4. Key Insights
- The top 5 regions, states, and cities by total products sold.
- The top 5 regions, states, and cities by total sales.
- The retailer that sold the most women's athletic footwear.
- The day with the highest sales of women's athletic footwear.
- Weekly sales trends for women's athletic footwear.

## Key Python Functions and Methods Used

- `read_csv`: To load the CSV files into DataFrames.
- `concat`: To combine multiple DataFrames.
- `groupby`: To aggregate data based on specific columns.
- `pivot_table`: To create pivot tables for more advanced data summarization.
- `sort_values`: To sort the DataFrames based on specific columns.
- `resample`: To resample the time series data into different time bins (daily, weekly).

- Conclusion
This analysis provides a comprehensive overview of the sales data, highlighting key trends and insights. By using various data manipulation techniques in pandas, we can effectively summarize and understand the sales performance of different products across different regions and time periods.
