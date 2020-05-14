# Flight Data Exploration
## by Md Kaish Ansari
## Dataset

> There are 7009728 rows of flights details in the data set for the year 2008, with 29 features, including cancellations and delay data for 20 unique carriers.
Data set can be found in the web site:
[Flights 2008](http://stat-computing.org/dataexpo/2009/the-data.html)
<br>For the univariate investigation, I used the data set as it is as a data frame. However, for the bivariate and for the multivariate investigation, I used an engineed data frame from the main data frame. 
The engineered data frame consisted of details of individual carriers such as, total number schedulled flights, total cancellations and total number of delays by the carriers, total delay in minutes and delay per flight operated.


## Summary of Findings

> The distribution of UniqueCarrier column is dominated by the carrier, Southwest airline with a 17.1% contribution. This seems normal as bigger airline carriers contributions are larger and small carrier contributions are smaller as expected. Over 7 million flights schedulled in 2008, 98% have been operated and 2% have been cancelled.There are four types of cancellations (Weather, Carrier, NAS and Security). Both weather and carrier cancellations are almost equal and summed up to about 80% of overall cancellations.Calulated number of cancellations per 100 flights schedulled by the carrier are compared here. American Eagle airline has the highest percentage of about 3.7% and the lowest is owned by Frontier Airline. Calulated number of delayes per 100 flights operated by the carrier are compared here. Atlantic Southwest airline has the highest percentage of about 13% and the lowest of about 3% is recorded by Aloha Airline. Calulated delay time in minutes per flight operated by the carriers are compared here. Mesa airline has the highest close to 8 min while Aloha airline has the lowest closer to 1 min. 


## Key Insights for Presentation

> The worst airline carrier in 2008 is Mesa airline. They have the highest delay time per flight and second highest in both percent cancellations and delayes. The best airline is Aloha air line and they recorded the lowest in both delay per flight and percent delayes while being the second lowest in percent cancellations.
