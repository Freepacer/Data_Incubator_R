# Data Analysis

Research quesion 1:

Is there any correlation between sleep time and general health condition? 
This may be helpful for people who want to know the relation between sleep and health.

Plot 1: https://github.com/Freepacer/Data_Incubator_R/blob/master/Plot%201.png

Result analysis: The mean sleep time is calculated by averaging all sleep time data (excluding N/A) for each general health condition
(excluding N/A). There is apparent negative correlation between average sleep time per day and general health condition. 
For example, the average sleep time is 7.19 hours for people with excellent general health condition, while only 6.74 hours for people with poor general health condition. 
Note that the relationship cannot be explained in an explanory way, because the data were acquired using phone interview. 
As a conclusion, we can observe obvious negative correlation bewteen average sleeping time and general health condition for US citizens.
 
Research question 2: 

Is there any correlation between the general health condition and the overall exercise time? That could mean either more exercise leads to better health condition, 
or people with better health condition tend to exercise more, or both.

Plot 2: https://github.com/Freepacer/Data_Incubator_R/blob/master/Plot%202.png

Result analysis: The total_monthly_hour is calculated by summarizing exercise hours per month for the exercises 
people spend the most and the second most time on (exercise times multiplied by time spent each time), then averaged over each health condition. 
All data entries of "N/A" are excluded.
According to the graph, the average total monthly exercise time decreases from 32 to 29.6 hours/month from "excellent" to "very good" 
health conditions. However, from "very good" to "poor" health conditions, the average total monthly exerise time increases almost linearly from 29.6 to 34.8 hours/month. 
There is not a clear positive or negaive correlation bewtween average total monthly exercise time and general health condition, which is quite different with the case of average sleeping time.
