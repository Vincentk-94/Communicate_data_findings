# Flights on Time
## by Vincent Khor

The main objective of this project is to analyse various variables by univariate, bivariate and then multivariate analysis to determine whether there are certain factors or trends that could affect whether a flight is more likely to be cancelled, delayed or diverted. 

A slide deck was then created to follow some of the key insights. 

## Dataset

- This dataset comes from the Bureau of Transportation Statistics: https://www.transtats.bts.gov/OT_Delay/OT_DelayCause1.asp 
- The dataset can be downloaded at: https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/HG7NV7

It contains data about flights from USA between January - April 2008. On-time performance of domestic flights by large carriers are included. Information includes the number of on-time, delayed, cancelled and diverted flights.

Provide basic information about your dataset in this section. If you selected your own dataset, make sure you note the source of your data and summarize any data wrangling steps that you performed before you started your exploration.

## Files included
- **2008 Flight Delays - Project** - Report containing exploratory data analysis.
- **2008_Flight_delays_Slide_Deck** - Presentation containing expanatory data analysis.
- **variable_descriptions.csv** - csv containing variable descriptions.
- **airports.csv** - csv containing basic information about airports in USA.
- **carriers.csv** - csv containing basic information about carriers in USA.
- **plane-data.csv** - csv containing basic information about planes by tail number.

## Summary of Findings

- 2.7% of flights are cancelled, 41.6% of flights are delayed, very few are diverted.
- Carrier and weather are the main reasonings for cancellations.
- Most flights depart on time but most arrive early.
- Wednesdays have the most flights whilst Saturdays are the quietest, February has the fewest flights as expected.
- Most flights are 500-1000 miles and take 100mins. 
- Carrier WN has the most flights, almost twice the amount of the second highest (AA), HA and AQ have the fewest.
- Tuesday and Fridays have the highest proportion of cancelled flights.
- All carriers do short distance flights but some do medium and long distance flights too.
- Most carriers depart on time, but some carriers are able to arrive early on average.
- There is a large variation in the proportion of cancellations/delays depending on the carrier.
- Most flights are able to make up time during the flight to reduce lateness.
- North of USA has the highest proportion of cancellations, diversion rates were higher at more isolated airports.
- The order for most impacting to least impacting delay is: Weather > Late aircraft > Carrier > NAS > Security.
- April has the lowest proportion of cancelled flights whilst February has the most. 
- Due to the low number of diversions, there are no obvious trends when comparing days of the week or month with diversion rates.
- The carrier does significantly affect the proportion of delay. WN can have over 65% of their flights delayed whilst HA and AQ have the least. 
- Fridays have the most delays and the days with the lowest amount of delays are Tuesdays and Wednesdays.
- Carriers F9, HA and AQ are the most punctual, OH prefers departing at 5 minute intervals.

## Key Insights for Presentation

- The main reason for cancellations are carrier and weather. Cancellations due to NAS are half as likely whilst security cancellations are extremely rare.
- 58.4% do depart on time but 41.6% are delayed.
- Carriers WN and CO have the highest proportion of delays whilst AQ and HA have the lowest.
- Most flights depart on time but most flights arrive early, this suggests that flights can makeup time during the flight.
- Weather delays create the longest delays followed by late aircraft and carrier. The least impactful delays are NAS and security.
