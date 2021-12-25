# Kickstarting with Excel

## Overview of Project

### Purpose

The purpose of this data analysis is to help my client, Louise, determine how best to offer incentives for fundraising plays in the future. To do that I am taking data from Kickstarter.com to calculate the success of previous fundraising campaigns. I am using two metrics: 1) the comparison of the relationship between launch dates and fundraising goals. 2) the comparison of the rates of success and failure with the amount of funding requested.
## Background

Louise’s recent campaign for the play Fever came close to its goal but did not reach it by the deadline. The campaign ran for just under one month. Being shy by only $400, less than the average pledge of two backers, she wants to know had the campaign run longer if it would have met its goal.

## Analysis and Challenges

There are three caveats to mention before outlining the methodology of my analysis. 

1 Accuracy of the data provided: I was not involved in collecting the initial data and as such I cannot speak to the accuracy or comprehensiveness of the data provided. I will have to assume that the information provided for my analysis is complete and correct. 

2 Limitations of the data source: Kickstarter.com provided the data for my analysis. Though Kickstarter is a popular fundraising site it is far from the only one. There are dozens of other websites whose data is not in the dataset. Additionally, I am not including analog forms of fundraising such as galas and word-of-mouth campaigns in this analysis. However, since Louise plans to use Kickstarter.com for future fundraisers she asked that I use only its data.

3 Data provided does not include campaign strategy: While this analysis focuses on the relationship between fundraising goals and timeframe, it does not measure methods for reaching out to backers. There is no metric for measuring interest in fundraising plays vs other forms of entertainment, certain genres over others, or the popularity of specific plays. This data analysis can only help determine how much time a campaign needs to reach its goal, but without other metrics it is impossible to predict the outcome of future Kickstarter campaigns with 100 percent confidence.

### Analysis of Outcomes Based on Launch Date

As Louise wanted to gain an understanding of the relationship between time and campaign success, I needed to create a couple of metrics for measuring it. First, because the time of year could play a role in campaign success, I wanted to explore the relationship between success and launch month. The data provided shows campaigns in four statuses: successful, failed, canceled, and live. Because live campaigns have not finished, it cannot be determined if they will be successful. I eliminated them from my calculations which left only three statuses for campaigns that ended. I wanted to control for canceled campaigns so I included them in the chart below.

![ Theater_Outcomes_vs_Launch](https://github.com/JovanHumphrey/Kickstarter-Analysis/blob/main/Theater_Outcomes_vs_Launch.png)

The campaign for Fever ran from June to July of 2016. We can see that historically more campaigns were launched in June than any other month except May. Additionally, campaigns launched in June were often more successful than any other month outside May. They were successful 65% of the time as compared to 67% in May, and as low as 49% in December. Taking it a step further we can see that again outside of May, June campaigns had the lowest percentage of failure. From this metric we can estimate that the launch month is not a leading factor in Fever’s failure.

### Analysis of Outcomes Based on Goals

Next, I wanted to see if Fever failed because the financial goal was too high. I created the chart below by first dividing the campaign goals into twelve categories: Below $1,000, Campaigns above $50,000, and everything in between in $5000 increments. I could have broken it down further, but I believed that these increments would accomplish my goals.

For the y-axis I created columns for successful play campaigns, failed play campaigns, and canceled play campaigns. Once I calculated those numbers, I added the totals up and measured success, failure, and cancelation in percentages against the total.

The campaign for Fever had a modest goal of $2,885. 515 other campaigns for plays were in the same bracket ($1000-$4999). Campaigns in that bracket were successful 75% of the time compared to 55% for campaigns between $5000-$9999. Only campaigns with goals under $1000 were more successful. This tells us that the campaign goal for Fever was not too high to attract backers.

![ Outcomes_vs_Goals](https://github.com/JovanHumphrey/Kickstarter-Analysis/blob/main/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered

## Results

Looking at the graph titled Theater Outcomes vs Launch Date we can see that more successful campaigns were launched in May and June than in any other month. Campaigns launched in December had fewer successes. It could be ill-advised to launch a theater campaign at the end of the year. It may be that as summer approaches, potential backers start thinking ahead to leisure activities and thus, are interested in funding those activities. While at the end of the year, potential backers may be committed to enough holiday events that they are less inclined to think about leisure. I would want to do more research before speculating further on backer motivations, but for now we can conclude that time of year does play a factor in campaign success.

- Limitations of the Dataset

As outlined in the Analysis and Challenges section of this report, there are three major reasons to conclude that this dataset is limited in its usefulness. It does not measure market interest, nor does it track campaign strategy. Additionally, this dataset only comes from one online fundraising platforms, ignoring vital information about other platforms and sites. It is possible that other fundraising techniques could be more successful than an online one. Patrons of the theater due to class, wealth, and age, may be less internet-savvy and may prefer more traditional fundraising methods. It may be that in-person fundraising campaigns for the theater are more successful, or perhaps a site like GoFundMe.com attracts backers in the arts more readily than Kickstarter.com does. To add to this the dataset only goes as far back as 2009, while fundraising for the theater is a centuries old practice. We can see that there were few plays campaigned for in 2009 vs 2017, aligning with the increased popularity of crowdfunding platforms such as Kickstarter.com. This may indicate that as the platform becomes more popular, Kickstarter campaigns may be utilized more often in the theater industry. It is unknown at this time if other fundraising methodologies will be introduced in the future and how that may influence the success of Kickstarter campaigns.

- Tables and graphs I would like to add for analysis

It is possible that further breaking down the Outcomes by Goals chart into more brackets, could show that campaigns between $2000-$3000 have a different rate of success than campaigns with slightly higher or lower goals. Perhaps had Louise’s goal been $2700 instead of $2885 she could have attracted another backer or two.

It would be useful to create a chart or graph showing successful goals on one axis, and the number of backers on the other. Or I could make a chart comparing average backer pledges for successful versus failed campaigns. These charts could tell us how much of a financial-load backers are willing to take for a play, and how many backers a campaign may need.

