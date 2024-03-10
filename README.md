#Amazon_sales_python_project
1. Introduction:
The project involves the analysis of an Amazon sales report using Python programming and various data science libraries. The dataset contains information about orders, fulfillment status, sales channels, and other relevant details.

2. Data Loading and Inspection:
* The dataset was loaded from a CSV file using Pandas (pd.read_csv).
* Initial exploration of the data included checking its shape and displaying the first few rows to understand its structure.                           
3. Data Cleaning and Preprocessing:
* Unrelated or blank columns, such as 'New' and 'PendingS', were dropped using df.drop.
* Null values were handled, with rows containing null values removed using df.dropna.
4. Data Type Modification:
* The 'ship-postal-code' column was converted to an integer data type.
* The 'Date' column was converted to a datetime format.
5. Exploratory Data Analysis (EDA):
(5.1) Size Preferences:
A count plot and a bar plot were used to visualize the distribution of sizes in the sales data.
The analysis revealed that M-size is the most preferred size among buyers.
(5.2) Courier Status and Order Status:
A count plot was used to explore the distribution of orders based on courier status and order status.
The majority of orders were shipped, and the fulfillment status was mainly 'Shipped - Delivered to Buyer.'
(5.3) B2B Buyers:
A pie chart was used to represent the distribution of B2B and non-B2B buyers.
Most buyers (99.3%) were identified as retailers, while 0.7% were B2B buyers.
(5.4) Fulfilment Distribution:
A pie chart was used to visualize the distribution of fulfillment methods.
The majority of orders were fulfilled by Amazon.
(5.5) State-wise Distribution:
Count plots and bar plots were used to explore the distribution of orders across different states.
Maharashtra was identified as the state with the highest number of buyers.
(5.6) Data Exploration:
Histograms and scatter plots were employed to explore the distribution and relationships between different variables, including 'Category' and 'Size.'
6. Conclusion:
The data analysis revealed several insights into the Amazon sales data, including the popularity of M-size, high demand for T-shirts, the dominance of Amazon in fulfillment, and a significant customer base in Maharashtra. These findings can inform business strategies, inventory management, and customer targeting.

7. Recommendations:
* Consider optimizing inventory for M-size products.
* Focus marketing efforts on T-shirts, given their high demand.
* Ensure efficient fulfillment through Amazon, considering its popularity among buyers.
* Target promotional activities in regions with high buyer concentrations, such as Maharashtra.
8. Future Work:
* Further analysis could include time-series analysis to identify sales trends over time.
* Customer segmentation analysis to understand different buyer groups.
* Integration with external data sources for a more comprehensive view of market trends.
9. Acknowledgments:
* Appreciation for the use of Python, Pandas, Matplotlib, Seaborn, and other libraries for efficient data analysis.
This report provides a comprehensive overview of the data analysis project, highlighting key findings, recommendations, and potential areas for future exploration.








