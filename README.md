# NSDP_Challenge_Katari
Objective of the Challenge

The objective of this analysis is to explore and visualize the delay data for multiple countries over several years. The key objectives include:

Analyzing yearly trends in delays for each country.
Comparing average delays by region.
Identifying the top 5 countries with the highest delays.
Conducting an outlier analysis to identify countries with extreme delays.

The analysis is performed using Python for data processing and Power BI for creating interactive visualizations.

Steps to Run Your Python Scrip
  Place your raw data files in the same directory as the Python script.
  Ensure the script is referencing the correct file paths.
  Run the script in your terminal or IDE (e.g., Jupyter Notebook or VS Code)
  The Python script processes the data and exports three CSV files:
      Average_Delay_By_Country.csv: Contains the average delay by country and year.
      Regional_Averages.csv: Contains average delay per region for each year.
      Outliers.csv: Contains countries identified as outliers based on z-scores.


Instructions on How to Open and Explore the Power BI Report
  Install Power BI Desktop from Power BI Official Website.
  
The report includes various visualizations:
    Yearly Delay Trends: A line chart showing the average delay per year for each country. With Slicer     that allow you to change the region and year 
    Regional Performance Comparison: A clustered bar chart comparing average delays by region for a            selected year. With a Slicer to allow you to change the Country Code
    Top 5 Countries with Highest Delays: A table listing the top 5 countries with the highest average     delays.
    Outlier Analysis: A scatter plot or table identifying countries with outlier delays based on z-scores.

Assumptions and Decisions Made During the Analysis:
  Z-Score Calculation:For identifying outliers, a z-score threshold of 1.8 was used instead of the typical   3 due to the relatively small number of data points available. This ensures that more relevant outliers   are detected without excluding too many data points.

  Top 5 countries: JPN,EGY,ARG,IND, and MEX




    
