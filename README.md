# surfs_up

## Overview
This project was to help start an ice cream and surf shop in Hawaii. In order to do that, we used SQLite to query the provided data and isolate the temperatures for June and December. These two querys give an idea of tempertures 6 months apart, one set in the summer and one set in the winter. 

## Resources
- Data sources: hawaii.sqlite
- Software: Python 3.6.1, jupyter notebook

## Results
Examining the base statistics for both June and December, there is one major conclusion to come to. It is generally warm there all year round. It can be a bit chilly with both June and December, with December dipping down into the mid 50s and June into the mid 60s. They both have high temperatures in the 80s, and both have an average temperature in the 70s. This seems like ideal weather for ice cream and surfing.

### June and December Temperature Statistics 
![alt text](December Temps.png)

### Considerations
Temperature data often includes 24 hour data collection. I would suggest getting data specific to the hours of operation, it likely is colder at 2am but the shop is unlikely to be open at that time. This will likely give a different set of statistics. It is also probably worth looking into weather patterns and whether or not there is a monsoon season there, if there is, the temperatures might be lower at that time. 
