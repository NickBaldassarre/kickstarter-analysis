# An Analysis of Kickstarter Campaigns

## Overview of Project

### In order to better plan an upcoming Kickstarter campaign for a theater production, I took a look at how different theater campaigns fared in relation to their launch dates and funding goals.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

First, I looked at the relationship between launch dates and outcomes. To do this, I created a pivot table with count of outcomes as my values. Filtering for theater as a the parent category, I compared month launched to outcomes, then created a line chart to visualize the relationship.

![Success Rates of Theater Kickstarter Campaigns Based on Launch Date](https://github.com/NickBaldassarre/kickstarter-analysis/blob/8c78b1a2f619259a36c16924e94a56fa0b07109c/Resources/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals

Next, I looked at the relationship between goals and outcomes. For this, I used the COUNTIFS function in Excel to count the outcomes for plays that fell within certain ranges. From here, I calculated the percentages of instances for each outcome within the specified ranges, and charted these on a line graph.

![Success Rates of Theater Kickstarter Campaigns Based on Campaign Goals](https://github.com/NickBaldassarre/kickstarter-analysis/blob/a40818ba0485acd8764a92af4768ca5b2c8cbd35/Resources/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered

Challenges that I could see arising when analysing this dataset would include deciding upon which relationships to study.

## Results

Based on my analysis of outcomes based on launch date, I can conclude that a theater campaign launched in May is more likely to succeed than one launched during any other month of the year. I can also conclude that a theater campaign launched in December has the lowest chance of success, and is just as likely to fail as it is to succeed. Given the fact that very few campaigns in this dataset took place in the southern hemisphere, it would seem that the summer months coincide with higher rates of success, gradually declining towards a low rate of success in the winter months. I would recommend launching this campaign in May.

Based on my analysis of outcomes based on goals, there seem to be two sweet spots that yield the highest rates of success: $0 - $5000, and $35,000 - $45,000. Conversely, the highest rates of failure are attributed to goals between $25,000 - $35,000, and goals above $45,000. I would recommend a campaign goal of $40,000 for this project.

One limitation of this dataset is that the vast majority of the data is from 2014 - 2016. More data from recent years would be very helpful.

Further recommended analysis would include charts showing the relationship between outcomes and length of campaign, as well as the relationship between outcomes and average donations.
