# surfs_up

## OVERVIEW

This analysis aims to assess and identify temperature trends in Oahu, Hawaii, for the months of June and December, over a seven-year period. It was prepared in order to evaluate the sustainability of a year-round surf and ice cream shop business.


## TOOLS & QUICK LINKS

**Data:** [hawaii.sqlite](https://github.com/farwaali08/surfs_up/blob/ee9bae2f9112355ad0cb4566a198d89221fad9df/hawaii.sqlite)

**Code:** [SurfsUp_Challenge.ipynb](https://github.com/farwaali08/surfs_up/blob/ee9bae2f9112355ad0cb4566a198d89221fad9df/SurfsUp_Challenge.ipynb)

**Software**

* Python 3.9.3
  * Anaconda Navigator 2.0.3
  * Conda 4.10.3   
* Jupyter Notebook 6.3.0 

The analysis was conducted with Python, however, as the weather data provided was stored in a SQLite database, SQLalchemy was required to facilitate communication between Python and the database. The stastistical component was completed using Pandas.


## RESULTS & ANALYSIS

Below is a statistical review of the temperatures for June and December:


![alt_text](https://github.com/farwaali08/surfs_up/blob/54453a5c6d61e254945b47515b81e504b99fa61a/Temperatures.png)


Notes and Key findings:

* The lower count of December observations suggests that there is data missing for some dates
  * Regardless, the sample size is sufficient to produce insightful results
* June Temperature Range: 64°F - 85°F
* December Temperature Range: 56°F - 83°F
* The average temperatures in June and December are approximately 75°F and 71°F, respectively
   * June has a higher average temperature, which is to be expected, however the December value is comparable
* With respect to standard deviation, December data is slightly more spread out than June, however both are comparable (stdev σ ~ 3)
  * This suggests that temperatures remain around the calculated average temperature, especially in the month of June
  * This also suggests that temperatures remain fairly consistent year-round 
 
Based on temperature data alone, the conditions appear to be favourable for the business, however further analyses that incorporate other climate features, such as windiness or precipitation, are strongly recommended. Oahu has a prominent [rainy season](https://www.hawaii-guide.com/oahu/articles/oahu_weather) that lasts from mid-November through to late March, which can impact tourism, and subsequently, sales. It is recommended to conduct a similar analysis on precipitation data to indentify the trends or seasonality. A similar analysis should be conducted for wind conditions as well.

In addition to that, it is also worthwhile to use weather trends to identify an optimal location for the business. This can be achieved by analyzing each weather station to determine which location generally has more stable weather patterns. 

