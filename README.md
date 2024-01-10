# Crowdfunding Analysis

## Overview
This assignment uses Microsoft Excel and covers aspects such as conditional formatting, column creation, pivot tables, stacked column charts, line graphs, written analysis, goal analysis, and statistical analysis for a database of 1,000 sample projects. It involves creating and analyzing various visualizations and presenting cohesive insights in a written report, including conclusions, dataset limitations, and suggestions.

## Languages/ Tools: 
  - Mircosoft Excel

## Conditional Formatting and Column Creation 
In this section, conditional formatting is applied to the 'outcome' column and 'percent funded' column. Six new columns were created for: 'percent funded', 'average donation', 'category', 'sub-category', 'Date Created Conversion' and 'Date Ended Conversion'. 

![conditional-columns](https://github.com/andreaira261/excel-challenge/assets/48165713/ba54b004-7d1b-4fac-868c-9f605c22b853)

## Pivot Tables, Stacked Column Charts, and Line Graphs Creation

In this visualization, a pivot table was created that counts how many campaigns were "successful," "failed," "canceled," or are currently "live" per 'Parent Category'. Additionally, a stacked column pivot chart was created that can be filtered by 'country'. 
![pivot-2](https://github.com/andreaira261/excel-challenge/assets/48165713/0529b6da-9744-4dc3-a996-3f1f3a4e4762)
<br>
<br>

In this visualization, a pivot table was created with a column of 'outcome', rows of 'Date Created Conversion', and values based on the count of 'outcome'. A filter was added based on the 'Parent Category' and 'Year'. A corresponding pivot chart line graph is also displayed. 
![pivot-3](https://github.com/andreaira261/excel-challenge/assets/48165713/4d568320-3f1a-490d-95ef-9167a7b684c2C)

## Analysis Report
Based on the crowdfunding database of 1,000 sample projects: 
-	Most of the campaigns (70%) are categorized under arts and entertainment – namely film & video, music, and theater – and about half of these campaigns (55%) succeeded in meeting or exceeding their initial goal. 
-	The month in which the project is launched may affect the outcome of the campaign as the most significant percent change in successful campaigns occurred between campaigns that were launched in July and August (29% decrease). Meanwhile, the most significant percent change in unsuccessful campaigns occurred between campaigns that were launched in August and September (34% decrease). 
-	The projects that had an initial goal between $15,000 and $50,000 are more likely to succeed as more than 65% of the projects within this range met or exceeded their initial goal.

Some limitations of this dataset include: 
-	The criteria for the “staff_pick” and “spotlight” columns are not given, only a “True/False” value is given. 
-	The dataset only includes the number of backers for each project, without specifying the individual contribution amount from each backer.
-	Based on the blurb of each project, the parent category and subcategory can be broad or there can be some overlap in the categories. 

Other possible tables and graphs that could be created based on this data are: 
-	A pivot table that gives the average count of backers for successful, failed, canceled, and live projects per category. A stacked-column pivot chart that visualizes this table can also be included. 
-	This would give an idea of which categories had more backers as well as the outcome of each project per category based on the backers count. 
-	A table and graph similar to the crowdfunding goal analysis, can also be created and instead of ranges of the initial goal, the ranges are made according to the average donation for each campaign. 
-	This would display if there is a relationship between the average donation to the outcome of the campaigns. It would provide information on whether a certain threshold for the average donation needs to be met or exceeded for a campaign to have a higher likelihood of success.
-	A table with a column of ranges of how many days each campaign were held for (0 to 5, 6 to 10, 11 to 15, … , 55 to 60) and columns for number of projects that were successful, failed, and canceled within these ranges. A stacked chart that visualizes this table can also be included. 
-	This would provide information on the more frequent duration for launching projects and whether the number of days affect the outcome of the campaign. 

## Crowdfunding Goal Analysis 
In this section, calculations of percentages for projects that were successful, failed, or canced per goal range were calculated. A line chart is created to show the relationship between the goal's amount and its chances at success, failure, or cancellation. 
![goal-analysis](https://github.com/andreaira261/excel-challenge/assets/48165713/3b3520c3-8d17-441b-93e6-7b66516e5bc0)

## Statistical Analysis 
In this section, calculations of the mean, median, minimum, maximum, variance, and standard deviation were computed using Excel formulas.
![statistical-analysis](https://github.com/andreaira261/excel-challenge/assets/48165713/f13bdb9b-cc65-4546-b4e5-6fa405301f14)

## Statistical Analysis Report
Since the data for successful and unsuccessful campaigns are both skewed left, the median is a more appropriate measure of central tendency. The median better summarizes the data because it is less affected by outliers and provides a value that is more representative of the typical number of backers for successful and unsuccessful campaigns. 

There is more variability with successful campaigns and this result makes sense because unsuccessful campaigns are more likely to have a lower number of backers, potentially reaching an amount where the project fails to meet its funding goal. In contrast, successful campaigns are more likely to have a greater number of backers and there is no limit to the number of backers the project would have as it has already surpassed a certain threshold for success. 


