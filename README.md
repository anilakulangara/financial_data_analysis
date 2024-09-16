# Powerbi Project - Data Analysis of Financial Sample
### Objective:
The primary goal is to provide a user-friendly and insightful financial reporting system in Power BI, empowering stakeholders with the necessary tools to make informed financial decisions.

### Report Overview
  - Dashboard: The report consists of two dashboards, focusing on sales overview and profit insights. You can navigate through the dashboards using the buttons provided in the bottom right.
  - Slicers: To interact with the data, you can use slicers located at the top right of each dashboard. These slicers allow you to customize the view based on your requirements.
  - Visualizations: Visualizations such as charts, tables, and reports provide a comprehensive view of the financial data.
  - 
Bookmarks are also provided for showing sales in 2013 and 2014 separately and sales in the United States for the government sector.

### Dashboards
#### Sales overview 
    - Offers a detailed analysis of sales, revenue and units sold
    - Offers geographic insights with maps and location-based data which allows you to explore sales across country.
    - Helps you understand which products, country and segment contribute the most to revenue 
#### Profit Insights
    - Offers a detailed analysis of profit
    - Helps you understand which products contribute the most to profit.

### How to Use the Report
Utilize slicers to focus on specific time periods, departments, or financial metrics. Click on data points or visual elements to drill down for more detailed information. Explore different dashboards to obtain a well-rounded view of financial performance.

### Measures Used
The data in this report is based on the Financial Sample dataset and is periodically updated.
The following measures were created for the project.
```
Total profit = SUM((financials[Profit]))
Total Revenue = sum(financials[Gross Sales])
Total sales = SUM(financials[ Sales])
Total Unit Sold = SUM(financials[Units Sold])
Overall Profit Margin = DIVIDE(SUM(financials[Profit]), SUM(financials[Gross Sales])) * 100
Gross Profit = SUM(financials[Gross Sales])-SUM(financials[COGS]) 
Total Revenue = SUM(financials[Gross Sales])
```

### Conclusion
We hope this Financial Sample Power BI report helps you gain a deep understanding of financial performance and aids in making informed financial decisions. 
Some insights from the analysis are:
1. France is the top profit-making country.
2. Government segment has more sales and more profit.
3. Paseo is the top-selling product.
5. The gross profit is 26.10M.
6. Overall profit margin is 13.21
