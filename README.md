# Kickstarter_Analysis_Challenge

## Overview of Project

Our client, Louise, would like to understand more details on Kickstarter campaigns and would like to leverage our prior analysis on Kickstarter campaigns and gain insight for her play campaign.  The goal of this project is to examine theater Kickstarter campaigns and their launch dates to determine if there is a preference better time to launch a successful campaign.  In addition, an examination of the outcomes relative to goals will be analyzed as well.  

### Purpose
  The purpose of the project is to build off existing work for the client.  The focus of this analysis is to examine the Kickstarter dataset for theater campaigns.  The focus will be to determine trends or relationships on the success of failure of a theater campaign based on the timing of its launch and/or fundraising goals.  Understanding when is the best time to launch a successful campaign and setting a goal expectation to lead to the highest chance of a successful outcome.

### Analysis of Outcomes based on Launch Date
  This work was performed using an Excel analysis.  The workbook is located here [Kickstarter_Challenge](Kickstarter_Challenge.xlsx) and are available for review.  The worksheet Theater Outcomes by Launch data in the referenced workbook, contains a pivot table of filtered Kickstarter campaigns.  The launch date was converted into a date from it's sourced UNIX time format.  A years column was created using the years function was extracted on this converted date.   The pivot table uses the years and Parent Category from the Kickstarter sheet.  The filter is set to only look at the theater campaigns.  The rows are the months and the columns in the table reflect the number of outcomes of only the successful, failed, and canceled theater campaigns.  Live campaigns were not shown as their outcomes are unknown.   This data is then used to create a chart of the campaign outcomes vs the month the campaigns were launched.  This chart is located below in Figure 1.

Figure 1
![Theater_Outcomes_vs_Launch_Date](Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes based on Goals

  This work was performed using an Excel analysis.  The workbook is located here [Kickstarter_Challenge](Kickstarter_Challenge.xlsx) and are available for review.  The worksheet Outcomes based on Goals data in the referenced workbook, contains a table of filtered Kickstarter campaigns.  Goals were split into 12 different provided fundraising target categories listed below:
  
  1)less than 1000
  2)1000 to 4999
  3)5000 to 9999
  4)10000 to 14999
  5)15000 to 19999
  6)20000 to 24999
  7)25000 to 29999
  8)30000 to 34999
  9)35000 to 39999
  10)40000 to 44999
  11)45000 to 49999
  12)greater than 50000

  Utilizing Excel's countifs function, the subcategories of plays were counted based on their success, failure, and canceled designation for each of the fundraising goals listed above.  The total sum of the projects in each goal range were summed and then percentages for the successful, failed, and canceled outcomes were calculated.  Please refer to the


Figure 2
![Outcomes_based_on_Goals](Outcomes_vs_Goals.png)


### Challenges and Difficulties encountered


### Results

In analyzing the theater outcomes vs launch date in Figure 1 above, two things appear to be apparent.
  1. Late Spring and Early summer months of May, June, and July have the highest amount of successful theater campaigns, with May being the best month.  
  2. The total number of failed campaigns per month don't change significantly.  There is an small increase in the summer months  with the exception of October. 








