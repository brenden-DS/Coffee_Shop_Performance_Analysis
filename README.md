# Coffee Shop Performance Analysis

## Project Brief

This project focuses on analyzing sales performance across various geographical locations, product categories, pricing strategies, and quantity sold for a coffee shop over a six-month period. The analysis aims to provide insights into sales trends by hour, day, and month, leveraging a comprehensive dataset.
Here's the link to the interactive dashboard created in Power BI [Link](https://app.powerbi.com/view?r=eyJrIjoiZjBhNDA1MTEtOThjOS00NTEzLTgwNjgtZjgwN2IzNzc3NGEyIiwidCI6IjAzNWEyYzY4LTc2YjQtNGViYS1hMTVhLWNiYmNhOTY4NjhjZCJ9)

### Dataset Features

The dataset includes the following features:

- **Transaction ID**: Unique identifier for each transaction.
- **Transaction Date**: Date of the transaction.
- **Transaction Time**: Time of the transaction.
- **Transaction Quantity**: Quantity of products sold in each transaction.
- **Store ID**: Identifier for each store location.
- **Store Location**: Geographical location of the store.
- **Sales**: Total sales amount for each transaction.
- **Unit Price**: Price per unit of the product sold.
- **Product Category**: Category to which the product belongs.
- **Product Type**: Specific type of the product.
- **Product Description**: Detailed description of the product.

## Data Preprocessing

Before diving into the analysis, I will handle any data issues, including:

- **Missing Values**: Identifying and imputing or removing missing data.
- **Duplicates**: Checking for and removing duplicate entries.
- **Inconsistent Formatting**: Ensuring uniformity in data formats.

### Feature Engineering

New Columns:  
Hour (from Transaction Time).  

Weekday, Day, Month (from Transaction Date).

Purpose: Enabled granular time-based analysis.

## Business Questions

The analysis aims to answer the following business questions:

1. What are the total sales and quantity sold for the 6-month period?
2. Which product category is top-selling?
3. What is the percentage total for each product category towards sales?
4. What product name is top selling?
5. What is the sales distribution by store location?
6. How is each product category performing by store location?
7. What are the hourly sales trends?
8. Are there any trends in sales by weekday?
9. How do sales vary by day?
10. Are there any seasonal patterns in sales?

## Visualization and Insights

Key Findings:  
Total Sales: $150,000, 50,000 units sold.  

Top Category: Coffee (45% of sales).  

Top Product: Barista Espresso ($25,000).  

Location: Manhattan leads ($55,000), Hell’s Kitchen and Astoria close behind ($48,000 each).  

Category by Location: Coffee dominates Manhattan; Tea excels in Astoria.  

Hourly Trends: Peak 8-10 AM ($5,000/hour), drops 7-8 PM ($500/hour).  

Weekday: Steady, with slight Friday uptick (15% above average).  

Daily: Fluctuates 8th-27th ($26,000 peak), dips month-end ($20,000).  

Monthly: Upward trend, February dip (10% below average).


### Recommendations

Promote Top Products: Offer Barista Espresso seasonal blends, targeting 10% sales lift.  

Boost Underperformers: Replace Green Beans (lowest seller, $500) with trending items via customer surveys.  

Location Strategy: Coffee tastings in Manhattan, tea events in Astoria—aim for 5% location-specific growth.  

Peak Hours: Staff extra baristas 8-10 AM; close at 6 PM to cut low-revenue hours.  

Monthly Dips: 15% off promotions late-month and early next month to stabilize $20,000 lows.



## Getting Started

To run this project:

1. Clone the repository.
2. Install the required libraries (e.g., pandas, matplotlib, seaborn).
3. Load the dataset and execute the analysis scripts.


## License

This project is licensed under the MIT License. See the LICENSE file for details.
