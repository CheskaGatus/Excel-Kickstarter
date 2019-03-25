# Excel-Kickstarter

## Data Analysis on Kickstarter using Microsoft Excel Formulae, Conditional Formatting, Pivot Tables and Charts

Steps taken to uncover some of the market trends of four thousand past Kickstarter projects . 

1) Used conditional formatting to fill each cell in the "state" column with a different color, depending on whether the associated campaign was "successful," "failed," "cancelled," or is currently "live".

2) Created "percent funded" column to uncover how much money a campaign made towards reaching its initial goal. Used conditional formatting to fill/color each cell using a three-color scale. The scale starts at 0 and becomes a dark shade of red, transitioning to green at 100, and then moving towards blue at 200.

3) Created "average donation" column to uncover how much each backer for the project paid on average.

4) Added two new columns, "category" at Q and "sub-category" at R, using formula to split the "Category and Sub-Category" column into two parts.

5) Created Sheet2 with a pivot table to count how many campaigns were "successful," "failed," "cancelled," or are currently "live" per category; and a matching stacked column pivot chart that can be filtered by country.

6) Created Sheet3 with a pivot table to count how many campaigns were "successful," "failed," "cancelled," or are currently "live" per sub-category; and a matching stacked column pivot chart that can be filtered by country and parent-category.

7) The dates stored within the "deadline" and "launched_at" columns are using unix timestamps. Converted and stored these values on new columns called "Date Created Conversion" and "Date Ended Conversion".

8) Created Sheet4 with a pivot table with a column of "state", rows of "Date Created Conversion", values based on the count of state, and filters based on parent category and years; and a matching a pivot chart line graph that can be filtered by category and years.

9) Created Sheet5 with 8 columns: Goal, Number Successful, Number Failed, Number Canceled, Total Projects, Percentage Successful, Percentage Failed, and Percentage Canceled. Made twelve rows with the following headers:
Less Than 1000
1000 to 4999
5000 to 9999
10000 to 14999
15000 to 19999
20000 to 24999
25000 to 29999
30000 to 34999
35000 to 39999
40000 to 44999
45000 to 49999
Greater than or equal to 50000
Used COUNTIFS() formula to count how many successful, failed, and canceled projects were created with goals within those ranges listed above. Populated the Number Successful, Number Failed, and Number Canceled columns with this data. Added up each of the values in the Number Successful, Number Failed, and Number Canceled columns to populate the Total Projects column. Computed for the percentage of projects which were successful, failed, or were canceled per goal range. Used a line chart to visualize the relationship between a goal's amount and its chances at success, failure, or cancellation.

10) Data Analysis report in Microsoft Word states three conclusions about Kickstarter campaigns, limitations of this dataset and some other possible tables/graphs that can be created.
