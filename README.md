# Diwali Sales Analysis

## Overview
This project analyzes Diwali sales data to understand customer demographics, purchasing behavior, and sales trends. The dataset consists of sales records, including customer details, product categories, and transaction amounts. The goal of this analysis is to derive insights that can help businesses optimize their marketing strategies and improve sales performance.

## Dataset
The dataset contains **11,251 records** and **15 columns** related to customer transactions. After data cleaning, the final dataset includes **11,239 records** with the following columns:
- **User_ID**: Unique identifier for customers
- **Cust_name**: Customer name
- **Product_ID**: Unique identifier for products
- **Gender**: Customer gender (Male/Female)
- **Age Group**: Age category of the customer
- **Age**: Exact age of the customer
- **Marital_Status**: 0 for single, 1 for married
- **State**: Customer's location
- **Zone**: Regional classification of states
- **Occupation**: Customer's job sector
- **Product_Category**: Category of purchased products
- **Orders**: Number of orders placed
- **Amount**: Total amount spent per transaction

## Data Preprocessing
- Removed unnecessary columns ('Status', 'unnamed1')
- Checked and handled missing values by removing null entries
- Converted 'Amount' column data type from float to integer
- Renamed 'Marital_Status' column to 'Shaadi'

## Exploratory Data Analysis (EDA)
### Key Insights
1. **Gender Analysis**:
   - Most buyers are **female** and they contribute to higher total purchases.

2. **Age Group Analysis**:
   - The **26-35 years age group** has the highest number of buyers and purchase amounts.

3. **State-wise Analysis**:
   - The highest number of orders and total sales come from **Uttar Pradesh, Maharashtra, and Karnataka**.

4. **Marital Status Analysis**:
   - Married women have higher purchasing power and contribute significantly to sales.

5. **Occupation-wise Analysis**:
   - Most buyers are from **IT, Healthcare, and Aviation** industries.

6. **Product Category Analysis**:
   - The most sold product categories are **Food, Clothing, and Electronics**.

7. **Top Selling Products**:
   - The top 10 most sold products were identified by analyzing 'Product_id' and 'Orders'.

## Visualizations
- **Bar charts** were used to analyze Gender, Age Group, State-wise sales, Marital Status, Occupation, and Product Categories.
- **Grouped bar charts** helped compare sales trends for different categories.
- **Top products** were visualized using bar plots.

## Conclusion
- **Married women aged 26-35 years** from **Uttar Pradesh, Maharashtra, and Karnataka** working in **IT, Healthcare, and Aviation** sectors are the most frequent buyers.
- They primarily purchase products from **Food, Clothing, and Electronics** categories.

## Technologies Used
- **Python**: Data processing and analysis
- **Pandas**: Data cleaning and manipulation
- **Matplotlib & Seaborn**: Data visualization

## How to Run the Project
1. Clone the repository:
                         git clone https://github.com/your-username/diwali-sales-analysis.git
   
3. Install required libraries:
                          pip install pandas numpy matplotlib seaborn

5. Run the Jupyter Notebook or Python script to generate analysis and visualizations.

## Future Improvements
- Perform **predictive analysis** to forecast future sales trends.
- Implement **machine learning models** for customer segmentation.
- Develop an **interactive dashboard** using Power BI or Tableau.



