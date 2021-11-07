# Kickstarter-Analysis

## Overview of the Project
- The project was assigned because of how quickly Louise's play, *Fever* was reaching was approaching the fundraising goal. Due to the success of the play, Louise wanted more information about her play fundraisers only. She specifically requested information about play fundraising outcomes with respect to what time of the year the fundraiser was held, and how successful her play outcomes were based on the goal amount set.
- To satisfy her request, I created a pivot table showing the number of theater fundraising campaigns that were either sucessful, canceled, or failed, based on the month the campaign was launched. I created a second spreadsheet that compared the number of successful, failed, and canceled plays based on goal amounts. 
- 
### Purpose
-The purpose of this project was to analyze the success of Louise's theater fundraisers based on the launch date's time of year as well as the success of her play fundraisers based on the how high the goal was set. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
-By filtering the theater fundraising outcomes based on their launch dates using a pivot table, I was able to refine Louise's data down to only 12 rows and 5 columns. This made the data much easier to represent visually. 
-The data from the pivot chart shows that her most successful launch date was in the month of May, with a total of 112 successful fundraisers versus 52 that failed. The data shows that her least successful month for theater fundraisers is in December, with 37 successful campaigns and 35 failed. 

### Analysis of Outcomes Based on Goals
-By classifying Louise's successful, failed and canceled play goals into ranges, I was able to see that most of her successful campaigns had lower goals set of <5000 of the country's currency. The percentage of successful fundraisers begins to drop off until 15000 to 19999 where the percentage of successful campaigns drops below the failed campaigns. The percentage of successful campaigns increases over 50% between 35000 and 44999 before dropping again to near zero.

### Challenges and Difficulties Encountered
-Using the pivot table to find the outcomes based on their launch dates was easy and efficient. The difficulties began when finding the outcomes based on goals. Where the general formula could be copied and pasted down the rows, the countif criteria had to be manually changed each row to satisfy the range, proving to be a tedious task. It was also easy to make a mistake because there isn't a way to see two spreadsheets at once so accidentally setting the wrong criteria range could easily lead to an error in the final product. 

## Results
- What are two conclusions you can draw about the Outcomes based on Launch Date?
The line graph shows that most successful theater fundraisers occured during the summer months of May, June and July, with May being the most successful month and linearly declines through through the summer. 
The line graph shows that her least successful campaigns are launched during the fall/winter months of October, November and December. 

-What can you conclude about the Outcomes based on Goals? What are the limitations of this dataset?
Plotting the goal ranges with respect to the percentage of successful fundraisers could be misleading. By looking at the graph alone, the goals set between 15000 to 19999 appear to be pretty positive with a 67% success rate, but there are only a total of 9 plays with goals set within this range. This skews the data into making the range seem much more successful because there are too few goals. One unsuccessful goal in this range can significantly drop the percentage down. 

- What are some other possible tables and/or graphs that we could create?
I would create a table that compared amount raised to the amount pledge, to find the expected amount to be raised based on how much was pledged. I could also graph the outcomes based on pledged. 
I could also form the same tables/graphs of the outcomes based on launch date for every subcategory and find out which category had the highest success rates for each season in the year. This would allow Louise to optimize her fundraisers by focusing on plays during the summer, and another category during different seasons.
I could set up a pivot table that showed the category's success rate across years instead of months to see if certain categories have lost or gained popularity over time.
