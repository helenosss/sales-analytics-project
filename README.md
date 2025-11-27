# sales-analytics-project
# Sales Analytics Project

This project analyzes multi-year sales data for a global retail company operating both online and offline.  
The goal is to clean the data, explore key business metrics, and identify meaningful insights that support decision-making.

## Project Structure
The dataset consists of three CSV files:
- **events.csv** — sales transactions over several years  
- **products.csv** — product categories and product codes  
- **countries.csv** — country and region reference information

## Objectives
1. **Data Overview**
   - Exploratory review of all columns  
   - Identification of key fields connecting the three tables  
   - Summary of dataset structure and meaning

2. **Data Cleaning**
   - Detection and handling of missing values  
   - Fixing incorrect data types  
   - Removing duplicates  
   - Identifying and addressing anomalies  

3. **Data Analysis**
   - Merging the three datasets into a unified dataframe  
   - Calculation of core business metrics (orders, revenue, profit, countries covered, etc.)  
   - Sales performance analysis by:
     - Product categories  
     - Geography (countries and regions)  
     - Sales channels (online vs offline)  
   - Analysis of shipping time intervals by:
     - Product categories  
     - Countries  
     - Regions  
   - Relationship between profit and shipping duration  
   - Time-series analysis of sales dynamics  
   - Day-of-week analysis and seasonality detection  

4. **Visualizations**
   - Revenue, cost, and profit charts  
   - Geographic heatmaps  
   - Category and channel performance plots  
   - Time-series dashboards  
   - Shipping time distribution plots  

## Tools & Technologies
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn, Plotly  
- Google Colab  

## Results
The final notebook includes:
- Cleaned and merged dataset  
- Analytical insights on product performance, regions, and channels  
- Visualizations of revenue, profit, and sales dynamics  
- Business-oriented conclusions and recommendations  

## File
`sales_analytics_project.ipynb` — full project code, analysis, and visualizations.
