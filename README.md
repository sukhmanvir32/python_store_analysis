# python_store_analysis

# Sales Data Analysis

This project involves the analysis of sales data across multiple months. The goal is to clean, transform, and explore sales data to derive insights such as the best month for sales, sales per city, and the sales distribution across hours of the day.

## **Features**
- Import and merge sales data from multiple CSV files into a single DataFrame.
- Clean and preprocess the data by handling missing values and duplicates.
- Extract useful information, such as the month and city, from the order date and purchase address.
- Perform data exploration and visualization, including:
  - Identifying the best month for sales.
  - Analyzing total sales per city.
  - Exploring sales distribution by hour of the day.

## **Libraries Used**
- `pandas`: For data manipulation and analysis.
- `numpy`: For numerical computations.
- `matplotlib`: For data visualization.

## **Setup**
1. Ensure you have Python 3.x installed on your machine.
2. Install the required libraries using pip:
   ```bash
   pip install pandas numpy matplotlib

## **Data Cleaning**
-The data is cleaned by:
-Removing rows with all null values.
-Dropping any duplicate entries.
-Converting relevant columns to appropriate data types, such as Quantity Ordered and Price Each to numeric types.
-Extracting the month and city from the order date and purchase address.
# Data Analysis and Visualization
## **The project produces the following analyses:**
-Best Month for Sales: A bar chart showing sales across the 12 months.
-Sales per City: A bar chart displaying total sales by city.
-Sales Distribution by Hour: A plot showing how sales are distributed across different hours of the day.
## **Example Output**
-Best Month for Sales: A bar chart showing sales in each month.
-Sales by City: A bar chart showing sales in various cities.
-Sales by Hour: A plot showing how many orders were placed during each hour of the day.

