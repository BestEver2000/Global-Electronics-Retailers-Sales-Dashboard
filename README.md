
# Global Electronics Retailers Sales Dashboard

## Project Overview
This project is a sales dashboard that provides insights into sales performance, orders trend, product performance, stores performance, etc. It was created using Power BI for visualization and Excel for data cleaning.

## Key Features

__Sales Performance__: Analyze overall and segmented sales metrics.

__Orders Trend__: Track and visualize trends over time.

__Product Performance__: Identify top performing and underperforming products.

__Store Performance__: Compare and assess performance across multiple stores.

__Customer Demographics__: Visualize customer distribution by age, gender, and geographic location to uncover trends.


## Tools & Technologies
__Excel__: Data cleaning and preprocessing.

__Power BI__: Data visualization and dashboard creation.

## Dataset
The dataset used in this project is the Global Electronics Retailers Sales Data, sourced from Kaggle. It contains detailed information about sales, store operations, product details, and customer demographics. The data spans from 2016 to 2021, with only two months of data available for 2021. It consists of four CSV files:

- __Sales__: 62,884 rows of transaction data.
- __Stores__: 67 rows containing store details.
- __Products__: 2,517 rows of product information.
- __Customers__: 15,266 rows of customer data.


## Data Structure
![Description of the image](Data_Structure.png)

## Data Cleaning and Preparation
- Removed unnecessary columns, including 'Subcategory Key', 'Category Key', 'Zip Code', etc., to focus on relevant data.
- Eliminated duplicates to ensure data accuracy.
- Removed unwanted characters from 'State' column.
- Corrected the date format in 'Order Date' and 'Delivery Date' columns.

## Formulas used

![Description of the image](Formulas.png)




## How to use this dashboard

To view and interact with this dashboard, make sure you have Power BI Desktop installed. Then, download the .pbix file and open it in Power BI Desktop.




## Conclusion
In this Power BI dashboard project, I visualized sales performance data to create an interactive and user friendly dashboard. The data was initially cleaned and preprocessed using Excel, before importing it into Power BI. The dashboard highlights key sales metrics, including total revenue, revenue by brand, product performance, and customer segmentation.

The interactive features, such as slicers for filtering provide users with the ability to explore specific segments and gain actionable insights. This dashboard empowers stakeholders to monitor sales trends, identify underperforming products, and make data driven decisions to optimize sales strategies.
