# Kickstarting with Excel

## Overview of Project

### Purpose

The purpose of this analysis is to see how different Kickstarter crowdfunding campaigns for theatrical plays fared in relation to their launch dates and their funding goals. I use the Kickstarter dataset that was utilized extensively throughout the coursework of Module 1 to visualize campaign outcomes based on their launch dates and their funding goals.

This analysis is done with the intention of advising a playwright named Louise on the things she might be able to do in order to increase her chances of success when starting future crowdfunding campaigns for her plays. 


## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

For the first deliverable, I created a visualization that showed campaign outcomes (“successful”, “failed”, and “canceled”) based on launch date. I performed this task in Microsoft Excel using the default Pivot Table and Line Graph tools provided in the software. 

This graph is useful because there might be a certain time of year/month when crowdfunding campaigns for plays might be more successful. If successful campaigns are more likely to be started in a certain month of the year or season, that information would certainly be valuable to Louise. With this information, Louise can make sure she starts her crowdfunding campaigns during the periods that correlate with the highest likelihood of success.

<img width="386" alt="Theater_Outcomes_vs_Launch" src="https://user-images.githubusercontent.com/80979705/119108722-80408880-b9ee-11eb-80f5-5f1c621ec02d.png">



### Analysis of Outcomes Based on Goals

For the second deliverable, I created a visualization that showed the percentage of successful, failed, and canceled plays based on the funding goal amount. I used Microsoft Excel to perform this task; I made good use of the ‘=COUNTIFS’ function, along with other Excel functions to create percentages and sums, to change the format of the data into a table that was useful for determining the probability of success according to the size of the fundraising goal. 

I then used the information in the table to create a line graph to better display this information. This line graph visualized the probability of success according to the size of the fundraising goal, which was split into units of around 5000 US Dollars.

This is potentially useful information for Louise because she will be better informed when setting her fundraising goals. It might also be interesting to see if larger monetary goals are correlated with less successful campaign outcomes. One might think this because raising more money should be more difficult than raising a smaller amount of money. In short, smaller goals should be more attainable than larger ones.

<img width="404" alt="Outcomes_vs_Goals" src="https://user-images.githubusercontent.com/80979705/119108840-a2d2a180-b9ee-11eb-963a-d662482a2ebc.png">



### Challenges and Difficulties Encountered

#### First Deliverable

A challenge I encountered in the first deliverable was while setting up the pivot table. When I first set up the pivot table, I had years and months in the rows- despite that not being my intention. I was able to resolve this through trial and error by deleting the ‘years2’ variable in the ‘Axis (Categories)’ section of the pivot table field menu.

#### Second Deliverable

While I did not encounter any challenges while working on the second deliverable, I did find filling in the table using the “=COUNTIFS” function time consuming and mundane. It is a very meticulous task since a single spelling error in just one of the many Excel equations contained in the cells can wildly change your outcomes and the resulting line graph. 

It is also important to meticulously check that one is filtering all the variables that are asked. I am including this because I almost forgot to filter the ‘subcategory’ data to only include plays (and not all the Kickstarter data unfiltered).

Secondly, it is to be noted that I was unsure whether to include the data for ‘canceled’ in the line graph since the value was ‘0’ for all the plays. In the end, I decided to include it since ‘canceled’ was still included in the legend of the example graph provided online- meaning the ‘canceled’ outcome data was still included in that graph, despite being null.


## Results


<img width="386" alt="Theater_Outcomes_vs_Launch" src="https://user-images.githubusercontent.com/80979705/119108497-3fe10a80-b9ee-11eb-8070-f364e2d95969.png">

### What are two conclusions you can draw about the Outcomes based on Launch Date?

#### First Conclusion

The visualization displaying Outcomes based on Launch Date shows that Kickstarter campaigns for plays tend to be much more successful in the early summer, and specifically May and June. 

While the number of failed outcomes for crowdfunding campaigns stays around the same throughout the year (varying between a low of 31 in November, and a high of 52 in May), successful outcomes vary greatly by season and peak in the month of May (Successful outcomes reach a high of 111 in May, while successful outcomes dip to a low of 37 in the month of December). In May, there are 111 campaigns started that turned out to be successful, compared to only 52 campaigns started that failed that month. Contrast this with December and the difference is striking; out of all the fundraising campaigns started in December, only 37 campaigns reached their fundraising goals, and 35 campaigns started that month failed.

