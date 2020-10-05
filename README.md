# Kickstarting with Excel
Performing analysis on "Kickstarter" dataset to uncover trends.

## Overview of Project
Louise was interested in comparing her fundraising campaign to that of others. Given the data set, I tried to find under what conditions fundraising goals were most likely to be met. One aspect I explored was figuring out what months were most ideal to try and fundraise in. Another stipulation I looking into was the outcome of fundraising based on the goal they initially set. To perform these calculations, pivot tables and pivot graphs helped me depict my findings.

### Purpose
The purpose of this Excel assignment was to determine and predict how Louise's play "Fever" compared in its fundraising goal in respect to different campaigns in relation to their launch dates and funding goals. To determine these results, creating pivot charts and tables were essential to understand the complete picture.

## Analysis and Challenges
The biggest challenge I had during this assignment was trying to determine what variables I wanted to use to create my pivot tables. At times, I wanted to add more data than was required. I also had a few issues with the UNIX Timestamps, but eventually figured out how to display the correct time and eventually convert it into hours. To understand how target amount and month of fundraising impacted how successful the campaign would be, I had to use pivot tables. Pivot tables are extremely powerful, because they allow me to pull and altar certain types of data and create efficient "Pivot Charts". One thing I didn't realize was that "Pivot Charts" allow you to put text in the x-axis, while other charts do not have this same function in excel.

### Analysis of Outcomes Based on Launch Date
Given our data set, I created a pivot table to inspect when various fundraising campaigns kicked off. When I graphed the results and found the percentage of success for the various months, the results seemed fairly clearly. Based off my findings, the warmer months such as "May", "June", and "July" statistically had a much higher chance to reach their goal than in the colder months like "November", "December" and "January". This leads me to believe that during the summer, people tend to give more. Perhaps during the winter time, people are strapped with little cash because of christmas gifts they have to purchase.

![Outcomes Based on Date](resources/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals
Using a line chart, I could see that in general, the higher the goal was set, the more likely the campaign was to fail. However, there was an anomally in the data which segmented this trend between a target of around $30,000 to $40,000 where somehow people managed to hit their goal more often, than the data immediately surrounding them. Those with a fundraising goal of less than $5,000 hit their goal around 70% of the time or more. However, those who set a goal to fundraise for $45,000 or more had over an 80% chance to not hit their goal. In general, the higher the fundraising target was set the more likely the campaign would fail to reach their number.

### Challenges and Difficulties Encountered
Navigating the pivot tables seemed to be a tough interacction for me at first. I was constantly second guessing which variables I wanted to put in or exclude. In addition, several of the formulas, especially the outcomes based on goals with the restrictions added took me a while to fully account for.

## Results
- What are two conclusions you can draw about the Outcomes based on Launch Date?
1) Time of year really does impact the success of a campaign. According to our data, the months of "May" and "June" have the highest chance of meeting their fundraising goal, while months like November, December, and January (the colder months in America and Europe) all have a much lower chance of meeting their goal.
2) The summer months, like May, June, and July all seem to have higher chances for success rates on meeting their funraising goal. One thing I do notice in the dataset, is that the number of data points during these months is much higher too (more events go on during these months). I wonder if the lack of data outside of the summer months can skew the data slightly.

- What can you conclude about the Outcomes based on Goals?
I can conclude companies that shoot for over $45,000 in fundraising or more statistically have a much lower chance of meeting their goal than those with goals of less than amount.

- What are some limitations of this dataset?
In this dataset, we did not exclude outliers. The data could have been trimmed to give us a cleaner final result. In addition, the higher the target goal number went the less data we had. The data across all the fields was not equal in terms of the number of runs we had in each column.

- What are some other possible tables and/or graphs that we could create?
For ease of visualization, we could have included a Box and Whiskers Plot like we did in the Modules. This is a great visual which helps us detect outliers to the dataset. I think it could have been very useful in trimming some of the outlier data.
