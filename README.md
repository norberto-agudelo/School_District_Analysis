# School District Analysis
Module 4 
## Overview 
Maria, who is the chief Data Scientist of a city school, needs to analyze data about students’ math and reading tests of 15 High Schools on a District using Jupyter Notebooks and Pandas library.

She requires to analyze, report and provide information about performance and trends about it.
After that, she was said that there is some evidence of something wrong with reading and math grades for Thomas High School ninth graders because it seems that data had been altered.

So, the main purpose of this project is replacing those grades for NaN and repeat all the analysis we did for the original data and write up a report “to describe how these changes affected the overall análisis”.

In other words, as a result of this project we have to analyze how the performance on reading and math tests change after probably altered data is changed. We have to review percentages of students who passed math, read and both as well as to analyze performance based on size (number of students), budget and type of High Schools

## Results

o	The district summary before and after changing don’t shows any difference. It could mean that district data has the same trend with or without that data from Thomas High Schools 9TH grade. It could need a deeper analysis but it seems that there are nothing wrong on that grade

 ![image](https://user-images.githubusercontent.com/107591542/178333878-025ccb03-65c5-4974-b762-79610cdad7f7.png)
![image](https://user-images.githubusercontent.com/107591542/178333987-d8c4a404-e803-4f48-b209-27d2952d4ba9.png)


o	School summary for Thomas HS shows a very different result. The original results show a percentage of students that passed math and reading around 90% but when 9th grade is removed the new percentage is 65%. 

The same trend is observed on math (decreased from 93% to 67%) and reading (decreased from 97% to 70%). It could be that there is something wrong in that grade. It might be an error, or there is something illegal in that class. It needs extra analysis


 

 


o	Replacing the ninth grader’s math and reading scores on Thomas High School makes that others get a better position in the schools ranking because its high scores. It could have implications on budget or academics decisions.  

o	Replacing the ninth grader’s math and reading scores on Thomas High School doesn’t make significant changes on scores by grade, school spending, school size and school type. Results on both scenarios show the same figures.

The reason of this is that number of records changed doesn’t impact substantially the size of the size of the data universe under analysis 

## Summary

o	As stated before, changes on Thomas 9th grade make that passing percentages (math, reading and overall) decrease significantly. It means that scores in that grade are really different than others which is no easily understandable. 
o	The percentage of 10th-12th grade students passing math, reading and both from Thomas High School shows high scores. It could mean that 9th grade scores were taken from the mean of others grades
o	Schools with more than 2,000 students (large) have the worst performance on math and overall passing. It could mean that smalls classes are more successful than others.
o	Type of school must be considered to make good decisions. Definitely charter schools performance is highly superior than district schools. The percentage overall passing on district schools is around half of the percentage on charter schools. 


 
