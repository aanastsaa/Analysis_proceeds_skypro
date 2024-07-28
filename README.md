# Analysis_proceeds_skypro
This is one of the projects in the field of data analytics, where it was necessary to calculate the revenue forecast based on a marketing plan.

## Our task: 
Calculate the revenue forecast based on the marketing plan.
- What I need to do?

  I need to calculate the average revenue per 1 student for 1 month and transfer it to the forecast of the number of students.

  ## Steps:
- Calculate revenue from 1 student:
``` total revenue per month / number of students per month ```
- Calculate the average revenue per 1 student
- Calculate "Retention" (the proportion of students who have returned to us since last month)
  1) Add a column of students from last month ``` total number of students per month - new number of students per month ```
  2) ```Retention = students from last month / total number of students per month ```
- Calculate the average "Retention"
- It is necessary to calculate from 01.03.21 to 01.03.22, for this period we have additional information - the number of new students for this period.
- How do I find out approximately the total number of students in the new month? ``` total number of students per last month * average "Retention" + the number of new students ```
- Estimated revenue = ```total number of students per month * the average revenue per 1 student ```
