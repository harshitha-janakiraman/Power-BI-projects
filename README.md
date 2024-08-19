![image](https://github.com/user-attachments/assets/755352bd-96ba-40ba-a442-1d69368c6a6c)

### Title: 
**"Plant Co. Sales Performance 2023"**

### Overview:
This dashboard provides a comprehensive view of sales performance for Plant Co. in the year 2023. It compares the Year-To-Date (YTD) sales with the Previous Year-To-Date (PYTD) sales and includes various visualizations to highlight performance metrics across different dimensions like countries, products, and time periods. DAX functions were extensively used to build the measures table, which was used for the visualization. Additionally, other Power BI features such as dynamic titles and switching between different measures were also leveraged to make the dashboard as useful and informative as possible. 

### Key Metrics (Top Row):
1. **YTD (Year-To-Date) Sales:** 
   - Displays the total sales accumulated so far in the year 2023, which is **13.00M**.

2. **YTD vs PYTD:** 
   - Shows the difference between the current year's sales (YTD) and the sales during the same period in the previous year (PYTD). Here, the value is **-512.26K**, indicating that sales have decreased compared to the same period last year.

3. **PYTD (Previous Year-To-Date) Sales:** 
   - This is the total sales for the same period last year, which is **13.51M**.

4. **GP% (Gross Profit Percentage):** 
   - The gross profit margin for the current period, which is **39.62%**.

### Visuals and Charts:
1. **Bottom 10 YTD vs PYTD by Country (Treemap):**
   - This chart highlights the bottom 10 countries where the current year's sales (YTD) have underperformed compared to the previous year (PYTD). 
   - The largest box, China, has the most significant decline with **-760.40K**. Other countries like Sweden, France, and Norway also show a decrease in sales.

2. **Sales YTD vs PYTD by Month, Country, Product (Waterfall Chart):**
   - This waterfall chart visualizes the monthly sales difference between YTD and PYTD, categorized by different countries and products. 
   - Green bars represent an increase in sales, red bars indicate a decrease, and the blue bar at the end represents the total difference.

3. **Sales YTD vs PYTD by Month (Line and Column Chart):**
   - This chart shows the trend of sales throughout the year, with a comparison of different product types (e.g., Indoor, Landscape, Outdoor).
   - The red line represents the PYTD sales, while the blue columns show the YTD sales for each month, giving a clear visual of how sales are tracking against last year.

4. **Account Profitability Segmentation (Scatter Plot):**
   - This scatter plot segments accounts based on their gross profit percentage (GP%) and sales performance.
   - Each dot represents an account, with its position showing how it compares in terms of profitability and sales performance (YTD vs PYTD).
   - The slider at the bottom allows filtering of accounts by the YTD vs PYTD difference, focusing on specific ranges.

### Features of Power BI Used:
- **Treemap:** Effectively used to display hierarchical data and quickly identify the countries contributing to the most significant sales declines.
- **Waterfall Chart:** Perfect for showing cumulative effects of sequential positive and negative values, helping users understand the components contributing to the overall sales performance.
- **Line and Column Chart Combination:** Offers a dual perspective, combining trends over time (lines) with comparative data (columns) to give a clearer picture of monthly performance.
- **Scatter Plot:** Used to segment data based on two variables, making it easier to analyze account profitability versus sales performance.
- **Slicers:** The YTD slicer allows users to filter the dashboard by different years or time periods, adding interactivity and flexibility to the analysis.

### Summary:
This Power BI dashboard provides a detailed yet straightforward analysis of Plant Co.'s sales performance for 2023. By comparing the current year's sales with the previous year, it allows stakeholders to identify areas of concern and opportunity across different countries, products, and time periods. The visualizations used in the dashboard effectively communicate the key metrics and trends in a way that's easy to understand and actionable.
