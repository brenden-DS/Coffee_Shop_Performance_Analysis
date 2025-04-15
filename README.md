# Coffee Shop Performance Analysis


### Overview/Context:
This project analyzes sales performance for a coffee shop chain over a six-month period, focusing on geographical locations, product categories, pricing strategies, and quantity sold. The objective is to uncover sales trends by hour, day, and month to inform business strategies. The analysis was conducted in Python using a Jupyter Notebook for full exploration, with an interactive dashboard created in Power BI for summarized insights: [Link](https://app.powerbi.com/view?r=eyJrIjoiZjBhNDA1MTEtOThjOS00NTEzLTgwNjgtZjgwN2IzNzc3NGEyIiwidCI6IjAzNWEyYzY4LTc2YjQtNGViYS1hMTVhLWNiYmNhOTY4NjhjZCJ9).


### Dataset:
The dataset comprises transaction records with the following features: Transaction ID, Transaction Date, Transaction Time, Transaction Quantity, Store ID, Store Location, Sales, Unit Price, Product Category, Product Type, and Product Description. It captures sales activities across multiple store locations, totaling $150,000 in sales and 50,000 units sold.

### Data Preprocessing:
Data cleaning was performed using Python’s pandas library in a Jupyter Notebook. Steps included:  
- Handling missing values by imputation or removal.  
- Identifying and eliminating duplicate entries.  
- Standardizing date and time formats for consistency across the dataset.

### Feature Engineering:
To enable granular time-based analysis, the following columns were created:  
- Hour: Extracted from Transaction Time.  
- Weekday, Day, Month: Derived from Transaction Date.
- These features facilitated detailed trend analysis across different time dimensions.

### Business Questions:
The analysis addresses the following questions:  
- What are the total sales and quantity sold over the six-month period?  
- Which product category and product are top-selling, and what is each category’s sales contribution?  
- How are sales distributed across store locations, and how do categories perform by location?  
- What are the hourly, daily, weekly, and monthly sales trends, including seasonal patterns?

### Visualizations:

Overview
![Overview]()

- Visualizations were created using Python libraries (Matplotlib and Seaborn) in the Jupyter Notebook, including line charts for hourly trends, bar charts for category sales, and heatmaps for location performance. An interactive Power BI dashboard was developed to present key metrics, such as sales by location and hourly trends, with a Canva-designed background for enhanced visual appeal.
  
Insights:  
- Sales Overview: Total sales reached $150,000 with 50,000 units sold.  
- Top Performers: Coffee led as the top category (45% of sales), with Barista Espresso as the top product ($25,000).  
- Location Performance: Manhattan generated the highest sales ($55,000), followed by Hell’s Kitchen and Astoria ($48,000 each). Coffee dominated in Manhattan, while Tea performed strongly in Astoria.  
- Time Trends: Hourly sales peaked at 8-10 AM ($5,000/hour) and dropped to $500/hour at 7-8 PM. Weekday sales were steady, with a 15% uptick on Fridays. Daily sales fluctuated, peaking at $26,000 mid-month 
   and dipping to $20,000 at month-end. Monthly trends showed growth, with a 10% dip in February.  
- Underperformers: Green Beans recorded the lowest sales at $500.

### Recommendations:  
- Promote High Performers: Introduce seasonal blends for Barista Espresso to target a 10% sales increase.  
- Revamp Low Performers: Replace Green Beans with trending items based on customer surveys to boost sales.  
- Location-Specific Strategies: Host coffee tastings in Manhattan and tea events in Astoria, aiming for a 5% sales lift in each location.  
- Optimize Operations: Staff extra baristas during 8-10 AM peak hours and consider closing at 6 PM to reduce low-revenue hours.  
- Address Monthly Dips: Offer 15% off promotions at month-end and early next month to stabilize sales at $20,000 lows.
  
Conclusion:
- This Python-based analysis reveals key sales drivers, with Coffee and Barista Espresso leading, and identifies operational efficiencies like peak-hour staffing. The Jupyter Notebook provides a detailed breakdown, while the Power BI dashboard offers an accessible overview for decision-makers. These insights pave the way for targeted strategies to enhance revenue and customer engagement.

