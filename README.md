# Surfs Up Challenge

## Overview of the Analysis
W. Avy likes your analysis, but he wants more information about temperature trends before opening the surf shop. Specifically, he wants temperature data for the months of June and December in Oahu, in order to determine if the surf and ice cream shop business is sustainable year-round.

## Results

June temperature and precipitation results are summarized: 

![June_temp](https://github.com/JaniceBgithub/surfs_up/blob/main/Resources/June_temperature.png)


December temperature and precipitation results are summarized: 

![Dec_temp](https://github.com/JaniceBgithub/surfs_up/blob/main/Resources/Dec_temp.png)

The key results are: 

- June is about 4 degrees warmer than December
- June weather is more consistent versus Decmeber with a lower temperature standard deviation
- December has more precipitation versus June 
- The weather is overall better in June for a surf shop!

## Summary and Additional Analysis

Summary: There are not huge differences in June versus December weather and weather in Hawaii seems to be generally pretty consistent throughout the year, go ahead and open the surf shop!!!

## Additional analysis
Some additional analysis were completed to see how the weather changed from year to year.

Average June temperature by year was plotted:

![June_line](https://github.com/JaniceBgithub/surfs_up/blob/main/Resources/June_temp_line_plot.png)

Average December temperature by year was plotted: 

![Dec_line](https://github.com/JaniceBgithub/surfs_up/blob/main/Resources/Dec_temp_line_plot.png)

The figures above show a general warming over the years, particularily in summer.  This trend may be short term or global warming related - more analysis is needed!

SQL Alchemy was used to join the two tables together on "station" so that additional analysis could be completed.  Pandas groupby function was used to compile information by weather station.  There were two higher altitude weather stations in the summary, these were dropped because for a surf shop, only costal temperature and precipitation is important.

![station_summary](https://github.com/JaniceBgithub/surfs_up/blob/main/Resources/station_weather.png)

For a surf shop, location is extremely important (ie waves and tourists!).  Weather and precipitation are less important, although something that could also be considered.  In general, the two warmer and less precipitation locations are Pearl City and Wakiki.
