# Excel Challenge

# GOAL

To analyze a database of 1000 sample projects to uncover any hidden trends

# Change Log

1. check for any null values in the  raw data (checking this as part of data cleaning process). There were no null values found.

2. Used conditional formatting to fill each cell with Red,Green,Yellow and Blue for the outcome failed,successful,live,cancelled.

3. Created a new column called Percent Funded to calculate how much money the campaign made based on the intial funding goal.

4. Used conditional formatting to fill each cell in the Percent Funded column based on the three color scale. The rule was set starting at 0 with a dark shade of red, and it should transition to green at 100 and blue at 200.

5. Created a new column called Average Donation to calculate how much each project backer paid on average.

6.  Split the existing column category and Sub-Category using a formula and the result was updated in the 2 new columns called Parent Category and Sub-Category.

7. Created a new sheet "Parent Category" with a pivot table to analyze the worksheet to count the outcomes(successful, failed, canceled, live) based on the parent category.

8. Created a stacked-column pivot chart that can be filtered by country based on the Parent Category.

9. Created a new sheet "Sub-Category" with a pivot table that analyze the worksheet to count the outcomes(successful, failed, canceled, live) based on the Sub-Category.

10. Created a stacked-column pivot chart that can be filtered by country based on the Sub-Category.

11. Created a new column Date Created conversion to convert the data contained in launched_at column from Unix timestamp to Excel's date format.

12. Created a new column Date Ended conversion to convert the data contained in deadline column from Unix timestamp to Excel's date format.

13. Created a new sheet "LineGraph" with a pivot table with the column of Outcome, rows of date created conversion, values based on the count of outcome, and filters based on parent category and Years. Also created a line graph based on the table.

14. Create a written report in word document.

# Crowfunding Goal Analysis

1. Created a new sheet "Goal Analysis" with 8 columns:

       Goal

       Number Successful

       Number Failed

       Number Canceled

       Total Projects

       Percentage Successful

       Percentage Failed

       Percentage Canceled

2. In the Goal column, create 12 rows with the following headers:

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

3. Used COUNTIFS() formula to count the number of successful, failed, and canceled projects were created with goals within the ranges listed above. Populate the values in the Number Successful, Number failed, Number Canceled columns.

4. Calculate the Total Projects coulmn by adding the values in the Number Successful, Number Failed, and Number Canceled columns.

5. Created a line chart that shows the relationship between the goal amount and its chances of success, failure, or cancellation.

# Statistical Analysis

1. Created a new worksheet "Statistical Analysis" and created one column for the number of backers of successful campaigns and one column for unsuccessful campaigns.

2. Calculate the follwing values for Successful and Unsuccessful campaigns
	mean 
	median 
	minimum number of backers
	maximum number of backers
	variance of the number of backers
	standard deviation of the number of backers
	Mode
	Quartile 1
	Quartile 2
	Quartile 3
	IQR
	Lower Outlier
	Upper Outlier

3. Summarized the statistical analysis report in the same word document along with written analysis report.
