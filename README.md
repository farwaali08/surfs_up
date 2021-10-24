# surfs_up

## OVERVIEW

This analysis aims to assess and identify temperature trends in Oahu, Hawaii, for the months of June and December, over a seven-year period. It was prepared in order to evaluate the sustainability of a year-round surf and ice cream shop business.

The analysis was conducted with Python, however, as the weather data provided was stored in a SQLite database, SQLalchemy was required to facilitate communication between Python and the database. The stastistical component was completed using Pandas.

## TOOLS & QUICK LINKS

**Data:** [hawaii.sqlite](https://github.com/farwaali08/surfs_up/blob/ee9bae2f9112355ad0cb4566a198d89221fad9df/hawaii.sqlite)

**Code:** [SurfsUp_Challenge.ipynb](https://github.com/farwaali08/surfs_up/blob/ee9bae2f9112355ad0cb4566a198d89221fad9df/SurfsUp_Challenge.ipynb)

**Software**

* Python 3.9.3
  * Anaconda Navigator 2.0.3
  * Conda 4.10.3   
* Jupyter Notebook 6.3.0 

## RESULTS & ANALYSIS

Below is a statistical review of the temperatures for June and December:


![alt_text](https://github.com/farwaali08/surfs_up/blob/54453a5c6d61e254945b47515b81e504b99fa61a/Temperatures.png)


Notes and Key findings:

* The lower count of December observations suggests that there is data missing for some dates
  * Regardless, the sample size is sufficient to produce insightful results
  
* The average temperatures in June and December are approximately 75°F and 71°F, respectively
  *  

* With respect to standard deviation, December data is slightly more spread out than June, however both are fairly comparable (stdev σ ~ 3)
  * This suggests that temperatures remain around the calculated average temperature, particularly in the month of June  
