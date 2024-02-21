
# Analyzing Sales Patterns and Pricing Anomalies in Bahbud Botique's Inventory Data

## Project Overview
This project delves into the sales data of Bahbud Botique, aiming to uncover insights into pricing anomalies and purchasing patterns among different items sold. Utilizing the Interquartile Range (IQR) method, we identify outliers in the product pricing to ensure competitive and fair pricing strategies. Additionally, we apply one-hot encoding and the Apriori algorithm to analyze which items are frequently bought together, providing valuable information for marketing strategies and inventory management.

## Features
- **Outlier Detection**: Identification of pricing anomalies using the IQR method to ensure products are competitively priced.
- **Association Rule Mining**: Discovery of item purchase patterns using the Apriori algorithm, revealing which items are often bought together.
- **Data Transformation**: Transformation of categorical data into a one-hot encoded format for analysis.

## Data Analysis Steps
1. **Exploratory Data Analysis (EDA)**: Initial examination of the dataset to understand the structure, identify missing values, and summarize the data.
2. **Outlier Detection**: Using the IQR method to find outliers in the product prices.
3. **Data Transformation**: Converting categorical data into a one-hot encoded format to prepare for association rule mining.
4. **Association Rule Mining**: Applying the Apriori algorithm to identify frequent item sets and generate rules indicating purchasing patterns.

## Technologies Used
- Python
- Pandas for data manipulation
- Matplotlib and Seaborn for data visualization
- Mlxtend for applying the Apriori algorithm and association rule mining

## How to Run the Project
1. Ensure you have Python installed along with Pandas, Matplotlib, Seaborn, and Mlxtend.
2. Clone the repository to your local machine.
3. Navigate to the project directory and run the Jupyter Notebook to view the analysis.
