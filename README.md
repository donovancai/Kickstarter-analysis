# An Analysis to Kickstart ***Fever***
>  For Louise
><br/>
## Overview of This Project 
    This project aims to identify factors and trends in Kickstarter campaigns that were successfully funded in the past, particularly those in the “theatrical plays” category. Analysis will be completed by using Excel, with tools and methods such as pivot tables, pivot graphs and various formulae. By analyzing past successful campaigns, we can identify effective methods that can be applied to Louise’s campaign to help her become fully funded.
<br/>  
   
### Purpose
	Kickstarter has many theater production campaigns and the most effective way for Louise to become successful on Kickstarter is by deciphering the receipt to success. By doing data analysis on past campaigns, Louise can level the playing field. 
<br/>  
   
#### Background
	An ambitious and up-and-coming playwright, Louise, is looking to fund her play, Fever. There are many moving parts in producing a play and Louise has estimated the budget for her project will be just over $10000, an amount she is looking to gather via crowdfunding. Given the estimated cost, Louise is a little uneasy about proceeding with it, and as a result, she has reached out to me for help in her decision making. 
	To help make Louise’s dream come true, I will be analyzing past theatrical production crowdfunding data on Kickstarter, especially those under the “play” category. In particular, I will be looking for common factors shared by successfully funded campaigns and apply similar methods to Louise’s Fever to give it the best chance at being fully funded. 
<br/>
 
## Analysis and Challenges
	The focus of the analysis is on Kickstarter campaigns under the “plays” category. The dataset from past Kickstarter campaigns ranges from 2009 to 2017. Two different analysis were conducted, “Theater Outcomes by Launch Date” and “Outcomes Based on Goals”. The first analysis focused on identifying whether certain month of the year had higher success rate in a campaign being fully funded. While the second analysis took an in-depth look at the correlation between a campaign’s funding goal and it’s success rate. 
<br/>

### Analysis of Outcomes Based on Launch Date
Although there were eight years of data presented, emphasis was given to individual months instead, due to the assumption that any individual year did not have any significant impact on campaigns being successful. Therefore, months across different years were grouped together in this analysis. 
By sorting data through a pivot chart and sorting by successful campaigns, a line graph was generated showing that May in any given year had the most number of successful campaigns (111 campaigns, as shown in the chart below). As such, I will recommend Louise to launch her campaign in May as well to guaranteed the best odds of it succeeding.

[Theater_Outcomes_vs_Launch.png](https://github.com/donovancai/Kickstarter-analysis/blob/main/Resources/Theater_Outcomes_vs_Launch.png)
<br/>

### Analysis of Outcomes Based on Goals
	In this analysis, the focus was the fundraising goals. The historic Kickstarter data had a wide range of goals, and as such 12 categories of goal breakdown were created. The exact breakdown can be seen in the chart below. 
	It can be seen that campaigns with goals less than $1000 has the highest success rate at 75.81%. Given Louise’s budget of just over $10000, historic data shows campaigns with goals between $10000 to $14999 only had a success rate of 54.17%, while failure in that same category was 45.83%. Although campaigns with goals less than $1000 has the highest success rate, it is unlikely that Louise will be able to pull off the production with that amount. 
	Looking at the chart below, campaign goals between $35000 to $39999 and $40000 to $44999 have success rates of 66.67%, which looks pretty good. However, it will be noted to Louise that these statistics should be taken with caution as there were only 9 data points between these two categories, which shows strong sample selection bias. 
[Outcomes_vs_Goals.png](https://github.com/donovancai/Kickstarter-analysis/blob/main/Resources/Outcomes_vs_Goals.png)
<br/>

### Challenges and Difficulties Encountered
The biggest challenge trying to determine whether partifuclar campaign goals had significant impact on success rate is sample selection bias. Looking at the pivot table below shoiwng the breakdown of the campiagn goal categories, it can clearly be seen that the majority of data points are in the first five categories. As previously stated, campaign goals between $35000 to $39999 and $40000 to $44999 have success rates of 66.67%, but there were only 9 data points between the two categoties. This is evidence that even if the chart is producing desiring results, one must determine whether there is truly enough underlying data to back it up. 

[Outcomes_Pivot](https://github.com/donovancai/Kickstarter-analysis/blob/main/Resources/Outcome_vs_Goals_Pivot.PNG)


## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

- What can you conclude about the Outcomes based on Goals?
- What are some limitations of this dataset?

- What are some other possible tables and/or graphs that we could create?
