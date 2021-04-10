# PyBer_Analysis
Module 5 Ride Share App Analysis

## Project Overview
We were provided ride and city data by PyBer, a ride sharing app company.  The ride-share data spanned a timeframe from January to early May 2019.  Our final projaect was to provide a ride sharing summary dataFrame by city type, a multiple-line chart of total fares for each city type and a final report documenting the work done.  During this study we also created various bubble charts and pie charts to gain familiarity with the data as shown below in our PyBer.ipnyb code (https://github.com/austin020269/PyBer_Analysis/blob/main/PyBer.ipynb) in Jupyter Notebook.

![alt text](https://github.com/austin020269/PyBer_Analysis/blob/main/analysis/code.PNG)
![alt text](https://github.com/austin020269/PyBer_Analysis/blob/main/analysis/Bubble.PNG)

![alt text](https://github.com/austin020269/PyBer_Analysis/blob/main/analysis/Pie.PNG)

## Resources
Data Sources provided to analyze and minipulate included:
- ride_data.csv - showing city, date, fare amount and the ride_id
- city_data.csv - showing city, driver_count and city type (urban, suburban or rural)

Software utilized for this study included: 
- Python 3.7.6 
- Conda 4.9.2 
- Jupyter Notebook 6.1.4
- GitHub account

## Analysis and Workflow
The following flow was generated in our PyBer_Challenge_starter_code_final.ipynb (https://github.com/austin020269/PyBer_Analysis/blob/main/PyBer_Challenge_starter_code_final.ipynb) Jupyter Notebook file.

The ride share data frame was created by:
- retrieving the total number of rides, the total number of drivers and the sum of the fares for each city type.
- calculating the average fare per ride and average fare per driver for each city type.

The mullti-line chart showing total fares for each city type was created by:
- creating a new dataframe showing the sum of the fares for each date.
- resetting the index on the dataframe.
- creating a pivot table with the date as the index, the columns ='type', and values='fare' to get total fares for each city.
- creating dataframe from the pivot table. 
- setting the "date" index to datetime datatype.
- creating a new dataFrame by week 'W' and get the sum of the fares for each week.
- plot the new dataframe using the df.plot() function. 

![alt text](https://github.com/austin020269/PyBer_Analysis/blob/main/analysis/Fig8.png)


## Summary

Specifically, me wanted to answer the following questions for the school district to summarize our study.

1. How is the district summary affected when reading and math scores are dropped fpr 9th graders at Thomas High School?
The % Passing of both math and reading dropped with the average math score decreased by 0.1 points.

2. How is the school summary affected?
The overall math and reading scores decreased for Thomas High School.

3. How does removing the ninth graders’ math and reading scores affect Thomas High School’s performance, relative to the other schools?
Thomas High School moved from 2nd place overall with a passing % of ~92% down to last place with a passing % of ~68%.

4. By removing 9th grade scores the following are effected:

- Math and Reading Scores by Grade - Thomas High School's 9th grade class has no math or reading score data to count. Everything else was unaffected.

- Scores by School Spending - The $630-644 bin saw a decrease in the passing percentages since Thomas High School was in that spending range. Though, interestingly the average math and reading scores for that range remained the same.

- Scores by School Size - The Medium (1000-2000) bin saw a decrease in the passing percentages since Thomas High School was in that school size. Though, interestingly the average math and reading scores for that range remained the same.

- Scores by School Type - The Charter schools saw a decrease in the passing percentages since Thomas High School was in that school type. Though, interestingly the average math and reading scores for that range remained the same.
