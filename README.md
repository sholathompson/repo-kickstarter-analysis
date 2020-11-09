# An Analysis of How Different Kickstarter Campaigns Fare In Relation To Their Launch Dates and Their Funding Goals
## Overview of Project
###### Background of this project 
Client met their Kickstarter fundraising goal for their play in a short amount of time and is interested in the relationship between launch dates and fund raising goals. 
###### Purpose of this project
Using the Kickstarter dataset provided, the purpose of this project is to analzed data and visualize data for client to display  outcomes based on goals and outcomes based on launch date. Further, this report will share recomendations for additional graphs and tables that may be completed as an adjunct to this report.
## Analysis and Challenges
###### Analysis
Screenshot 1 shows a pivot table was created to analyze the relationship between outcomes and launch month. As the screenshot 1 shows, of the 1,393 campaigns from Jan- Dec, 839 of them were successful with May and June being the most sucessful months with 111 and 100 successful campaigns respectively.

![Theater Outcomes By Launch Date.png](https://github.com/sholathompson/repo-kickstarter-analysis/blob/main/Theater%20Outcomes%20By%20Launch%20Date.png)
--
Screenshot 2 shows a pivot table created to analyze the relationship between campaign outcome based on funding goal. Results show that the most successful campaigns had funding goals under $1,000 and campaigns over $50000 were more likely to fail.

![Outcomes Based of Goals.png](https://github.com/sholathompson/repo-kickstarter-analysis/blob/main/Outcomes%20Based%20of%20Goals.png)
--
###### Challenges
In the original data set, date was formatted to display date and time serial numbers as date values. I fixed this by formatting the date cells to United States, Gregorian, date formatting
## Results
###### Two Conclusions about Theater Outcomes by Launch Date
The graph below indicates 2 noteable findings. May had the most campaigns launched that were successful and also had the most campaigns launched in general accross all outcomes (sucessful, live, failed and cancelled). Also 47% of campaigns launched in December failed, hence Decemember is the month with the least successful campaigns launched.

![Theater_Outcomes_vs_Launch.png](https://github.com/sholathompson/repo-kickstarter-analysis/blob/main/Theater_Outcomes_vs_Launch.png)
--
###### One Conclusion about The Outcomes Based on Goals
As the graph below indicates the most successful campaigns had funding goals under $1,000.

![Outcomes_vs_Goals.png](https://github.com/sholathompson/repo-kickstarter-analysis/blob/main/Outcomes_vs_Goals.png)
--
## Summary Of The Limitations Of The Dataset
The dataset did not come with a codebook and as a result there were a few variable names that I had to assume what data was represented in that column. Recommendation for qualitative data analysis of "blurb" column as the way that the project was described may affect fundings. Further other graphs could of compared the relationship between number of "backers" (i.e. persons donating to fund the project) and outcome. Also, client could benefit from information on the relationship between spotlight (i.e. whether their kickstarter was promoted on the kickstarter page) and outcome.


