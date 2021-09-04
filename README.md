# Kickstarting with Excel

## Overview of Project

### Purpose

In this analysis I will examine theatre campaign outcomes based on their launch dates and whether play campaign outcomes were effected by their funding goals. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

To begin my analysis of Outcomes Based on Launch Date, I had to first extract the "Years" from the "Date Created Conversion" column in the dataset. I then proceed to create a pivot table based on "Parent Category" and "Years". Next I had to filter the columns to show only "successful", "failed" and "canceled", along with filtering "Parent Category" to show only the data for "theatre". Using the data in the pivot table I was then able to create a line chart to display the correlation between theatre outcomes and the month it launched.

### Analysis of Outcomes Based on Goals

I started by creating a new sheet to summarize my findings based on Outcomes and Goals. The goal amounts were then grouped into categories ranging from $0-$50,000 with $5,000 increments. I used the COUNTIFS() function to populate the "Number Successful", "Number Failed" and 'Number Canceled" columns. I also included "plays" as the criteria for the "Subcategory" column. 

After using the SUM() function to populate the "Total Projects" column, I was able to calculate the percentage of successful, failed and canceled projects for each row. 

Finally, calculating this data allowed me to create a line chart to display the goal-amount ranges and the percentage of successful, failed or canceled projects.

### Challenges and Difficulties Encountered

A challenge I encountered while coding the COUNTIFS() function in the Outcomes Based on Goals analysis was to ensure that I included "=" in my code. This guaranteed that data within both my upper and lower limits were included in my analysis and displayed correctly within my chart. 

![This is an image](https://github.com/ddigioac/kickstarter-analysis/blob/47f50589c11386c0cc489c01723a98172c575499/Inclusive_Function.png)

## Results

**- What are two conclusions you can draw about the Outcomes based on Launch Date?**

Theatre campaigns launched in May had the highest number of successful outcomes.

Overall theatre campaigns had the highest number of successful outcomes from April through to August.

**- What can you conclude about the Outcomes based on Goals?**

There is a greater chance of a successful campaign if the funding goal is less than $15,000.

There is a greater chance of a failed campaign if the funding goal is greater than $45,000.

**- What are some limitations of this dataset?**

The data is only collected from 2009-2017.

**- What are some other possible tables and/or graphs that we could create?**

Outcomes Based On Average Donation - Is there a correlation between higher donation amounts and a successful campaign?

Backers Count Based on Country - Is there a correlation between where the campaign runs and how many backers it receives. 




