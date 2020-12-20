# From New York to Des Moines: Lessons from a Bikeshare.

[link to bikeshare](https://public.tableau.com/profile/andrej.arsovski#!/vizhome/Bikeshare_challenge/AnalysisofNewYorkCitysCITIBIKEProgram)

## Overview
The purpose of this analysis was to examine in depth New York City's CITIBIKE program in preparation for preparing a similar project for Des Moines, Iowa. A number of parameters were examined such as the customer and composition of ridership, the trip breakdown by hour of day and day of week. A number of important considerations have emerged when considering launching a new bike share program.

## Results

While New York and Des Moines are very different cities a scaled-down bikeshare program could be succesful if the following findings are considered carefully.

### 1. Ridership is highest among 30 year olds.
There appears to be an initial inverse correlation between rider age and number of trips followed by a decrease as rider age drops below 30 years old. The number of trips increase as the rider age decreases with only 423 trips taken by riders born in 1940 and 1,375 by riders born in 1945. Rides increase as age decreases with riders born in 1990 had the highest number of rides with  102,926. There is then a decrease as the birth year increases. There is an unusual spike at bith year year 1969, which means 237,533 riders think themselves hilarious. The age structure of Des Moine's population needs to be considered for this program to be successful there.

![age.png](https://github.com/andrej-arsovski/bikeshare_m14/blob/main/tableau_screenshots/age.png)

### 2. Riders are mostly male. 
The large majority of users are male. 1,530,272 users identified as male, 588,431 as female, and 225,521 are unknown. Thus far the data suggests that the target population for the Des Moines program should be males in their 30's.

![gender.png](https://github.com/andrej-arsovski/bikeshare_m14/blob/main/tableau_screenshots/gender.png)

### 3. Rides are extremely long.
The most common trip duration in New York is approximately 5 hours. Hopefully Des Moines has enough bikable streets, or streets to support hours long bike rides. 

![duration.png](https://github.com/andrej-arsovski/bikeshare_m14/blob/main/tableau_screenshots/duration.png)

### 4. Trip duration patterns are similar between genders.
Trip duration by gender suggests that those identifying as male take longer bike trips then those identifying as female or unknown. 5 hour bike rides are again most popular amongs males and females while those identifying as 'unknown' seem to ha e a flatter trip duration curve.

![duration_by_gender.png](https://github.com/andrej-arsovski/bikeshare_m14/blob/main/tableau_screenshots/duration_gender.png)

### 5. Bikes for commuting on weekdays, leisure on weekends
Trips appear to cluster around two major time points during the weekday in New York City. The first peak is at 8am followed by a second peak at 5 and 6 pm. This strongly suggests that the bikes are primarily used for work or school commute. During the weekend bike usage increases uniformly with heavier use between the hours of 11am and 5pm, suggesting leisure use. This is important to consider for Des Moines. Ideally, there as in New York there is a large population that lives in the downtown core or resides a bikeable distance from work or school. The urban plan of Des Moines must be considered if a bike share program can succeed. 

![usage_by_day.png](https://github.com/andrej-arsovski/bikeshare_m14/blob/main/tableau_screenshots/usage_by_day.png)

### 6. Gender patterns similar on weekdays and weekends
Examining the usage by day and gender follows the same pattern. Males use the bikes more then females but both use the bikes most around 8am and 5-6pm on weekdays. Saturday and Sunday use increases in the afternoon hours suggesting leisure usage. This is similar regardles of the gender of the user.

![usage_by_day_gender.png](https://github.com/andrej-arsovski/bikeshare_m14/blob/main/tableau_screenshots/usage_by_day_gender.png)

### 7. Subscribers are a must.
Finally, the majority of users are subscribers among those identifying as male and female. Except for those identifying as 'unknown' this is not surprising as those non subscribers are probably more likely noot to bother providing correct information. A successful program in a different city must be able to secure a strong base of subscibers.

![subscribers.png](https://github.com/andrej-arsovski/bikeshare_m14/blob/main/tableau_screenshots/customer_type.png)

## Summary

For the bike share program to be successfully implemented in Des Moines it must be able to support a largely commuting use pool. For this the urban plan of Des Moines must be closely studied. Does Des Moines have a large enough population that lives within a bikeable distance from work? from School? Does a large enough portion of the population live in the downtown core for example or is it more of a suburban sprawl. 

Another important consideration is whether there is infrasctructure in Des Moines to sustain the amount of biking required to make this kind of program a success. Are there dedicated bike lanes, greenways, and tourist attractions to sustain a weekend and leisure use. 

### Additional Analyses

1. Who is driving the usage? It would be very useful to see whether usage is spread evenly amongst subscribers or is it a small group of heavy users that are responsible for the majority of rides.

2. Rides by month. It would be important to know what time of year the bikes are used the most in order to correlate to the climate in Des Moines. If usage is down in colder months this could be a time for repairs and infrastructure repairs.
