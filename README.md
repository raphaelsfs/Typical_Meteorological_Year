# Typical_Meteorological_Year

I developed this code to read a considerable amount of ".csv" files containing time series with meteorological data in different locations within the Mediterranean Sea, concatenate these files, clean the data and use some methods already existed to evaluate the mean behaviour of the wind and the solar energy in the specified location.

Each file contain as data, hourly measurements of different meteorological parameters, considering all the months from the year 2000 to the year 2015.

In summary the code is able to compare, for instance, the behaviour of all the values for the month of January throughout all the years with the values of January for each year, which means that the output will be the January that has the most similar values to the average values obtained from all months of January. This will be done for each different month and in the end we will obtain the year that closely represents all 15 years, therefore the Typical Meteorological Year.