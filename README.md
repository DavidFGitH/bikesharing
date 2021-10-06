# bikesharing
Bikesharing with Tableau

## Overview of Project

To use the bikesharing data from Citibike to create multiple visualizations using Tableau

### Purpose

In order to understand the viability and market for starting a bikesharing business, we have to analyze data taken from Citibike of users in August and visualize in a way that is clear and appealing to investors

## Results

[TableauStory](https://public.tableau.com/app/profile/david.f2211/viz/Bike-SharingAnalysis/Bike-SharingAnalysis)

![PieChart](https://github.com/DavidFGitH/bikesharing/blob/main/Resources/S1Pie.png)

To begin, we can do a general look at a pie chart of the percentage of instances of bikesharing were used by a specific gender. Clearly, a majority people using the bikesharing service are male, and even if the unknown section consists of all female riders, males riders still outnumber them by a sizable portion.

![BarHour](https://github.com/DavidFGitH/bikesharing/blob/main/Resources/S2CountHour.png)

In this chart, we have the hours in which the use of a bikesharing service was logged, and how often they were logged at that hour. The times that show the least activity range from about 1AM to 5AM, which makes sense since most people are clearly sleeping during that period. Afterwards, the number of riders increase before peaking at about 8AM, corresponding to the start of the workday, before dipping and rising again to the peak of the bar graph at 5PM, which is the end of most workdays. The interesting part is to explain why the peak at 5PM is greater than the peak at 8AM, but we can only speculate assuming that people take public transportation to work, they use the bikesharing service to do other things before going home

![TripDuration](https://github.com/DavidFGitH/bikesharing/blob/main/Resources/S3CheckoutDur.png)

On this line chart we can see the duration of time riders used their bikesharing service plotted across the number of instances for that length of time. From this chart we can conclude that a majority of users only used the bikesharing service for about 5 minutes, before seeing a large dropoff in the number of users using the bikesharing service for any longer period. This is interesting because 5 minutes is not necessarily that significant amount of time, suggesting that perhaps having stations in closer proximity is preferable to riders to just bike to where they need to and get off.

![GendTripDuration](https://github.com/DavidFGitH/bikesharing/blob/main/Resources/S4GendCheckoutDur.png)

This line chart follows the same parameters as the previous except it also separates the counts by gender as well. Looking at this graph, we know from earlier the number of female users are fewer than the male ones, but it seems that they follow similar trends in terms of length of rides. While the male riders peak at around 5 minutes of usages, the female riders peak at around 6 minutes, not much more. Other than that we can see that the unknown riders rises more gradually up to 11 minutes of usage before gradually decreasing at lengthier ride usage before dropping dramatically at around 26-28 minutes.

![HeatmapWeek](https://github.com/DavidFGitH/bikesharing/blob/main/Resources/S5HeatWeek.png)

This is a heat map of the rides logged at specific days of the week and the times that they are logged. Using the scale shown in the legend, we can clearly see one of our previous conclusions from the bar chart earlier of a peak at 8AM and 5PM mostly true during the weekdays, but on weekends the number of users is more evenly distributed between 8AM and 5PM. There are lots of interesting observations to be made from the heatmap, such as the numbers of users on Wednesday afternoon are significantly less compared to other weekdays, the peaks of users on weekends are closer to 12PM, there are more users before 5PM on Friday compared to other days.

![GendHeatmapWeek](https://github.com/DavidFGitH/bikesharing/blob/main/Resources/S6GendHeatWeek.png)

This is a heat map following the same parameters of the previous heatmap, just isolated by gender. Generally, the trends shown from the previous heatmap holds true for both male and female users, with both having similar peaks and usage across the days of the week. Other than that, there are people more likely to report as unknown on weekends compared to other days.

![SubscriberHeatmapWeek](https://github.com/DavidFGitH/bikesharing/blob/main/Resources/S7SubHeat.png)

In this last visualization, we have a heat map of riders divided by both gender and whether they are a subscriber or not, then counting across the days of the week. By far the largest group are male subscribers, followed by female subscribers, afterwards being more of wash between non-subscribers with the smallest group being unknown subscribers. Another observation to made is that the peak usage for subscribers on Thursdays, with male and female riders having similar distributions while non subscribers tend to peak around weekends. Also, it seems that subscribers are more willing to use their bikes on weekdays as opposed to weekends.

## Summary

Overall, there are several things that a clear looking at analysis of the data. Clearly a majority of users of the bikesharing service are male subscribers, who using bikesharing most likely to commute to and from work. This is reinforced by the data showing that the most popular times to use the bikesharing service are around 8AM and 5PM. A majority of users also don't use their bikesharing service for long, with a majority riding their bikes around 5-6 minutes. Male and female bikesharing also follow similar trends across the board, with minor variations within margin or error. From these conclusions, we have to a few avenues that still require more investigation. The population density for New York is obviously different compared to Des Moines, which is important considering a majority of riders only have 5-6 minute trips. Creating a visualization to determine the length of travel distribution would help to see how far most people are willing to use the bikesharing service before considering other means of travel. Another avenue we explore would be the age of the riders, since demographics could play a large role in determining the viability of the bike sharing service. We could see the distribution of riders based on age, and the average length of time for riders of specific ages.
