# SQlalchemy-challenge

Summary: Congratulations! You've decided to treat yourself to a holiday vacation in Honolulu, Hawaii! To help with your trip planning, you need to do some climate analysis on the area. The following outlines what you need to do.

Use the SQLAlchemy to be able to reflect existing databases in Python

Use the queries to retrieve the last 12 months of precipitation data and plotting them over time using a pandas DataFrame

Start designing queries to obtain the number total of the stations, such as the most active stations, 12 months of temperature observation data 

Then you will need to create a Flask API app to be able to create routes that retrieve from the JSON data such as precipitation values by date, stations, temperature observations from the last year, and min, max, and average temperatures within a specified date range.




Bonus: Other Recommended Analyses

The following are optional challenge queries.


Temperature Analysis I


Hawaii is reputed to enjoy mild weather all year. Is there a meaningful difference between the temperature in, for example, June and December?


You may either use SQLAlchemy or pandas's read_csv() to perform this portion.


Identify the average temperature in June at all stations across all available years in the dataset. Do the same for December temperature.


Use the t-test to determine whether the difference in the means, if any, is statistically significant. Will you use a paired t-test, or an unpaired t-test? Why?



Temperature Analysis II


The starter notebook contains a function called calc_temps that will accept a start date and end date in the format %Y-%m-%d. The function will return the minimum, average, and maximum temperatures for that range of dates.


Use the calc_temps function to calculate the min, avg, and max temperatures for your trip using the matching dates from the previous year (i.e., use "2017-01-01" if your trip start date was "2018-01-01").


Plot the min, avg, and max temperature from your previous query as a bar chart.


Use the average temperature as the bar height.


Use the peak-to-peak (TMAX-TMIN) value as the y error bar (YERR).






