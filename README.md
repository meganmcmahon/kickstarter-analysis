# Kickstarting with Excel

## Overview of Project

Louise’s play Fever came close to its fundraising goal in a short amount of time. Now, she wants to know how different campaigns fared in relation to their launch dates and their funding goals. 

### Purpose

The purpose of this analysis is to provide Louise with data on how launch dates and funding goals are related. By arming Louise with a detailed analysis, she is more likely to be successful in her future kickstarter campaigns!

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

To analyze the data on outcomes based on launch date, I began by adding a "years" column so we are able to add yearly data to our analysis.  Next, I created a pivot table to show campaigns that were successful, campaigns that failed, and campaigns that were cancelled. The pivot table is arranged for rows to show the months of the year and the total number of successful, failed, and cancelled campaigns. I added two filters to the pivot table so that we are able to sort by the parent category of campaigns and by years.

I then created a line graph to visualize the data from the pivot table which shows the relationship between outcomes and launch month. 

### Analysis of Outcomes Based on Goals

To complete the analysis of outcomes based on their funding goals, I created a new sheet and put goal amounts in the first column. I created dollar amount ranges so we could analyze projects in a funding goal range. I then used the COUNTIFS() function to populate columns for the number of successful, failed, and canceled Kickstarter campaigns. Next, I added those numbers together to get a "total projects" column. Then, I found the percentage of successful, failed, and canceled projects. 

Once I had this data I created a line chart to visualize the relationship between the Kickstarter goal amounts and the percentage of successful, failed, and canceled projects.

### Challenges and Difficulties Encountered

A challenge I encountered during the analysis of outcomes based on goals was ensuring that all monetary values were accounted for. At first, I was only using less than/greater than but after noticing the numbers were not adding up, I went back through the equations to add the "=".
I did not run into challenges when analyzing outcomes based on launch dates, however, one could potentially run into challenges trying to visualize this data by not have the correct data on the pivot table. Not filtering by month would make the line graph visual less helpful.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
From the analysis, I can conclude that the months of May-July have the highest number of successful campaigns and the number of successful campaigns drops significantly in November and December. The number of failed campaigns stays within a very small range throughout the year and we are not able to draw a significant conclusion based on failed campaigns.

- What can you conclude about the Outcomes based on Goals?
From the data, I can conclude that the campaign goals that were $1000 to $4999 had the highest number of successful campaigns. A campaign with a goal of $5000 or less is 75% likely to be successful. 

- What are some limitations of this dataset?
The dataset only shows us hard numbers. How many backers, how much money was raised. But there could be many other factors that went in to a successful campaign that would help Louise besides which month had the most successful campaigns. Marketing, graphics, promotions, etc could all have played a bigger role in the success or failure of a campaign.

- What are some other possible tables and/or graphs that we could create?
We could create graphs and tables looking at the number of backers and the average donation. The average donation and average number of people who contribute to campaigns could also provide data that would help Louise set her funding goal at an amount that is most likely to be successful.
