# PyBer_Analysis
Module 5 ride share app analysis

## Project Overview
We were provided ride and city data by PyBer, a ride sharing app company.  The ride-share data spanned a timeframe from January to early May 2019.  Our final projaect was to provide a ride-sharing summary dataFrame by city type and a multiple-line chart of total fares for each city type.  During this study we also created various scatter plots and pie charts to get an idea of what the data looked like as shown below.

![alt text](https://github.com/austin020269/PyBer_Analysis/blob/main/analysis/Fig1.png)

![alt text](https://github.com/austin020269/PyBer_Analysis/blob/main/analysis/Fig6.png)

## Resources
Data Sources provided to analyze and minipulate included:
- ride_data.csv - showing city, date, fare amount and the ride_id
- city_data.csv - showing city, driver_count and city type (urban, suburbal or rural)

Software utilized for this study included: 
- Python 3.7.6 
- Conda 4.9.2 
- Jupyter Notebook 6.1.4
- GitHub account

## Analysis and Workflow
Data for the math and reading scores were removed then we created district and school summary dataframes to manipulte the following:

- Top 5 and bottom 5 performing schools
- Average math score received by students in each grade level at each school
- Average reading score received by students in each grade level at each school
- School performance based on the spending per student
- School performance based on the size of the school
- School performance based on the type of school

The Jupyter notebooks (Python code) for the above analysis was worked through in the following files.

https://github.com/austin020269/School_District_Analysis/blob/main/PyCitySchools.ipynb
https://github.com/austin020269/School_District_Analysis/blob/main/PyCitySchools_Challenge_testing.ipynb

The Challenge at the end of the module which finakized results of the study is here:

https://github.com/austin020269/School_District_Analysis/blob/main/PyCitySchools_Challenge_final.ipynb


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
