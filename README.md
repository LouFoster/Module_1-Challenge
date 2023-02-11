# Module_1-Challenge
# Kickstarting with Excel

## Overview of Project
(As captured from Data Bootcamp Module 1.0.2) 

This challenge is to demonstrate the ability to do the following.  
1.	Import data into a table for analysis.
2.	Apply filters, conditional formatting, and formulas.
3.	Generate and interpret pivot tables.
4.	Calculate summary statistics such as measures of central tendency, standard deviation, and variance.
5.	Characterize data to identify outliers in datasets.
6.	Perform an Excel analysis with visualizations.
7.	Interpret Excel visualizations.

### Purpose
(This module is built around a project that mirrors a real-world scenario that would require data analysis and visualization.)

As a Data Analyst, I am helping an up-and-coming playwright, Louise, who wants to start a crowdfunding campaign to help fund her play. An initial analysis of Kickstarter data was conducted to assist a client (Louise) in determining how different campaigns fared regarding their launch dates and funding goals. The Client, Louise, is hesitant about jumping into her first fundraising campaign and thus has now asked for a follow-up analysis.
For this analysis, we will determine the number of successful, failed, or canceled outcomes based on launch dates by month and the funding goal ranges.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
# Deliverable 1: Analysis of "Outcomes Based on Launch Date Chart"
Initially, I provided Louise (my Client) with a visual summary of the data via pivot tables. (See Kickstart File Worksheet tab labeled "Outcomes by Launch Date" and the related chart, "Outcomes by Launch Date.png," which illustrates the following: 

•	The month that launched the most successful Kickstarter campaigns was May. However, January, June, July, and October all had roughly the same number of failed campaigns launched.

## Overview of all data points for Outcomes by Launch Date 
![ALL_Outcomes_vs Launch](https://user-images.githubusercontent.com/117233641/218183304-dee56d91-2e39-42c7-b5e1-b815d2bda8f7.png)

# Narrowing down to focus to Parent Category "Theater" * due to the Client's interest in the theater data.

In addition, Louise (my Client) would benefit from additional data visualization to see the outcomes of all the categories. As such as the assigned Data Analyst, I need to add visualizations using the same data by creating summary tables, charts, and graphs.

See the Kickstart File Worksheet tab labeled "Theater Outcomes by Launch Date" and the related chart, "Theather_Outcomes_vs_Launch.png," which illustrates the following:

•	By glancing at the data, we can determine that theater is a popular and successful type of campaign overall. Using filters, we can see that theater follows the overall trend: a spike of successful campaigns that began in June but that tapers off by the end of the year. 

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/117233641/218183680-b5ce0488-3702-455e-8c53-ed711c5aa795.png)

### Analysis of Outcomes Based on Goals

## Deliverable 2: Analysis of "Outcomes Based on Goals Chart"
While looking at the theater data as a whole has been helpful, including more data will make my analysis, as Data Analyst, more detailed and thus generate additional insight. Analysis of Outcomes Based on Goals utilizes my Excel skills to help the Client to visualize the percentage of successful, failed, and canceled plays based on the funding goal amount.

•	See the Kickstart File Worksheet tab labeled "Outcomes Based on Goals" and the related chart, "Outcomes_vs_Goals.png," which illustrates the following:

•	The Goal Range of less than 1000 has the largest percentage of successful "plays." In addition, plays with a Goal Range of 45000 to 49999 had the largest percentage of failed "plays."

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/117233641/218184225-28136fe4-7ccb-49db-8186-aef97c2afaaf.png)

### Challenges and Difficulties Encountered
To ensure the accuracy/validation of the data analysis, raw data was filtered to confirm that no canceled plays existed. **(Within Kickstart File, there are several hidden sheets illustrating validation efforts) .

## Results

##- What are two conclusions you can draw about the Outcomes based on Launch Date?

1.	By glancing at the data, we can determine that theater is a popular and successful type of campaign overall. Using filters, we can see that theater follows the overall trend: a spike of successful campaigns that began in June but that tapers off by the end of the year. 
  •	Viewing the line graph, the key months to launch successful theater projects are May and June, which decline through the end of the year.

2.	Data analysis of summary tables, charts, and graphs also shows there are very few canceled theater projects.



##- What can you conclude about the Outcomes based on Goals?

The Goal Range of less than 1000 has the largest percentage of successful "plays." In addition, plays with a Goal Range of 45000 to 49999 had the largest percentage of failed "plays."


##- What are some limitations of this dataset?

There is limited data on canceled theater projects, and there were no examples of canceled plays in the subcategories.


##- What are some other possible tables and/or graphs that we could create?

As an assigned data analyst for the Client (Louise), I would have suggested Applying Descriptive Statistics to our analysis. Statistics provide an unbiased view of the data. Based on these statistics, we can determine the following:

•	Failed Kickstarter campaigns have much higher fundraising goals than successful Kickstarter campaigns.

•	In addition, the mean and median pledged amounts are much lower than the successful pledges, which indicates that failed Kickstarter campaigns are unsuccessful for reasons other than asking for too much money.

•	 The mean of each distribution is around the 3rd quartile, so the data follows similar distributions in each subset.

•	The standard deviations are larger than the mean, which means everything below the mean is considered "close" to the center.

•	The standard deviations are all roughly twice the IQR in each distribution, except in the failed Kickstarters, where the standard deviation is closer to three times the IQR. This stat would indicate that there exist some failed Kickstarters with high goals.