Given this information, it would be wise for Louise to start her fundraising campaigns in the early summer, specifically May, and avoid fundraising in the winter, especially in December.

This outcome makes sense as plays and theatrical productions in general are more popular in the summer. This may be due to factors such as the longer hours of daylight, warmer weather, and the many large arts festivals that take place in the summer, such as the Edinburgh Fringe.

#### Second Conclusion

As touched upon briefly in my previous response, my second conclusion is that the month of December should be avoided at all costs when starting Kickstarter campaigns with the intent of crowdfunding a play. In December, the chances of starting a successful campaign drop to nearly 50% (compared to nearly a 67% chance of success when started in May).

The reasons for a lack of successful campaigns starting in May could include the short days, cold weather, distractions related to the holidays, and usual patrons lacking additional disposable income in that month, relative to other months, due to the annual costs of Christmas gift shopping. In addition to this, people might just be busier in general due to Christmas/Hanukkah/Kwanza/New Year preparations and celebrations.

Consequently, I would advise Louise to avoid starting Kickstarter campaigns for her plays in the month of December, if possible, in order to increase her chances of success.


<img width="404" alt="Outcomes_vs_Goals" src="https://user-images.githubusercontent.com/80979705/119108605-5b4c1580-b9ee-11eb-9351-98786bf1fb65.png">

### What can you conclude about the Outcomes based on Goals?

While one might rationally think that the chances of a successful campaign decrease when fundraising goals increase, that is not exactly true. While there is a general trend that suggests the likelihood of starting a successful campaign shares a negative relationship with the size of the fundraising goal set (that is, larger fundraising goals/targets are more difficult to meet than smaller fundraising goals), crowdfunding campaigns that have goals between $35,000 and $44,999 enjoy a tremendous amount of success. Campaigns with a fundraising goal between $35,000 and $44,999 are more successful than all other crowdfunding campaigns when sorted by goal, with the only exception being campaigns with goals under $4,999. 

Based on this information, I conclude Kickstarter campaigns for plays enjoy a higher likelihood of success when the fundraising goal is between $35,000 and $44,999, or below $5000. If a goal between $35,000 and $44,999 is impossible, then it is generally the best practice to decrease the fundraising goal as much as possible, in order to increase the likelihood of success.

Based on this data, I would advise Louise to keep her fundraising goals for her Kickstarter campaigns between $35,000 and $44,999 – unless she can cut the play’s production costs so much as to decrease her fundraising goal to below $5000.


### What are some limitations of this dataset?

Limitations of this dataset include the size, while the entire dataset unfiltered is large, it is much smaller when only taking into account plays (total:1393). A good example of the small size of the data being an issue was encountered while working on the first deliverable, when the ‘canceled’ outcome category was completely empty.

Another notable limitation is age of the data, the data seems to be a bit out of date and last updated in 2017. While 2017 is not too long ago, it is a long enough period of time that changes unaccounted for might have occurred in the crowdfunding sector, theatre/dramatic arts market (or entertainment market, in general), and the overall economy (such as a pandemic maybe!) that would make the conclusions based on this data obsolete and irrelevant.

Another limitation (or ‘slight annoyance’, rather), was the lack of ‘live’ outcome data for months other than January through March. Presumably, the reason for this is because the data was last updated in mid/late March or early April. In an ideal world, it would be nice to go back and find out whether those ‘live’ crowdfunding campaigns turned out to be successful or not.


### What are some other possible tables and/or graphs that we could create?

-	As Louise was interested in both the US and UK markets for her plays, it would potentially be useful to create a visualization that displayed Outcome based on Country, this way one would be able to see which countries enjoyed the highest success rate for crowdfunded plays.

-	Another possible graph that might be of interest would be to visualize ‘Outcome based on Genre’. This could be done by sorting the plays connected to the fundraising campaigns into different genres using the given blurbs. You could then see if comedies or tragedies received higher levels of success.

-	Lastly, another possible visualization that could be useful would sort outcomes based on length of campaign. While one may assume, longer campaigns meet their fundraising goals more often (and therefore, are more successful) because they are given more time to reach their targets, this may not be the case if you take into account factors like ‘exclusivity’ and ‘hype’. This would potentially be useful for Louise because she can make more informed decisions on how long to pursue her fundraising campaigns and keep them ‘live’, before giving up or canceling it. 

