# school_district_analysis

## Overview of Project

The purpose of this project is to re-analyze the student funding and student standardize test scores due to evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders. This analysis will be used to inform discussions and strategic decisions at the school and district level. 

The various data provided will be analyzed and presented to provide insights about performance, trends and patterns. 

## School District Analysis Results

The data preparation utilizes Pandas and Jupyter to perform calculations and analysis by creating DataFrames and various functions to explore the data. This helped to create multiple DataFrames to use for future analysis. Insight are generated on the <a href="PyCitySchools_Challenge.ipynb">PyCitySchools script</a>. 

**How is the district summary affected?**

After altering the data to disregard the reading and math grades from Thomas High School ninth graders, the overall district summary was only slightly affected. 

This is the original data:
<img src="DistrictSummary_Original.png" width="400">

This is the altered data:
<img src="DisctrictSummary_New.png" width="400">

The Average Math Score, % Passing Math, % Passing Reading and % Overall Passing decreased by 0.1% to 0.3%. Whereas the Average Reading Score was not affected. 

**How is the school summary affected?**

All school data remained the same except for Thomas High School. The Average Math Scores and Average Reading Scores are barely effected and only change by ~0.1%.

The % Passing Math, % Passing Reading and % Overall Passing are also barely effected and only changing by 0.1-0.3%

This is the original data:
<img src="SchoolSummary_Original.png" width="400">

This is the altered data:
<img src="SchoolSummary_New.png" width="400">

**How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?**

In the original and new dataset based on the % Overall Passing score, Thomas High School was ranked 2nd out of the 15 schools.

In the original dataset, the % Overall Passing score was 90.95%, whereas in the new dataseet, the score was 90.63%. 

This pushes Thomas High School closer to the 3rd-5th place schools, that all range from 90.54% to 90.60%.

**How does replacing the ninth-grade scores affect the following:**
Math and reading scores by grade
Scores by school spending
Scores by school size
Scores by school type

## Summary
