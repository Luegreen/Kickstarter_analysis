# Kickstarter_analysis
## Analysis on Kickstarter Data (Columbia)
Overview of Project
A hypothetical client funds her plays from Kickstarter. Her campaign is already successful but she'd like to know, based on the goals and launch date, what can propel her to consistently successful results. 

## Analysis and Challenges 
I faced some challenges beginning with not knowing my way around Excel. When tasked to build the Launch Date Pivot tables, I was struggling with a number of data points that had no date. I realize that I had converted the Date Code while a filter was on. This left a number of rows with no converted year. 

When building the Goals data set, my graphs were different from the example. I realized that an entire Goal Bracket was missing, and, that I hadn't filtered the data set to plays. Once I filled that in, my graphs began to parallel the example. I also had to nest the 'success' 'fail' metric into the formulas which was a fun problem to solve. 

### Analysis of Outcome Based on Launch Date

### Analysis of Outcome Based on Goals
Although an initial analysis of percentage of goals as shown in this chart implies that the most successful goals are less than 5k, but there is also a spike at 35K and 45K. !(https://user-images.githubusercontent.com/14239715/114956163-52cf5080-9e2c-11eb-95a6-e26e1060c9da.png)


These conclusions are deceptive because they show the percentage of each outcome per goal dollar bracket. I was curious how many actual campaigns were in each bracket. I ran a statistical analysis showing that data set is heavily right scewed meaning the vast majority of the values are on the lower side of the data set. The mean is less that the medium on both the Successful and Failed Campaign goals. <img width="369" alt="Statistical Analysis of Play Goals" src="https://user-images.githubusercontent.com/14239715/114959464-20752180-9e33-11eb-8e62-be52c7eaee01.png">

I was eager to find a way to illustrate this to the client. I camm up with the following graph. 
(!![Number of Play Campaigns by Goal](https://user-images.githubusercontent.com/14239715/114956496-01739100-9e2d-11eb-8f78-22a26b3da751.png) We realize that the 35K to 45K Goal success has a tiny sample number thus it's statistically insignificant. The vast majority of Goals, both successful and Failing are between the 1K to 5K Goal bracket. I though it would be interesting to break these down to see if we could get more specific about our recommendation. I created this chart of only the Successful Plays with goals between 1K and 5K. ![Successful_Plays_Pie](https://user-images.githubusercontent.com/14239715/114957262-a9d62500-9e2e-11eb-811d-e9ef38ae95b0.png)







### Challenges and Difficulties Encountered

## Results: 2 Conclusions based on Launch Date
Based on Goals, the client will have the most success with goals between $1000 and $3500. 
Limitations of the Data set, the data set is deeply skewed right, and has the majority of data between 2013 and 2016. This may be a reflection of Kickstarter. It may be a platform that induces lower goals. 

It would be interesting to compare Kickstarter data with other fund raising platforms. It would also be interesting to compare the different types of Campaigns against one another to see which were the highest/lowest fund raising projects the platform supports. 

