# An Analysis of Kickstarter Campaigns
## Description
In this project, I performed basic data analysis on several thousand crowdfunding projects on Kickstarter to try and uncover any hidden trends. 
To do this, I used Microsoft Excel and its tools, such as VLookup, Pivot Tables, and Pivot Charts. Most of the data I focused on was related to the Theatre industry, and more specifically: plays and musicals. I analysed the attributes of what makes a kickstarter campaign succesful, focusing on the differences in the statistical distribution of pledges, goals, and average donation for both failed and succesful Kickstarter campaigns in the Theatre industry. I also took into account variables such as country and year. My Excel workbook can be found attached in this GitHub repository. 

Louise, a playwright who is looking to fund the her theatrical production named 'Fever', is my main client for this exercise, as she is looking for information and advice on how to launch a succesful Kickstarter campaign. 

## Report 

Judging from my findings, Louise would be well suited to launch a Kickstarter campaign. While there are only a total of 604 Kickstarter campaigns for plays in Great Britain, the 'theater' category is the most succesful. The month that launched the most successful Kickstarter campaigns was May. However, January, June, July and October all had roughly the same number of failed campaigns launched.
Failed Kickstarter campaigns have much higher fundraising goals than successful Kickstarter campaigns. Louise is asking for more than twice the average successful Kickstarter goal, so this isn't great news for her campaign. In addition, the mean and median pledged amounts are much lower than the successful pledges, which indicates that failed Kickstarter campaigns are unsuccessful for reasons other than asking for too much money. In other words, if the failed projects were also getting a median pledge amount of around $3,000, it's possible that those that failed just asked for too high of a price. Since the median is much lower, there must be another factor keeping people from pledging to those unsuccessful projects. Because of this, it is suggested Louise try to lower her fundraising goal if possible.

When I looked at the statistics of the distribution between succesful and failed campaigns and their pledged and goal amounts, I discovered:
  - The mean of each distribution is around the 3rd quartile, so the data follows similar distributions in each subset.
  - The standard deviations are larger than the mean, which means everything below the mean is considered "close" to the center.
  - Some large values are driving all of these distributions. The standard deviations are all roughly twice the IQR in each distribution, except in the failed Kickstarters, where the standard deviation is closer to three times the IQR. There must be some failed Kickstarters with really high goals.

While Louise is committed to her play in the US, she is also interested in the UK theatrical market, specifically, if 4000 GBP is a good Kickstarter goal. The mean campaign goal is around £4,000. This is outside of the range of outliers for amount pledged, so Louise should probably try to get her play produced for less than £4,000. Half of the campaign goals are less than £2,000, which is just over the 3rd quartile for amounts pledged.

<img width="347" alt="Outcomes based on launch date just theatre" src="https://user-images.githubusercontent.com/80979705/119069866-eb6d6900-b9b4-11eb-83bd-eaf881f9a21d.png">
<img width="244" alt="Line Chart" src="https://user-images.githubusercontent.com/80979705/119069838-e0b2d400-b9b4-11eb-9823-f26197b4ad81.png">
<img width="360" alt="Parent Category Outcomes Theatre" src="https://user-images.githubusercontent.com/80979705/119069879-f1fbe080-b9b4-11eb-8ca7-5d09f88223f9.png">
<img width="361" alt="Parent Category Outcomes" src="https://user-images.githubusercontent.com/80979705/119069892-f58f6780-b9b4-11eb-82c5-6564fb01632c.png">
<img width="493" alt="US Theatre Subcategory Analysis" src="https://user-images.githubusercontent.com/80979705/119069901-f922ee80-b9b4-11eb-8844-1ff8adfe49e3.png">
<img width="777" alt="Box and Whiskers Chart" src="https://user-images.githubusercontent.com/80979705/119069905-fc1ddf00-b9b4-11eb-9752-4baadcb18d6c.PNG">

