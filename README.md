# Surfs Up!

## Project Overview
   Gather data on the seasons of Oahu and determine whether the seasons could affect the surf and ice cream shop business. Specifically, are there certain times of the year when business might be slower, or the type of customer could be different?
   
 ## Resources
  Data Source: Hawaii sqlLite
  Software: Python 3.8.3, Jupyter Notebooks
  Libraries: Pandas, SQLAlchemy, Flask
  
## Challenge Overview
  SQLAlchemy is used to access the sqlLite dB file. The two tables in the dB (measurement and station) are declared and queried against. A Flask App is also set up to facilitate real-time pings against the dB using Python. The measurement table gives data on precipitation and average temperature readings for the time period of August 2016 to August 2017.
  
  Analysis of the data for the months of December 2016 and June 2017 shows results as expected of Summer versus Winter. June was 6 degrees warmer (77 degrees) than December (71 degrees), and the coldest day during June was 11 degrees warmer (71 degrees) than December (60 degrees). On average, the month of June is much warmer than the month of December. In terms of precipitation December brought slightly higher amounts.  December saw 8 millimeters (.20 mm) more precipitation than June (.12 mm). The amount of precipitation also supports the notion that ice cream is better suited for the summer when sunshine, and warm weather are plentiful. It can also be inferred that surfing does better in the summer compared because of the warmer weather and sunshine.
  
  The analysis can be spurred by pulling in additional data points. The data on hand is weather related, but lacks any past correlation to how well ice cream or surf shops do during the analysis periods. What may be worth exploring is interfacing with Yelp to understand how often ice cream parlors and surf shops are reviewed. This could give enough information to make a baseline assumption of how busy these businesses are. What can also help is any data related to ocean swells during the analysis period. Currently there lacks a clear picture of surfing on Oahu. It would be beneficial to understand when the best surf on the island occurs when understanding variability of business and customer by season.
