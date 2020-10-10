# sqlalchemy-challenge

#### I've decided to treat yourself to a long holiday vacation in Honolulu, Hawaii! To help with my trip planning, I needed to do some climate analysis on the area. Please see below for my findings as well as an app I created to help others with theirs. 

## Climate Analysis and Exploration

### Precipitation Analysis

####From the summary stats and the plot below on precipitation we see that Hawaii did not have a lot of rain the previous year.

![Image of PRCP](https://github.com/giovannahayes/sql-challenge/blob/main/EmployeeSQL/QuickDBD-export%20GOH.png)

![Image of STAT](https://github.com/giovannahayes/sql-challenge/blob/main/EmployeeSQL/QuickDBD-export%20GOH.png)

### Station Analysis

#### A total of nine stations were identified in the database query. Their total combined observation count was close to 20,000 observations but their most active station, USC00519281, accounted for 15% of those observations. The average temperature for the previous year at this station was approximately 77 F. 

## Climate App

#### After completing my initial analysis, I designed a Flask API based on the queries developed above. The routes are listed below. 

* /
    * Home Page
    * Listed Routes Available
* /api/v1.0/precipitation
* /api/v1.0/stations
* /api/v1.0/tobs
* /api/v1.0/<start> and /api/v1.0/<start>/<end>

#### Please reference app.py for the code written to build the API app
