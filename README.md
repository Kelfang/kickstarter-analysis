# An Analysis of Kickstarter Campaigns


## Overview

The purpose of this analysis is to determine how various theater campaigns performed in relation to their launch dates and their funding goals. 


## Analysis of the Data

In using the Kickstarter dataset, I have focused on the Parent Category of Theater and evaluated by month, rather than specific dates or weeks. This breakdown provides clear indications of optimal timing without furthering the assumptions that one day (or days) within a month is better than others. In addition, it’s important to see how many campaigns were successful, how many failed and how many were canceled each month. 

Aside from looking at the outcomes based on the launch month, I have evaluated the outcomes based on the goals that the same theater campaigns set. Here I elected to put the goals in ranges, much like specific dates, I do not believe it is beneficial to examine the outcomes in a single dollar increment. To fully understand the big picture, I also opted to focus on the campaigns that were successful, failed and canceled to mirror the launch date and keep the data cohesive.


## Challenges of the Data

Overall, the Kickstarter data is thorough and robust, both quantitative and qualitative. This gives me a high level of confidence that the data I’m presenting to you has tangible benefit. However, please keep in mind that the most recent year of this data is 2017, therefore it does not take into consideration the current state of the world. It does not register the impact of the COVID-19 pandemic, the present economic conditions and/or evolving social issues that might cause a shift of interest in play themes or subject matter. 


## Results

###### Launch Date

Diving into the launch date detail, you’ll see in the image below, that the month of May had the most successful campaigns with June close behind. In sharp contrast, the months of November and December were the least successful months to launch a campaign. Even though we’re looking at data from around the global, there are some prevalent reasons why time of year matters. November and December are significant holiday months that often drive spending into the direction of travel, gifts, and dining out. Therefore, I urge you to avoid these months. In May and June, it’s more likely that people are looking for opportunities to “get out of the home” once spring and summer arrive in the Northern Hemisphere. May is also the month following tax season in the United States which can often provide households with extra money and it’s a few months before the back-to-school spending kicks in. 

Shifting our focus to the failed campaigns, you’ll see that the trajectory mimics the successful campaigns until we start heading towards year end. October has the second highest percentage of failed campaigns in relation to the number of successful campaigns that month, following December. Even though the number of failed campaigns in October is only two less than May, there were 46 more successful campaigns in May than in October. This still makes May a far more favorable time to launch a campaign.

![Theater Outcomes by Launch Date](https://github.com/Kelfang/kickstarter-analysis/blob/main/Theater_Outcomes_vs_Launch.png)

###### Campaign Goals

Moving onto the campaign goals, you’ll see in the graph below that the greater chance of success in relation to failures is when the target goal is under $15,000 (USD).  If a goal can be kept below $5,000 the opportunity for success increases dramatically. If possible, I recommend trying to stay in this range to ensure the opportunity for success. While reviewing this graph you might experience a feeling of hope while looking at the $35,000 to $45,000 ranges, however, there are less than 10 campaigns that fall between those 2 amounts. Due to the small number of campaigns, I would want to see more theater campaign data in those ranges before drawing further conclusions. Therefore, I cannot recommend that you set your campaign goals between those dollar amounts. 

![Outcomes Based on Goal](https://github.com/Kelfang/kickstarter-analysis/blob/main/Outcomes_vs_Goals.png)


## Further Recommendations

As I previously stated, there is a robust amount of data that lies within these files. I would encourage some additional digging to make certain we’re evaluating this appropriately from all sides.

 1.	Geographical filtering – where is the play intended to be performed? Honing in on location would give better insight since this is where you’ll likely be soliciting donations. It will provide a more astute understanding of the donors in that area with regards to launch date and donation amount. 
2.	Percentage of goal funded – drilling down into what percentage the campaigns received in relation to their goal could further your confidence in where you should set your goal. I think knowing that a goal was missed by $10 or $1,000 can be helpful. This layered with location would likely give a better understanding of how people donate towards theaters in the pertinent location. 
3.	Backer count and average donation – coupled with the items listed above, this could provide additional insight on where to set the goal and when to time the launch. If there are more people donating during certain months and/or the average donation is higher at some points of the year, this would be beneficial. Knowing how many people you would need to reach and understanding the average donation may help determine if that would be feasible in the given location. 



