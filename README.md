# Kick starting with Excel

## Overview of Project
This is an analysis of historical data of several crowdfunding campaigns aiming different types of projects from around the world trough different years. For this particular analysis, we focused on theater plays around the world and if they were successful according to the launch month for the campaign, and also, how does the outcomes relate to the monetary goal.

### Purpose
The purpose of this analysis is to identify the best month to launch a crowdfunding campaign and to set the optimal monetary goal to fund a theater play in order to maximize the probability of success as an outcome.

## Analysis and Challenges
For this particular challenge what I found to be the most difficult was the correct interpretation of what was required, the background invites you to consider a filter by country it´s even required for deliverables 1 and 2, nonetheless, we are not asked to actually filter by country, even though we kind of know that the project is going to be launched in the US or maybe UK because of the previous activities and that was confusing.

I still don’t get why in the interpretation in the module 1 activities we can clearly see that the highest success outcomes come in May, later on, it says that the success outcomes tendency starts in June, that was super confusing and I came to the conclusion that it was a mistake of some kind.

### Analysis of Outcomes Based on Launch Date
![alt text](https://github.com/MauricioIQA/Module-1/blob/main/Theater_Outcomes_vs_Launch.png)

For this analysis we took all the data and then we filter by category to just have theater outcomes through the years, it’s important to say that this is a graph of the months with the input from outcomes that go way back to 2009 and end up in 2017. 

 We can appreciate in the “Theater Outcomes by Launch Date” graph that we have a relation between the month of the year and the record of how the outcomes went to those who decided to launch their campaigns in different months. 
 
We have three types of Outcomes: Successful, Failed and Canceled.   

### Analysis of Outcomes Based on Goals

![alt text](https://github.com/MauricioIQA/Module-1/blob/main/Outcomes_vs_Goals.png)

For this analysis we are comparing the percentage of our three outcomes possible that are Successful, Failed and Canceled and the relation with the goal based for the campaign we have $5,000 dollars as the difference between the sets. 

## Results

What are two conclusions you can draw about the Outcomes based on Launch Date?
- First you should definitely want to launch your play campaign on May, June, maybe July, not sooner not later. 
We need to be careful with our assumptions answering this question, let’s remember that the country wasn’t filter and that we are considering the years all the way back to 2007, art is especially susceptible to trends and seasonality, I would be more confident if we took in to account only the last two years, filtered by country, by state if possible, not with this data set but in the real scenario It should be consider, a play in NY is in a completely different environment than Washington, both in the US.

What can you conclude about the Outcomes based on Goals?
- I would carefully think that you have better chances of succeeding if you ask for more money, I´m aware that there’s a clear inflexion point, for some of us is not that harsh and the overall trend seems somewhat positive, maybe if que could go way higher in our research all the way up to 500k maybe the trend would be more obvious, and it somehow makes sense to me, In data analysis there’s always some sort of interpretation of the analyst, and for me if you have more resources you can actually pull out a play with better results. 

Another thing to consider, is that I’m almost positive that there’s a relationship between the number of supporters and the amount of money you manage to gather, it’s not like you are going to ask for 50k to 10 people, there’s going to be lots of people supporting those campaigns with big goals, and that is closely related to the way the market is going to behave towards the play, it’s just that in most cases there’s going to be more people involved and that´s what makes a play successful, the audience. 

What are some limitations of this dataset?
- As mentioned before, you would definitely want to go deeper than countries geographically speaking, we have countries with regions that seem completely opposite, in some cases they don’t even speak the same language. The play classification is still very wide, and this is because we are talking about art, there are thousands of genres and the market behaves completely different between them, we can compare it to music, if someone launched a music campaign for a boy band in L.A. will have a completely different result than someone launching a heavy metal band in the heart of Texas. 

What are some other possible tables and/or graphs that we could create?
- The question would be, which ones we should not create, in data analytics every single trend needs to be observed and analyzed, the relationship between outcomes and the rest of the variables, and also the combination of those variables. I can almost assure that there would be a close relationship with the ratio of supporters, average donation and monetary goal, the actual interaction of those tree make a completely different function that would behave in some relation with the outcomes. 
