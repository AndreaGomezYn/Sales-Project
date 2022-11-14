# Sales Data Analysis
Analysis of 12-month product sales data.

## Project Overview
Conducted Data Analysis using 12-month product sales data to answer the following real world business questions:
1. What was the best month for sales? How much was earned that month?
2. What City had the highest number of sales?
3. What time should we display adverstisement to maximize likelihood of customer's buying product?
4. What products are most often sold together?
5. What product sold the most? Why do you think it sold the most?

## Code and Resources Used

- **Python Version:** 3.8.8
- **Packages:** pandas, glob, os, numpy, seaborn, matplotlib, calendar
- **Data Collection:** https://www.kaggle.com/datasets/knightbearr/sales-product-data
- **Supporting material:** https://www.youtube.com/watch?v=eMOA1pPVUc4&t=1498s

## Process:
#### Import and merge all 12 data files using glob.glob method, or alternatively, OS Module.
### Data Cleaning
Clean up the data to make it usable for the analysis. This section consisted of the following tasks: 
- Drop NAN Values
- Drop the rows where all elements are missing
- Remove bad data (Duplicate column names in the dataframe)
- Type conversion (to_numeric, astype, to_datetime)

### EDA (Exploratory Data Analysis)
- Identify relevant and useful data from which relevant information can be extracted and added as an additional column (Month, Hour, Minute, Sales, % Total Sales, City)
- Pandas and Matplotlib Methods used:
  - .apply() method
  - groupby() method to perform aggregate analysis
  - Plotting bar charts and lines graphs to visualize the results

## Findings:
