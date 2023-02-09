# Movies-ETL-

## Overview 

The purpose of this code was to create an automated data pipeline that takes in new data, performs the appropriate transformations, and loads the data into existing tables. The data selected for this was movie data from wikipedia. Data included categories of each movie including (genre, director, release data, revenue, run time, languages, and popularity) The end goal was to clean the data to only the information that was desired and load into Postgres database

![This is an image](https://github.com/BrandonCodes95/Movies-ETL-/blob/120a29747ef28b09951f160a9adc13212bf39e3e/Raw%20data%20image.PNG)


### Cleaning Data 

Creating functions and using processes such as list comprehensions, lambda functions, and regular expression within Jupyter Notebooks I was able to clean the data sets imported from Wikipedia.
Cleaning the data included formatting it to the preferred form, seperating data for better analysis, and writing code that could be reused on larger or smaller datasets. 

![This is an image](https://github.com/BrandonCodes95/Movies-ETL-/blob/120a29747ef28b09951f160a9adc13212bf39e3e/Images/Cleaned%20Data%20function.PNG)

![This is an image](https://github.com/BrandonCodes95/Movies-ETL-/blob/28dab9751816b62126762a86f765edcd46c1c481/Images/Function%20example%20Image.PNG)

![This is an image](https://github.com/BrandonCodes95/Movies-ETL-/blob/28dab9751816b62126762a86f765edcd46c1c481/Images/Lamda%20example%20image.PNG)


### Uploading to PGAdmin 
Finally the data was cleaned and exported from jupyternotebook into two seperate tables within Postgres for data warehousing to be used for any further analysis. 

One table for ratings data and one table for movie descriptive data.

![This is an image](https://github.com/BrandonCodes95/Movies-ETL-/blob/ec5f97e274e609185d54c4c6cde1d5f35653be70/Images/Exporting%20image.PNG)

![This is an image](https://github.com/BrandonCodes95/Movies-ETL-/blob/ec5f97e274e609185d54c4c6cde1d5f35653be70/movies_query.png)

![This is an image](https://github.com/BrandonCodes95/Movies-ETL-/blob/ec5f97e274e609185d54c4c6cde1d5f35653be70/ratings_query.png)
