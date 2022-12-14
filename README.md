# Codingdemo
Using the Excel workbook in your .zip file, modify and analyze the sample-project data and try to uncover market trends.

This dataset was created by Trilogy Education Services, a 2U, Inc. brand.

Use conditional formatting to fill each cell in the outcome column with a different color, depending on whether the associated campaign was successful, failed, canceled, or is currently live.

Create a new column called Percent Funded that uses a formula to find how much money a campaign made relative to its initial funding goal.
Use conditional formatting to fill each cell in the Percent Funded column according to a three-color scale. The scale should start at 0 with a dark shade of red, and it should transition to green at 100 and blue at 200.

Create a new column called Average Donation that uses a formula to find how much each project backer paid on average.

Create two new columns, one called Parent Category and another called Sub-Category, that use formulas to split the Category and Sub-Category column into the two new, separate columns.

Category Stats

Create a new sheet with a pivot table that analyzes your initial worksheet to count how many campaigns were successful, failed, canceled, or are currently live per category.
Create a stacked-column pivot chart that can be filtered by country based on the table that you created.

Subcategory Stats

Create a new sheet with a pivot table that analyzes your initial sheet to count how many campaigns were successful, failed, or canceled, or are currently live per sub-category.

Create a stacked-column pivot chart that can be filtered by country and parent category based on the table that you created.

The dates in the deadline and launched_at columns use Unix timestamps. Fortunately for us, this formulaLinks to an external site.that can be used to convert these timestamps to a normal date.

Create a new column named Date Created Conversion that will use this formulaLinks to an external site.to convert the data contained in launched_at into Excel's date format.

Create a new column named Date Ended Conversion that will use this formulaLinks to an external site.to convert the data contained in deadline into Excel's date format.

Outcomes Based on Launch Date

Create a new sheet with a pivot table that has a column of outcome, rows of Date Created Conversion, values based on the count of outcome, and filters based on parent category and Years.

Now, create a pivot-chart line graph that visualizes this new table.

Create a report in Microsoft Word, and answer the following questions:

Given the provided data, what are three conclusions that we can draw about crowdfunding campaigns?
What are some limitations of this dataset?
What are some other possible tables and/or graphs that we could create, and what additional value would they provide?
Bonus
Create a new sheet with 8 columns:

Goal
Number Successful

Number Failed

Number Canceled

Total Projects

Percentage Successful

Percentage Failed

Percentage Canceled

In the Goal column, create 12 rows with the following headers:

Less than 1000

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

A table and corresponding graph showing the percentage of projects that are successful, failed, and canceled based on their crowdfunding goal.

Using the COUNTIFS() formula, count how many successful, failed, and canceled projects were created with goals within the ranges listed above. Populate the Number Successful, Number Failed, and Number Canceled columns with these data points.

Add up each of the values in the Number Successful, Number Failed, and Number Canceled columns to populate the Total Projects column. Then, using a mathematical formula, find the percentage of projects that were successful, failed, or canceled per goal range.

Create a line chart that graphs the relationship between a goal amount and its chances of success, failure, or cancellation.
