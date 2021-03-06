# Kickstarting *Fever* : An Analysis
>  For Louise


## Overview of This Project 
   This project aims to identify factors and trends in Kickstarter campaigns that were successfully funded in the past, particularly those in the “theatrical plays” category. Analysis will be completed by using Excel, with tools and methods such as pivot tables, pivot graphs and various formulae. By analyzing past successful campaigns, we can identify effective methods that can be applied to Louise’s campaign to help her become fully funded.
<br/>  
   
### Purpose
   There are many Kickstarter campaigns for theater productions and the most effective way for Louise to become successful on Kickstarter is by deciphering the receipt to success. By conducting data analysis on past campaigns, Louise can level the playing field. 
<br/>  
   
#### Background
   An ambitious and up-and-coming playwright, Louise, is looking to fund her play, *Fever*. There are many moving parts in producing a play and Louise has estimated the budget for her project will be just over $10000, an amount she is looking to gather via a Kickstarter campaign. Given the estimated cost, Louise is a little uneasy about proceeding, therefore she has reached out for help in her decision making. 
   
   To help make Louise’s dream come true, past theatrical production crowdfunding data on Kickstarter will be analyzed, especially those under the “play” category. The analysis will look to reveal common factors shared by past successful campaigns and apply those methods to Louise’s campaign to give it the best chance at being fully funded. 
<br/>
 
## Analysis and Challenges
   The focus of the analyses is on Kickstarter campaigns under the “play” category. The dataset from past Kickstarter campaigns ranges from 2009 to 2017. Two different analyses are conducted, “Theater Outcomes by Launch Date” and “Outcomes Based on Goals”. The first analysis seeks to determine wether there is a correlation between month of the year and funding success rate. While the second analysis takes an in-depth look at the correlation between funding goal amount and success rate. 
<br/>

### Analysis of Outcomes Based on Launch Date
   Although there are eight years of data presented, emphasis is given to individual month instead, due to the assumption that any individual year did not have significant impact on the success rate. Therefore, months across different years were grouped together in this analysis. 
   
   Before the data can be analyzed, a new helper column is created to extract the launch year of each campaign. Then a pivot table is created with two filters, one on "Parent Category" and another on the helper column, "Year". As aforementioned, emphasis is placed on launch date by month rather than by year. To accomplish this goal, all the years in the pivot table are grouped to show months only. In other words, data points across different years are tallied up to show monthly totals. At this point, the data can be sorted by successful campaigns, a line graph is used to visualize the findings (linked below). 
   
   The line graph reveals that the month of May across different years has the most number of successful campaigns (111 campaigns or 13.2% of total). As such, it is recommended that Louise should launch her campaign in May to increase the likelihood of success.

[Theater_Outcomes_vs_Launch.png](https://github.com/donovancai/Kickstarter-analysis/blob/main/Resources/Theater_Outcomes_vs_Launch.png)
<br/>

### Analysis of Outcomes Based on Goals
   In this analysis, the focus was on successs rates among different fundraising goal amounts. To better quantify the data, 12 categories of goal amounts are created. The exact breakdown can be seen in [Outcomes_vs_Goals.png](https://github.com/donovancai/Kickstarter-analysis/blob/main/Resources/Outcomes_vs_Goals.png). 
   
   It can be seen that campaigns with goals less than $1000 has the highest success rate at 75.81%. Given Louise’s budget of just over $10000, historic data shows campaigns with goals between $10000 to $14999 only had a success rate of 54.17%, while failure in that same category was 45.83%. Although campaigns with goals less than $1000 has the highest success rate, it is unlikely that Louise will be able to pull off the production with that amount. 
   
   overall, Campaigns with goals less than $4999 have over 72% success rate, and campaigns with goals between $5000 to $19999 have success rates of about 53%. Louis should reconsider her $10000 budget for the play if she were to have a higher chance at success.
   

<br/>

### Challenges and Difficulties Encountered
   The biggest challenge trying to determine whether particular campaign goals had significant impact on success rate is the lack of data for campaigns with higher goals. Looking at the pivot table below showing the breakdown of the campaign goal categories, it can clearly be seen that the majority of data points are in the first five categories. As previously stated, campaign goals between $35000 to $39999 and $40000 to $44999 have success rates of 66.67%, but there were only 9 data points between the two categories. This is evidence that even if the chart is producing desiring results, one must determine whether there is truly enough underlying data to back it up. 

[Outcomes_Pivot](https://github.com/donovancai/Kickstarter-analysis/blob/main/Resources/Outcome_vs_Goals_Pivot.PNG)


## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
   > The first outcome from this analysis is that May is the month with the most successful campaigns. 
   
   > The Second outcome is that December is the month with the fewest successful campaigns. Louise should seek to launch her campaign in May and avoid launching in December at all costs. 

- What can you conclude about the Outcomes based on Goals?
   > Campaigns with goals less than $4999 have over 72% success rate, and campaigns with goals between $5000 to $19999 have success rates of about 53%. Louis should reconsider her $10000 budget for the play if she were to have a higher chance at success. 

- What are some limitations of this dataset?
   > One of the limitations of this dataset is that there is a limited quantity of campaigns of higher funding goals, which would help determining whether higher funding goals truly result in higher failure rates. Another limitation is that the analysis assumes that individual years have no impact on success rates, which is a bit of a stretch. Going to see a play is considered a discretionary activity, an increase in discretionary spending is linked to strong economic environments. By ignoring individual years, economic activity and personal income during those year cannot be taken into affect in forming a conclusion. 

- What are some other possible tables and/or graphs that we could create?
   > We can dive deeper into outcomes based on launch date by breaking down each month with categories we created for Outcome Based on Goals. This way we can see if the month of May has also been historically good for launching campaigns with goals over $10000. 
   
   > As well, another analysis can be done to find correlation between funding goals and countries. This might reveal countries that are indifferent to campaigns with higher goals and Louise can choose to launch her campaign there instead. 

