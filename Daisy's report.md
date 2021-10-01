# Kickstarting with Excel

## Overview of Project
This analysis including pivot tables, some charts, and the statistic of the kickstarters in the U.S. and GB. It clearly define the successful,failed,and canceled outcomes with a visual exhibition and descriptive statistics such as the the mean, median, standard deviation, and the quartile of the goal  and pledged. We specialized the theater outcomes by launch date and goals, so we can see the outcome trending  of the parent category month by month. We use box plots to compare the distribution of campaign goals and the distribution of total amounts pledged for plays in Great Britain as well. 
### Purpose
Understanding the meaning of mean, median, standard deviation and quartile. Using excel skills to define different outcomes of the kickstarters and visualizing Distributions in several charts. Becoming familiar with filter and field in the pivot table. 

## Analysis and Challenges
 
### Analysis of Outcomes Based on Launch Date
I use the parent category and years as filter and years in the rows as well at the beginning. The chart ranged by years instead of months showed in the picture. I tried to put years 2 and not working finally, I just used the date created conversion and it looks exactly the same as the picture required. Also filter for the descend for the cancel, failed and successful is hard to find, I tried most filter tabs and field options that I could see obviously. Finally, I found it on the table its-self. 

### Analysis of Outcomes Based on Goals
There were many coding skills in this part. I use countifs formula to solve the first cell which was B2 then copy to B3 and adding another criteria to limit the upper range. The hard part was clicking data from the original kickstarter sheet and it still showed the data from Outcomes based on goals sheet, so I have to put it in order manually.   
### Challenges and Difficulties Encountered
I use the data resource from different spread sheets to count for Descriptive Statistics, use year() code to find the year on the launch year, use pivot table and filter to show the main character that I want to show to the reader. The most challenge part for me is to be familiar and remember all the meaning of the codes to apply in a real products. It is hard to complete all the requirements without hints. Especially converting the date from serial numbers to readable date in formula. To design the pivot table also is a tough part since I am not sure which content goes to row or columns.I have to try so many times to play around to figure it out.  
## Results

###- *What are two conclusions you can draw about the Outcomes based on Launch Date?*
![avatar](https://raw.githubusercontent.com/Daisyzhao21/KICKSTARTER-ANALYSIS/3af3337b98f1d9c0dc4122d68381234a16d0d75f/Theater_Outcomes_vs_Launch.png)

The outcome of successful number is almost doubled the failed number.
	
From May, the successful is on the highest number of 111 and decreasing about 10 each month later until September. 
	
Failed number is relatively flat at the range of 31-52 during the whole year. Based on Launch date, the outcome is more successful 

###- *What can you conclude about the Outcomes based on Goals?*
![avatar](https://raw.githubusercontent.com/Daisyzhao21/KICKSTARTER-ANALYSIS/3af3337b98f1d9c0dc4122d68381234a16d0d75f/outcome_vs_goals.png)
Based on the graph, which is symmetrically for the successful and failed, when some successful there are similar number of them failed and the canceled are 0.

Based on the goals, the outcome is half successful and half failed. 

###- *What are some limitations of this dataset?*
It can show the overall successful, failed and canceled percentage but a box plot can give a clear define most of the successful people are below the median 50%

###- *What are some other possible tables and/or graphs that we could create?*
I have attached a bot plot of percentage of failed and successful based on goals
It can show that most of the successful people are below the median 50% and the failed people are mostly over the median and up to 70% percent.
![avatar](https://raw.githubusercontent.com/Daisyzhao21/KICKSTARTER-ANALYSIS/3af3337b98f1d9c0dc4122d68381234a16d0d75f/possible%20graph.png)