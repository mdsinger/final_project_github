# Final_project_github

ROUGH DRAFT

HYPOTHESIS 
- Utilizing machine learning and ETL create a predictive model create and illustrate using Tableau to forecast the probability of flooding from abrupt snowpack disinegration. Areas of focus; are cities within Salt Lake, Utah and Davis Counties. 

TECHNOLOGIES 
- Jupiter Notebook.
- Excel
- Machine Learning
- Tableau https://public.tableau.com/app/discover to Edit USERNAME shoessold0411@outlook.com PASSWORD Capita11Nas!

ETL

EXTRACT the data parameters below for folllowing dates and locations PAST 01/01/1983 - 05/31/1983 | 01/01/2011 - 05/31/2011 | MEDIAN 01/01/1991 - 05/31/2020 | CURRENT/FUTURES 04/01/2023 - 05/31/2023. 4 types timeframes PAST, MEDIAN, CURRENT/FUTURES each coincedies with an timeset above. 

NOTE: if these locations do not suffice, send me NOAA's weather stations for Utah.
DATA LOCATION Extraction are as follows, using USDA. Salt Lake County (Snowbird (84092), Thayne Canyon (84060), Mill-D  North (84121)) | Utah County (Cascade Mountain (84604), Timpanogos Divide (84003), Hobble Creek (84663)) | Davis County (Farmington (84025), Farmington Lower (84037), Parrish Creek (84014)). 
 


- Snowfall: PAST, MEDIAN, CURRENT/FUTURES. (Melissa)
- Snowpack levels: PAST, MEDIAN, CURRENT/FUTURES. (Melissa)
- Snow/Water equivilent: PAST, MEDIAN, CURRENT/FUTURES. (Thomas)
- Resevoir capcity: PAST, MEDIAN, CURRENT/FUTURES. (Thomas)
- Stream cubic volume: PAST, MEDIAN, CURRENT/FUTURES. (Thomas)
- River cubic volume: PAST, MEDIAN, CURRENT/FUTURES. (Thomas)
- Soil Moisture, CURRENT (Thomas)
- Precipation: : PAST, CURRENT/FUTURES.  (Melissa)
- Temperature: PAST, MEDIAN, CURRENT/FUTURES. (Melissa)
- Population, numbers/growth. : PAST, MEDIAN, CURRENT/FUTURES. (Jane Tableau)

TRANSFROM 

- First step aggregate the data then merge the data into 9 or 10 columns. Assign by date, check and elminate duplicates and nulls. 

- Second clean the data find the correlation.

- Third the outcome, logistical regression. 

Clean
The data exhibits and extrapolates the plausibility of flooding in zip codes/real estate developments of high risk.  

MACHINE LEARNING 

- Try K-Clustering don’t forget to write yourself a legend and colors. 
- Easy ensemble classifier. 
- Utlize keras try them all!

KEY SITES FOR TRANSFROMING AND CLEANING THE DATA.


https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.corrwith.html

https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.corr.html

https://github.com/EnzoZirotti/Wildfire-Prediction-Website

https://keras.io/guides/keras_tuner/getting_started/ Module 19
 

Weather Stations USDA
https://wcc.sc.egov.usda.gov/reportGenerator/view/customMultipleStationReport/daily/state=%22UT%22%20AND%20network=%22SNTLT%22,%22SNTL%22%20AND%20element=%22SNWD%22%20AND%20outServiceDate=%222100-01-01%22%7cname/0,0/name,stationId,WTEQ::value,WTEQ::delta,SNWD::value,SNWD::delta?fitToScreen=false



5 TAKEAWAYS/STORYBOARD ILUUSTRATIONS WE NEED TO ARTICULATE FROM ETL AND MACHINE LEARNING.  

We decided to to do this study basedd on the snowfall/snowpack. Based off the record snowfall and snowpack will what flood? 

Are the Resviors full? What are the stream cubic volume currently? What cities and counties are in line with a particular swelling in population to stream flow.

Temperature ? 

Precipatation ? 

Utah County and Salt Lake County Weather Station. 


Tableau Storyboard 

Heres what happened in 1983, 2011, and 2023. 

Bar charts, heat maps for population, area's, 









 











