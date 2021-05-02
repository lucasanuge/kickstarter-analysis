# Kickstarting with Excel

## Overview of Project

We are analyzing our Kickstarter data to see trends between the launch date of a play and it's outcome.

### Purpose

The purpose of this project is to help Louise to compare her play "Fever" with other plays in our Kickstarter data  base. We would like to help Louise make similar decisions as successful plays in order to increase her chances of having a successful play.

## Analysis and Challenges

For our first analysis, we compared the outcomes of all the shows in the theater category ('successful', 'failed', and 'canceled'), in our Kickstarter database, to the months at which the shows were launched. 
For our second analysis, we found the percentages of different outcomes of plays based of their fundraising goals. 

### Analysis of Outcomes Based on Launch Date

We used PivotTable to count the number outcomes of all the shows under the category of 'theater' based on the month at which the shows were launched. We only used 'successful', 'failed', and 'canceled' outcomes for this analysis. We then used PivotChart to visualize our findings as a line graph. 

### Analysis of Outcomes Based on Goals

We used the COUNTIFS() function to count the number of shows in different combinations of outcomes and fundraising goals. We also chose shows that were 'plays'. For each fundraising goal and outcome combination, we found their row percentage and made a line chart using PivotChart.

### Challenges and Difficulties Encountered

There were no difficulties encountered during the analysis. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

From the **Theater_Outcomes_vs_Launch.png**, we observe that there is an increasing trend of  successful plays from the month of January to May, and then a decreasing trend towards the end of the year. The peak of successful plays happens during the month of May. As for the failed and cancelled plays, we see no trends seen from our chart. 

This means that no matter what month it is in the year, the number of launched canceled and failed theater shows are relatively similar. However, most successful theater shows  launched during the summer months and the number of successful shows decrease as the year progresses.

- What can you conclude about the Outcomes based on Goals?

From the **Outcomes_vs_Goals.png** chart, we see that the percentage of failed plays increases as their goal increases and that the percentafe of successful plays decreases as the goal of the play increases.

This means that a successful play is not based on how high their fundraising goal is. The higher the fundraising goal of a play, the higher the chance of it failing.

- What are some limitations of this dataset?

limitations to this data set is that it has a few unnecessary column data such as 'blurb' and 'currency'. We have already been given the parent category and subcategory of each show, hence, a description of the show is unnecessary. We have also been given which country the show comes from, hence, knowing the currency of the each show is also unnecessary. 

- What are some other possible tables and/or graphs that we could create?

Other possible graphs will be a histogram of the pledged column in our data set. We could see its distribution and find out whether it is skewed or normally distributed.
