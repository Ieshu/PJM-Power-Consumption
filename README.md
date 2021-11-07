# PJM-Power-Consumption

PJM Interconnection LLC (PJM) is a regional transmission organization (RTO) in the United States. It is part of the Eastern Interconnection grid operating an electric transmission system serving all or parts of Delaware, Illinois, Indiana, Kentucky, Maryland, Michigan, New Jersey, North Carolina, Ohio, Pennsylvania, Tennessee, Virginia, West Virginia, and the District of Columbia.

The hourly power consumption data comes from PJM's website and are in megawatts (MW).

The regions have changed over the years so data may only appear for certain dates per region.

Given the rise of smart electricity meters and the wide adoption of electricity generation technology like solar panels, there is a wealth of electricity usage data available.

In this we have 10 Interconnection RTO datasets which contains the hourly energy consumed by people 

1. AEP
2. COMED
3. DAYTON
4. DEOK
5. DOM
6. DUQ
7. EKPC
8. FE
9. NI
10. PJME
11. PJMW
12. PJM_Load
13. est
14. pjm

Ideas of what to do with this dataset:

> Perform univariate,bivariate and multivariate analysis on this data to check 3 hypothesis-

 (a) Does seasons with higher or lower temperatures use more energy ?
 
 (b) Does holiday periods spend more energy ?
 
 (c) Does we spend more energy in Weekends ?
 
> Split the last year into a test set- to build a model to predict energy consumption

> Find trends in energy consumption around hours of the day, holidays, or long term trends

> Understand how daily trends change depending of the time of year. Summer trends are very different than winter trends.

> Performed time series analysis using 3 variants of LSTM models namely Vanilla LSTM, STACKED LSTM & BI-DIRECTIOANL LSTM to predict the time series dataset.

> Used SARIMAX model alongwith teh otehr models to forecast data in the future.
