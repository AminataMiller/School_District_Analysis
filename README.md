# School_District_Analysis

## Overview
	Maria, chief data scientist for the school district is responsible for analyzing the student data for the school district. But the school board wants the math and reading scores not considered into the analysis for Thomas High School ninth graders.

### Purpose
	In this analysis we will be working with student data by removing all the ninth-grade students math and reading scores for THS and replace them with NaN and redoing the data frames. 

## Results

* District Summary is affected by the removal of the THS ninth graders data with the math, reading and overall passing percentages drop slightly by less than a half percent.
Below is screenshot for before and after the removal of the THS ninth grader scores:

Before
![image](https://user-images.githubusercontent.com/97865472/160477368-9e650ec3-b2dd-4a94-a61a-8b3f72958656.png)

After
![image](https://user-images.githubusercontent.com/97865472/160477454-f1f07f9c-28f3-44a8-84f5-8ebc201ae0a6.png)

* The school summary for THS is affected in a way that there is a new total number of students being used to perform the analysis which in return affected the overall passing percentage for the school.

Before
![image](https://user-images.githubusercontent.com/97865472/160477555-a5beef1a-1b36-4fc2-b089-3f30cc6afe7d.png)

After
![image](https://user-images.githubusercontent.com/97865472/160477607-d508fef7-e74e-4569-9997-a7a79418fed1.png)

* By replacing the ninth graders’ math and reading scores, THS overall passing percentage increased from 65.07% to 90.58%. but it did not affect its position in the top 5 schools.

Before
![image](https://user-images.githubusercontent.com/97865472/160477857-fda6db9a-805b-4068-9070-154e7902e280.png)

After
![image](https://user-images.githubusercontent.com/97865472/160477708-a24d248e-c5ec-4dcd-a586-4c1ca4c3c970.png)

* replacing the ninth-grade scores affected the following:

> Math and reading scores by grade: the ninth graders have no scores, but the rest of the students were not affected by it.
> Scores by school spending: the spending range bin ($631-645) has a slight drop in its scores and percentage metrics.
> Scores by school size: the Medium (1000-1999) school size was affected with a slight drop
> Scores by school type: the charter school type also had a dropped slightly.
## Summary
	After the reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs, 
> The overall passing percentage went up by 0.1%
> The overall passing percentage at THS went up
> The scores by school size changed
> The scores by school type also changed. 
