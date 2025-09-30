# A Longitudinal Exploration of Food Inflation and Healthy Diet Affordability Across  (Low- and Middle-Income) Countries

This project explores global food price trends and affordability from 2017 to 2025, focusing on key food groups such as meat, fish, and eggs.  

## Research Questions
 a) How are food prices changing over the years, 
-in different countries, regions, 
-income levels (at country level) 
-for different food products

b) How is accessibility of healthy diets chaning across the years,
-in different countries, regions, 
-income levels (at country level) 

Notes:
Employing EDA, descriptive statistics, trend analysis, regresison analysis?

## Data Sources  
- [Inflation of Consumer Prices (Our World in Data)](https://archive.ourworldindata.org/20250916-102301/grapher/inflation-of-consumer-prices.html)  
- [Share of Population for Whom a Healthy Diet is Unaffordable (Our World in Data)](https://ourworldindata.org/grapher/share-healthy-diet-unaffordable#reuse-this-work)  
- [WFP - Food Prices](https://data.humdata.org/dataset/global-wfp-food-prices)  

## Data Cleaning  
- Dropped unnecessary columns from **World Food Prices (WFP)** dataset  
- Handled missing values by filling or removing where appropriate  
- Filtered datasets for **2017–2024** to align with analysis scope  
- Converted data types (object → float) for numerical columns  

## Data Wrangling  
- Imputed missing price values in USD using interpolation  
- Grouped data by **category** (Meat, Fish, Eggs) and **country**  
- Aggregated data by calculating **sum** and **mean** for comparison across countries and years  



