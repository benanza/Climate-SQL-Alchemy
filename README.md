# Climate-SQL-Alchemy

### Project Premise: I've decided to treat myself to a long holiday vacation in Honolulu, Hawaii. To help with my trip planning, I need to do some climate analysis on the area.

- Use SQLAlchemy create_engine to connect to sqlite database

- Reflect tables into classes and save a reference to those classes called Station and Measurement


#### Precipitation Analysis

1. Design a query to retrieve the last 12 months of precipitation data and load the query results into a Pandas DataFrame.

2. Use Pandas to print the summary statistics for the precipitation data.

#### Station Analysis

1. Design a query to calculate the total number of stations.

2. Design a query to find the most active stations.

3. List the stations and observation counts in descending order.

4. Design a query to retrieve the last 12 months of temperature observation data (TOBS).

5. Filter by the station with the highest number of observations.

6. Plot the results as a histogram.

#### Flask App Creation

1. Create routes

2. Convert the query results to a dictionary and return the JSON representation of it

3. Query the dates and temperature observations of the most active station for the last year of data.

4. Return a JSON list of temperature observations (TOBS) for the previous year.

5. Return a JSON list of the minimum temperature, the average temperature, and the max temperature for a given start or start-end range.

6. Calculate TMIN, TAVG, and TMAX for all dates greater than and equal to the start date.

7. Calculate the TMIN, TAVG, and TMAX for dates between the start and end date inclusive.
