---
layout: post
title: Project Benson Analysis
---

Recently, we did an analysis for WTWY, a non-profit organization focused on improving the involvement of women in the tech sector, to determine which subway stations would be the best to conduct outreach at to provide free tickets for a gala in support of their organization in the early summer and to spread information about their organization.

In order to determine where the best locations to conduct the outreach would be, we first had to ask the question, who would be the individuals that would be the most passionate about the causes that WTWY stood for. The group that we believed would be the most passionate about increasing the numbers of women in tech were women in the tech sector.

To target these individuals, we compiled two sets of data, one with the largest tech companies in the City of New York including their addresses and the number of employees, and another with the number of females working in computer occupations in the City by ZIP Code. For the number of employees, once the number of employees at these companies was grouped by ZIP Code, the employee numbers was reduced to 27.2% of their value, assuming that this was the percentage of employees at each company that were female (since 27.2% of workers in the tech sector were female). We then found the ZIP Codes with the highest combined numbers of these groups and targeted our outreach to the top 8 ZIP Codes.

We then found the subway stations that were located in each of these 8 ZIP Codes, and then using MTA entry and exit data from three months between late April and early July, to include the top 20 stations. We then joined the data of the top 20 stations and the stations in the top 8 ZIP Codes in order to find the best stations to target, of which there were 15. All of these stations were located in between 59th Street and 14th Street in Manhattan, wherein there is a large number of both females employed by tech companies and females working in tech occupations.

<iframe src="https://www.google.com/maps/d/embed?mid=1OwkxSCyGi7rrzaduR-dtDnP2bJhjNVJp" width="640" height="480"></iframe>

With the information regarding the best stations to target, we then determined which day of the week was the best to conduct outreach to reach our target audience. Analyzing the data, we found that the best days of the week to conduct outreach were Tuesday through Thursday, as those were the days with the highest number of entries and exits combined out of all the days of the week. The heat map below shows the results of our analysis of the data.

![Heatmap of daily entrances](aabramson92.github.io/images/Traffic for top 10 stations.png)

Finally, with the locations and days of the week, the last piece of information we needed for our recommendation is which weeks in the time period before and during the early summer would be the best to conduct the outreach in. With an analysis of total entries and exits for each week in the time period where data was collected, we found a steady level of ridership in the time period, except for the time period around the Memorial Day and Fourth of July holiday weeks. The heat map below shows the levels of entries and exits in the study time period and the decreases around the holiday weeks.

![Heatmap of weekly entrances](aabramson92.github.io/images/heatmap_fig_final.png)

With all of this analysis complete, we presented our first stage recommendation, that the outreach be conducted in a target area be between the 59th Street and 14th Street in Manhattan, that the outreach be conducted between Tuesday and Thursday in the week, and that the outreach not be conducted around the summer holidays.

For our second stage of analysis, we will focus on a more granular level of data for the entry and exit data. Firstly, we will analyze the combined number of entries and exits at each individual station entrance to determine where the optimal locations to conduct outreach by the targeted subway stops would be. In addition, we will take into account the distance between subway entrances as it may be more efficient to conduct outreach at the same station, but at entrances located 5 blocks from each other versus at two different stations that are only 1 block apart. Finally, we will focus on the exact times where the station entrances are the most used and determine which time of the day would be ideal to conduct outreach.