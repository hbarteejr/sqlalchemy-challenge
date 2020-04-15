# sqlalchemy-challenge

# SQLAlchemy Homework - Surfs Up!

In this SQLAlchemy Homework-Surfs Up homework assignment, I created a new repository called `sqlalchemy-challenge. Next, I cloned the new repository to my computer.  Next I added a Jupyter notebook and `app.py` to this folder, which include the main scripts to run for analysis. The changes that I made were finally pushed to GitHub along with the csv files, images and other resources provided with this assignment.  

In this project, a decision has been made to go on a long holiday vacation in Honolulu, Hawaii! To help with the trip planning, some climate analysis was provided through climate analysis and exploration.  

Some of the tools used were Python and SQLAlchemy to do basic climate analysis and data exploration of the climate database through SQLAlchemy ORM queries, Pandas, and Matplotlib.

### Precipitation Analysis
* Design a query to retrieve the last 12 months of precipitation data.
* Select only the `date` and `prcp` values.
* Load the query results into a Pandas DataFrame and set the index to the date column.
* Sort the DataFrame values by `date`.
* Use Pandas to print the summary statistics for the precipitation data.

### Station Analysis
* Design a query to calculate the total number of stations.
* Design a query to find the most active stations.
* List the stations and observation counts in descending order.
* Which station has the highest number of observations?
* Design a query to retrieve the last 12 months of temperature observation data (TOBS).
* Filter by the station with the highest number of observations.
* Plot the results as a histogram with `bins=12`

An attempt was made to complete Step 2 - Climate App by designing a Flask API based on the queries that were developed.

### Routes
* `/`
* Home page.
* List all routes that are available.
* `/api/v1.0/precipitation`
* Convert the query results to a dictionary using `date` as the key and `prcp` as the value.
* Return the JSON representation of your dictionary.
* `/api/v1.0/stations`
* Return a JSON list of stations from the dataset.
* `/api/v1.0/tobs`
* Query the dates and temperature observations of the most active station for the last year of data.
* Return a JSON list of temperature observations (TOBS) for the previous year.
* `api/v1.0/<start>` and `/api/v1.0/<start>/<end>`
* Return a JSON list of the minimum temperature, the average temperature, and the max temperature for a given start or start-end range.
* When given the start only, calculate `TMIN`, `TAVG`, and `TMAX` for all dates greater than and equal to the start date.
* When given the start and the end date, calculate the `TMIN`, `TAVG`, and `TMAX` for dates between the start and end date inclusive.
- - -

An additoinal attempt was made to do one of the bonus activities in this project.  

