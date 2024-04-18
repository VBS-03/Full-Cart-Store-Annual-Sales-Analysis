# Full Cart Store Annual Analysis

## Objective


THE “FULL CART STORE” WANTS TO CREATE AN ANNUAL SALES REPORT FOR 2022.SO THAT, FULL CART STORE CAN UNDERSTAND THEIR CUSTOMERS AND GROW THEIR SALES IN YEAR 2023.

## Key Performance Indicators (KPIs) to be examined include:

-       Comparison of the Sales v/s orders using single chart.
-       Which month got the highest sale and orders?
-       Who purchased more- Men or Women in 2022?
-       What are the different order status in 2022?
-       List top 10 states contributing to the sales?
-       Relation between Age and gender based on number of orders.
-       Which channel is contributing to the maximum sales?
-       Highest selling category?

### Steps followed 

- Step 1: Cleaned and transformed data in the excel.
- Step 2: Removed Nulls, changed the datatypes where ever required, changed the date format, 
- Step 3: Checked for some ambigious data present in columns and remove them.
- Step 4: We had only city name in the dataset. So we have included a new column "State" using the Vlookup.
- Step 5: We have create a column "Age-Group" which could help us with our data analysis.
- Step 6: Created a new column "Month" by extracting the month from the given "Date" column using "Text('cell','mmm')".
- Step 7: Created Pivot Tables which could help us to create the individual visuals as per the KPIs.
- Step 8: Utilized the above visuals to create a final interactive dashboard that helped us examin all the KPIs and thereby helping us with our analysis.

# Snapshot of Dashboard (Power BI DESKTOP)

![Full cart](https://github.com/VBS-03/T20-Cricket-World-Cup-Analysis/assets/162421729/d3163c6a-076b-4536-8ed6-3b0792bbc51e)
 
# Insights

Based on the analysis, the following key insights were observed:

- The highest sales and orders were recorded in the month of March.
- Approximately 64% of purchases were made by women, indicating a higher likelihood of purchase compared to men.
- Maharashtra, Karnataka, and Uttar Pradesh emerged as the top three states, accounting for approximately 35% of sales.
- The adult age group (30-49) contributed the most to sales, making up around 50% of purchases.
- Amazon, Flipkart, and Myntra were the primary sales channels, contributing to approximately 80% of total sales.
- The top-selling product category was "Sets".


### In conclusion, to enhance sales for the "Full Cart Store," it is recommended to target women customers aged 30-49 residing in Maharashtra, Karnataka, and Uttar Pradesh. This can be achieved by offering targeted advertisements, promotions, and coupons on platforms such as Amazon, Myntra, and Flipkart. Additionally, focusing on planned sales or offers between January and May could yield optimal results.
