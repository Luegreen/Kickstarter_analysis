# Kickstarter Analysis
## Analysis on Kickstarter Data (Columbia)
# Overview of Project
A hypothetical client funds her plays from Kickstarter. Her campaign is already successful but she'd like to know, based on the goals and launch date, what can propel her to consistently successful results. 

### Analysis of Outcome Based on Launch Date
Beginning with the Theater Outcome by Launch Graph (below), there appears to be an obvious take away: Launch in May. However, I wondered a few things: How evenly is the data spread over the years? Our client is focused on plays, it would be better if we stuck with play analysis specifically (not all of theater). Is there a trend over the years or just an accumulation of values over the years?
![Theater_Outcomes_by_Launch_Date](https://user-images.githubusercontent.com/14239715/115100929-46232900-9f0e-11eb-9c3e-28b44e3236db.png)

I also wondered if there were trends for all of Kickstart, or just the plays. The below graph shows all of the Kickstarter data in this data set by Launch Date. It makes it clear that there is only significant data in 2014, 2015 and 2016.
![All Kickstarter by Date](https://user-images.githubusercontent.com/14239715/115100955-6c48c900-9f0e-11eb-91ab-c7f2738dbcc4.png)

I was then curious about plays only. January and February of 2014 are missing. So we realize that there are not enough consistent years to notice a signficant trend.
![All Play Kickstarter by Date](https://user-images.githubusercontent.com/14239715/115101130-b8483d80-9f0f-11eb-9da5-2bc04892154d.png)


And finally I wanted to see the success/failure ratio over each year for plays only. We can see that the boost in May is not a consistent trend but merely an month of success in 2015 only. The successes mirror the graph above that shows all of the play campaigns. At best we can say that more play campaigns were run in the earlier part of the year, but not that there was a higher percentage of success consistently in the early part of the years. 
![All Play Success:Fail Kickstarter by Date](https://user-images.githubusercontent.com/14239715/115101014-ec6f2e80-9f0e-11eb-86f9-a8daff2942bb.png)


### Analysis of Outcome Based on Goals
An initial analysis of percentage of goals as shown in this chart implies that the most successful goals are less than 5k, but there is also a spike at 35K and 45K. ![Outcome_vs_Goal](https://user-images.githubusercontent.com/14239715/114959758-b1e49380-9e33-11eb-8ccf-712008423168.png)



These conclusions are deceptive because they show the **percentage of each outcome** per goal dollar bracket. I was curious how many actual campaigns were in each bracket. I ran a statistical analysis showing that data set is heavily right scewed meaning the vast majority of the values are on the lower side of the data set. The mean is less that the medium on both the Successful and Failed Campaign goals.
<img width="369" alt="Statistical Analysis of Play Goals" src="https://user-images.githubusercontent.com/14239715/114959464-20752180-9e33-11eb-8e62-be52c7eaee01.png">

I was eager to find a way to illustrate this to the client. The following graph shows the value of all campaign goals for plays.  
(!![Number of Play Campaigns by Goal](https://user-images.githubusercontent.com/14239715/114956496-01739100-9e2d-11eb-8f78-22a26b3da751.png) It illustrates that the 35K to 45K Goal success has a tiny sample number thus is statistically insignificant. The vast majority of Goals, both successful and Failing are between the 1K to 5K Goal bracket. I though it would be interesting to break these down to see if we could get more specific about our recommendation. I created this chart of only the Successful Plays with goals between 1K and 5K. ![Successful_Plays_Pie](https://user-images.githubusercontent.com/14239715/114957262-a9d62500-9e2e-11eb-811d-e9ef38ae95b0.png)







### Challenges and Difficulties Encountered
I faced some challenges beginning with not knowing my way around Excel. When tasked to build the Launch Date Pivot tables, I was struggling with a number of data points that had no date. I realize that I had converted the Date Code while a filter was on. This left a number of rows with no converted year. 

When building the Goals data set, my graphs were different from the example. I realized that an entire Goal Bracket was missing, and, that I hadn't filtered the data set to plays. Once I filled that in, my graphs began to parallel the example. I also had to nest the 'success' 'fail' metric into the formulas which was a fun problem to solve. Finally, the chart was organizing the rows out of order. I had to create an index column to get the columns to line up in the correct order. 

## Results: 
# 2 Conclusions based on Launch Date: 1) Two of the three months in the data set had the highest success ratio in June (2014, 2015) and the third has the best success ratio in March, April and May (2016). 2) There are more Kickstarter Play Campaigns launched in the spring months of the year but that does not reflect thier likelyhood of success. 

# Conclusions based on Goals: the client will have the most success with goals between $1000 and $3500. 
Limitations of the Data set: the data set is deeply skewed right. This may be a reflection of Kickstarter. It may be a platform that induces lower goals. 

Also, the date range of this data set is limited. Although it has values from many years, the majority of data between 2014 and 2016. 

It would be interesting to compare Kickstarter data with other fund raising platforms. It would also be interesting to compare the different types of Campaigns by Category and Sub-category against one another to see which were the highest/lowest fund raising projects the platform supports. 

