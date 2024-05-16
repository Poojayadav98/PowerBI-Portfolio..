# Project Title: Sales and Profits Insights of Global Superstore Data.

## Objective
The objective of this project is to analyze sales and profit data from a global superstore to uncover trends, patterns, and insights that can help in strategic decision-making.

## Data Source
The dataset used for this analysis is from a global superstore and contains sales, quantity, and profit information over a period of time. The dataset includes various categories such as furniture, office supplies, and technology.

## Methodology
1. **Data Cleaning**: Removed duplicates and handled missing values.
2. **Data Transformation**: Created new columns for better analysis, such as extracting year, quarter, and month from the order date.
3. **Calculated Measures**: Created a calculated measure for profit margin using the formula:
   ```DAX
   Profit Margin = DIVIDE(SUMX(Orders, Orders[Profit]), SUMX(Orders, Orders[Sales]))
4. **Visualization**: Developed various visuals to highlight key insights about sales and profit trends, performance by sub-category and market, and profit margins by category.

## Visualizations
1. Cards: Displaying total Sales, Quantity, and Profit.
2. Slicers:
Category Slicer: Allows filtering by Furniture, Office Supplies, and Technology.
Date Range Slicer: Allows filtering by order date range.
3. Sales and Profit by Year, Quarter, and Month: A line chart showing the trends of sales and profit over time.
4. Sales and Profit by Sub-category: A bar chart displaying sales and profit across different product sub-categories.
5. Average of Quantity and Profit by Market: A bar chart comparing the average quantity sold and profit generated across different markets.
6. Profit Margin by Category: A bar chart showing the profit margins for each main category.

## Key Insights
1. Sales Trend: Sales show a steady increase over the years, peaking in Q4 of each year.
2. Top Sub-categories: Phones and Copiers are the top-performing sub-categories in terms of sales and profit.
3. Market Performance: Canada leads in average profit, followed by the US and the EU.
4. Profit Margins: Technology and Office Supplies have higher profit margins compared to Furniture.

## Conclusion
This analysis provides valuable insights into the sales and profit performance of the global superstore. These insights can help the management make informed decisions to enhance sales strategies and improve profitability.

## Files in this Project
Data/Global_superstore.xlsx: The dataset used for analysis.\
Reports/Global_superstore.pbix: The Power BI report file.\
Screenshots/: Folder containing screenshots of the key visuals from the Power BI report.\
Report file/
