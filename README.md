Project Description:

Our project aims to uncover the patterns in mortality rate in the United States due to cardiovascular diseases; trends in mortality rate across time (from 1980 to 2014) and across geography (county and state). We also intend to check, through advanced statistical methods, the kind of correlation factors like obesity and higher education have on cardiovascular mortality rate.
Mortality Rate is defined as deaths per 100,000 people as published at Global Health Data Exchange (http://ghdx.healthdata.org/record/ihme-data/united-states-mortality-rates-county-1980-2014) 

Scope: 

After exploring multiple options (e.g. effects of mobile usage on children, spread of diabetes in USA), we finalized on exploring cardiovascular mortality data across United States. We intended to do both a time-series analysis and a location analysis of cardiovascular deaths. Additionally, we wanted to explore a few factors like obesity, education, poverty, homelessness. 
Once we decided the scope, we wanted to ask the following questions:
•	How does mortality rate vary across US geographies (state and county)
•	How does cardiovascular mortality rate vary across time (1980 – 2014)
•	How do factors like Obesity and Higher Education level affect cardiovascular mortality rate
Identify Data Sources

Global Health Data Exchange provided the cardiovascular mortality data, annually and quinquennially, at county, state and national level.
Stateofobesity.org provided the obesity data, while the US Department of Agriculture Economic Research Wing provided the data for the education dataset

Data Cleansing:

The initial dataset had data at state and county level. However the yearly data was spread in columns and had to be converted into a row level data. 
The jupyter notebook DataCleansing.ipynb details the steps taken to cleanse the data. The raw files can be obtained in the Data folder

Analysis:

We created choropleth maps to showcase cardiovascular mortality in counties and states across the years. The jupyter notebook Analysis.ipynb showcases the technique to draw the maps. Since these maps can't be saved using savefig(), they need to be called separately through a user input denoting the year that the user wants to see the data for.

We also applied correlation for finding relationships between Obesity and Education. These can be found in the jupyter notebook Analysis2.ipynb
Next, we did a prediction model using linear regression for 3 states - CA (state of residence), MI, the state with highest mortality rate, while MN the one with the lowest mortality rate. These can be found in the jupyter notebook Analysis3.ipynb 

Finally we put together the presentation with our findings. Link to the presentation is :

https://drive.google.com/file/d/1Hdb026O3rqES0kVlHB-2JOpLRCBZIH6T/view?usp=sharing

