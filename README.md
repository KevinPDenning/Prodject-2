Project 2
------------------------------------------------
We started of by importing the dependcies ( pandsa, numpy, matplotlib.pyplot, and csv)
Created a file path to import the data from the summer olympics, winter olympsics, and the dictionary to get the medal data 
Turned the summer CSV into a dataframe 
Turned the winter CSV into a dataframe
Turend the dictionay CSV into a dataframe 
Merged the summer and winter dataframe togther using and outer join and named it merged_df
Renamed the County column to code so the we had somewhere to merge the dictionary data frame into 
Created the final_merged_df by mergering the dictionay df into the mereged_df and set the index to Athlete 
Filtered the data to the year 2014 to match the Population and GDP per Capita data
created a data frame for gold medals only
created a data frame for only silver medals
created a data frame for bronze medals
The we sorted the data by each country 
The counted the numder of gold medals each country had by using the groupby function
Used groupby to see the number of silver medals each country had
Used groupby to see the number of bronze medals each country had
 Created a data frame called medal_df to show the total amounts of each medal 
 #We wanted to see if countries with a higher GDP performed better than the ones that had a lower GDP. We were suprised to find that the counries with a low GDP actually out preformed the countries with a higher GDP.
 Sorted the GDP Values from least to greatest 
Sorted the silver medals from countries in alphabetical order
Sorted the Bronze medals from countries in alphabetical order
Sorted gold medal by country from greatest to least
Sorted the silver medals from countries in alphabetical order again
Sorted the bronze medals from countries in alphabetical order again
