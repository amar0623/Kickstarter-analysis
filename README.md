# Kickstarting with Excel

## Overview of Project

For this project, we are analyzing the data of over 4,000 kickstarter campaigns to uncover trends.

### Purpose

The purpose of this analysis is to look for trends in the data to see if there are specific factors that affect the kickstarter campaign's success or failure.
The analysis of these trends will help Louise, an up-and-coming playwrite, model her own campaign to set her up for success.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

The outcomes based upon launch date were filtered for all "theater" kickstarters, and sorted by month over the span of a few years.
The campaigns are in order of successful campaigns, failed campgaigns, and canceled campaigns. 
A majority of the total campaigns were successful, with May being the overall most successful month to launch a campaign. 
The least successful month to start a campaign is December.
While May has the highest number of successful campaigns, it is also the month with the highest amount of failed campaigns. 
October is a close second for number of failed campaigns.

### Analysis of Outcomes Based on Goals

The outcomes based upon goals were filtered specifically for "plays", and sorted by 12 ranges of goals anywhere between $1,000 and over $50,000. 
The most successful campaigns either had a goal of less than $4,999 or a goal of between $35,000 to $44,999.
Campaigns failed the most when they had a goal of $45,000 to $49,999.
There were no canceled kickstarter campaigns for plays.

### Challenges and Difficulties Encountered

The most difficult challenge during this analysis was using the "=Countifs" function for the goal ranges for the Outcomes Based on Goals data.
While inputting the "=Countifs" function, excel did not automatically place a "$" before every column value in the formula, so the formula kept giving an error.
![image](https://user-images.githubusercontent.com/96644316/159152724-2ce3e164-9628-42c2-ae65-fafb2e0c8224.png)
I watched the tutorial video on canvas, and the example had $ before each column for the function criteria range.
![image](https://user-images.githubusercontent.com/96644316/159152692-157cdae3-6fe6-4309-a755-e7ae11af85dd.png)
The remedy was found due to comparing the canvas instructional video and what excel was automatically filling in my fomula bar for the same function. 
I googled what a $ does, and the $ causes excel to keep a static row or column, which was needed for the formula to run properly.

## Results

#### - What are two conclusions you can draw about the Outcomes based on Launch Date?
The first conclusion is that May is the most successful month to start a campaign. 
Even taking into consideration that May also has the highest number of failed campaigns, there were way more successful campaigns in May than any other time of the year.

The second conclusion is that December is the worst time of the year to launch a campaign.
December has the lowest number of successful campaigns, and a comparitively similar amount of failed campaigns as well.

#### - What can you conclude about the Outcomes based on Goals?
Campaigns are much more likely to be successful with a goal of less than $5,000. The failure of the campaigns is much more likely with a goal of over $20,000.

#### - What are some limitations of this dataset?
Neither analysis performed was filtered by country, which could be a limitation based on cultural trends. 
For Louise to more closely mirror succesful campaigns, filtering to the country the play will be in would help find trends of that country.
An example could include how the least successful month was December, but this could be because a huge holiday in primarily Christian countries would be Christmas, and people celebrating that holiday may be less likely to attend a theater during this time.
For the outcomes based on goal, there were significantly less campaigns that had goals of more than $20,000. Small sample sizes do not reflect the total data well.

#### - What are some other possible tables and/or graphs that we could create?
One useful table or graph we could create might track how many campaign backers there were for a given month out of the year, and how much on average they pledged.
This could help Louise anticipate which month out of the year brings in the most money.
