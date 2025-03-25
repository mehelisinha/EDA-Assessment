# Exploratory Data Analysis (EDA) Assessment
## Overview
This project performs an exploratory data analysis on `Product_DataSet.csv` using Python and visualisations are performed using PowerBI.
The project includes:
## Python Analysis (Jupyter notebook):
- Dataset loading and viewing using pandas. The dataset has 4566 rows and 11 columns.
  ## Dataset overview:
    - The dataset contains **product-related features** such as:
    - **Category**: Type of product (e.g., clothing, jewelry, footwear)
    - **MRP**: Original price of the product
    - **Discount**: Discount applied (%)
    - **SellPrice**: Selling price after discount
- Setting file paths for the uncleaned and cleaned dataset.
- Dataset cleaning which includes:
    - checking and handling missing values, duplicate rows.
    - dropping unnecessary column.
    - Converting key features like MRP and SellPrice from object type to numeric.
- Summary Statistics using .describe(): mean, median(50%), standard deviation.
- Converting the cleaned dataframe to .csv file for further usage in PowerBI visualisation.
## Power BI visualizations:
Created PowerBI report in both .pdf and .pbix format with the following representations:
- **Top 10 selling brands**: Used a bar chart. The chart represents that the top 10 selling brands.
- **Discount Analysis by Category**: Used stacked bar-chart. The chart represents the average discount by each category of product.
- **Category wise product distribution**: Used pie chart. The chart represents each category with the count of product they have along with their percentages.
Key Findings from the Power BI Visualisation:
- The most selling brand is **and** with **709** sold products.
- Jewellery-Women has the highest average discount with **40.17%**.
- Westernwear-women has the highest number of product with a count of **1654 (36.22%)**.
- Fragnance-Women as the least number of product with a count of **167 (3.66%)**.
**Open `EDA_Report.pbix` in **Power BI Desktop** or use `EDA_Report.pdf` as an alternative to explore insights.
## Folder Structure
- `data/` → Contains the raw and the cleaned dataset
- `notebooks/` → Jupyter Notebook with EDA code
- `visuals/` → Power BI reports (pbix and pdf)
