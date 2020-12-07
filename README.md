# Surfs Up(Let's sell some Ice Cream)
## Overview of Analysis

W. Avy temperature data for the months of June and December in Oahu, in order to determine if the surf and ice cream shop business is sustainable year-round.

## Results of the Temperature Analysis

I queried the temperature data for June and December from the SQLite file provided by W. Avy. I completed a simple statistical analysis for each month. The results are below.

* The average tempreatures only vary by about 4 degress.
* December has a -8 lower min temp and a -2 max temp. These are only marginally lower than June min and max temp.
* June has a larger sample size. The more extensive data set will allow us to make better predictions of future June temperatures.

![June Temp Data](https://github.com/skanab/surfs_up/blob/main/June_Temps.PNG?raw=true)

![December Temp Data](https://github.com/skanab/surfs_up/blob/main/December_Temps.PNG?raw=true)


## Summary

The temperature analysis results show that people will eat ice cream in June and December without any problem as the temperature varies very little between the two months. W. Avy seems to be assuming that people will eat more ice cream when it's warmer. This data set does not provide the data we need to validate that. There are many good reasons to eat ice cream during all months of the year. The most obvious reason being that ice cream melts slower in lower temperatures. 

## Two additional data points that I reviewed

### Average temperature by year and station

I wanted to see if the temperature varied by year or station. Temperature data differed very little for June and December by station or year.


![June Temp Data By Station](https://github.com/skanab/surfs_up/blob/main/June_Temps_Station.PNG?raw=true)

![December Temp Data By Station](https://github.com/skanab/surfs_up/blob/main/December_Temps_Station.PNG?raw=true)

### Average precipitation by year and station

When reviewing the precipitation data, I found that year and station data did have some variances worth exploring more. Some stations have meager yearly rainfall totals across all years. Locating the surf shop near these stations may lead to more traffic due to the favorable conditions.

![June Rainfall Data By Station](https://github.com/skanab/surfs_up/blob/main/June_Rainfall_Station.PNG?raw=true)

![December Rainfall Data By Station](https://github.com/skanab/surfs_up/blob/main/December_Rainfall_Station.PNG?raw=true)

