# Surf's Up Challenge
## Overview
An analysis on the weather in Oahu was performed to determine if opening a surf and ice cream shop would be a lucrative business plan for W. Avy to invest in. This analysis specifically looks at trends in temperature data in the months of June and December in Oahu. to determine if the surf and ice cream shop business is sustainable year-round.

## Results
### December Summary Statistics
<img width="131" alt="Surfs_up_Dec_Summary-Stats" src="https://user-images.githubusercontent.com/69849998/116815284-c9f22d80-ab2a-11eb-9aa6-85b247b95044.png">

### January Summary Statistics
<img width="132" alt="Surfs_up_Jan_Summary-Stats" src="https://user-images.githubusercontent.com/69849998/116815287-cd85b480-ab2a-11eb-91df-69a827a52a8d.png">

Using the .describe function in Pandas provides the summary statistics shown in the screenshots above for each month. 
* January has a slightly higher average temperature of 74 degrees farenheit (23 celsius), compared to 71 degrees farenheit (21 celsius).
* The minimum temperature is lower in December at 56 degrees farenheit (13 celsius), compared to 64 degrees farenheit (17 celsius).
* The maximum temperature is slightly higher in January at 85 degrees farenheit (29 celsius), compared to 83 degrees farenheit (28 celsius).

## Summary
While there are suble differences between the temperature in the months of December and January, the temperatures is relatively similar than both months. It would be helpful to see which months of the year are the hottest and coldest, as it is likely that the surf/ice cream shop will see higher sales during the warmer months. This could be done by sorting the temperature data by month, and developing a histogram using the pandas df.plot() with the month along the x-axis and the temperature along the y-axis. Similarly, it would be helpful to do the same and develop a histogram that plots the precipitation by month. 
