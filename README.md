Project-2: Summer and Winter Olympics Analysis
Dependencies
pandas
numpy
matplotlib.pyplot
csv

Data
Summer Olympics CSV
Winter Olympics CSV
Medal Data Dictionary CSV

Data Processing
Imported the necessary dependencies
Created a file path to import the data from the summer olympics, winter olympsics, and the medal data dictionary
Turned the summer and winter Olympics CSV into dataframes
Merged the summer and winter dataframes together using an outer join and named it merged_df
Renamed the 'Country' column to 'code' to prepare for merging with the dictionary dataframe
Merged the dictionary dataframe into the merged_df and set the index to 'Athlete' to create the final_merged_df
Filtered the data to the year 2014 to match the Population and GDP per Capita data
Created dataframes for gold, silver, and bronze medals
Sorted the data by each country
Counted the number of gold, silver, and bronze medals each country had using the groupby function
Created a dataframe called 'medal_df' to show the total amounts of each medal
Analysis
We wanted to see if countries with a higher GDP performed better than the ones that had a lower GDP. We were surprised to find that the countries with a lower GDP actually out performed the countries with a higher GDP.

Sorting
Sorted the GDP values from least to greatest
Sorted the silver medals by country in alphabetical order
Sorted the bronze medals by country in alphabetical order
Sorted the gold medals by country from greatest to least
Sorted the silver and bronze medals by country in alphabetical order again for further analysis.

Conclusion
The analysis of the Summer and Winter Olympics data shows that countries with lower GDPs outperform those with higher GDPs in terms of medal count. Further analysis and research is needed to understand the reasons behind this correlation.
