# ecommerce-sales-analysis
Excel-based dashboard project analyzing sales, customer behavior, and product trends
# Sales Data Analysis and Visualization

## Project Overview
This project involves the analysis of sales data using Excel and the creation of insightful visualizations. The dataset contains information about customer purchases, including product details, quantities, total prices, and customer IDs.

The visualizations are aimed at answering key questions related to sales patterns, customer behavior, and product demand. These visualizations were created to help decision-makers understand customer segments, sales trends, and more.

## Visualizations:
1. **Top 10 Frequently Purchased Products**  
   Shows the products with the highest quantities sold.
   
2. **Total Sales by Country**  
   Displays the total sales across different countries.
   
3. **Top 5 High-Spending Customers**  
   Highlights the top customers who have spent the most across different countries.
   
4. **High-Value vs Low-Value Purchases**  
   Compares high and low-value purchases across countries.

5. **Sales and Quantity Trend Over Time**  
   Displays the trend of sales and quantities over different months.

6. **Customer Purchase Frequency by Day of the Week**  
   Analyzes customer behavior based on the day of the week.

## Tools Used:
- Excel (for data cleaning and visualization)
- GitHub (for version control and sharing)

## How to Run:
1. Download the dataset and open it in Excel.
2. View the various visualizations and analysis created using pivot tables and charts.
Steps Followed in the Project:
Import Data:

You imported the dataset from Kaggle (though the exact source was not mentioned, but it's typical for Kaggle datasets).

Data Cleaning:

You removed any empty cells or rows with missing values to ensure the dataset is clean for analysis.

You converted the InvoiceDate column to the correct datetime format, allowing for easier manipulation and extraction of date-based features.

Feature Engineering:

You created new calculated columns to enrich the dataset, such as:

TotalPrice: This was calculated as Quantity * UnitPrice.

HighValueFlag: You flagged purchases as high value if the TotalPrice was greater than 50.

InvoiceYearMonth: You extracted the year and month from the InvoiceDate column for time-based analysis.

Day of Week: You extracted the day of the week from InvoiceDate to identify purchasing patterns based on the day.

Visualization:

You created several visualizations based on your cleaned data:

Top 10 Frequently Purchased Products: This was based on the total quantity of products sold, with a slicer for country.

Total Sales by Country: This was a sum of total price by country, with a slicer for product description.

Top 5 High-Spending Customers in Different Countries: This visualization displayed the top 5 customers by total spending, with a slicer for country and product description.

High-Value vs Low-Value Purchases: A breakdown of high-value and low-value purchases in each country, with a slicer for product description.

Sales and Quantity Progress Over Time (Monthly): This chart visualized the total sales and quantities sold through each month, with slicers for country and product description.

Sales and Quantity by Day of the Week: A visualization showing total sales and quantities by the day of the week, with a slicer for country.
