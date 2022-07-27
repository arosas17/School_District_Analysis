# School_District_Analysis
Thomas High School(THS)


## Overview of the school district analysis

To demostrate what will happen in placing null data into a data set.

Explain the purpose of this analysis.

## Results

Using bulleted lists and images of DataFrames as support, address the following questions.




### District Summary (Complete Data)
![District Summary (Complete Data)](/Images/district_summary_PyCity_Schools.png)

### District Summary (Removed Data)
![District Summary (Without THS 9th Grade Data)](/Images/district_summary_challenge.png)

As a district, the removal of THS's 9th grade data shows a very minimal amount of change. The most effected part of the district summary would be the overall passing rate with as decrease of 0.3%. This is most likely due to the fact that a single from one school is a small part of a rather large data set.  The two tables demostrate a few ideas of what taking THS 9th grade data does to the district as a whole. This would indicate that the THS 9th grade students were generally doing well, grade-wise, and bringing the results up slightly in the disctrict summary.

Overall, the changes when the data was taken out are:
* The average math score decreased from 79.0 to 78.9.
* The average reading score show no diffrence.
* The passing math percentage decreased from 75.0% to 74.8%
* The passing reading percentage decreased from 85.8% to 85.7%
* The overall passing rate decreased from 65.2% to 64.9%.



### School Summary (Complete Data)
![School Summary (Complete Data)](/Images/school_summary_PyCity_Schools.png)

### School Summary (Removed Data)
![School Summary (Without THS 9th Grade Data)](/Images/school_summary_challenge.png)

How is the school summary affected?

Natutally, since the school summary table is devided into schools, THS was the only school effected by the removal of their grades. With this removal of data, a general decrease in passing percentage is shown. The average reading score stayed roughly the same. Overall, only small changes were made to THS data with the removal of their 9th grade information. This would indicate that the 9th grade scores of THS should be very similar to the THS scores as a whole.  

When the data was taken out, it led to changes in THS, such as:

* A small decrease in average math score from 83.42 to 83.35.
* A small increase in average reading score from 83.85 to 83.90
* A small decrease in percentage passing math from 93.27% to 93.19%
* A small decrease in percentage passing reading from 97.31% to 97.02%
* A small decrease in percentage passing overall from 90.95% to 90.63%




### Schools Top Five (Complete Data)
![School Top Five (Complete Data)](/Images/top_five_PyCity_Schools.png)
### Schools Top Five (Removed Data)
![School Top Five ((Without THS 9th Grade Data)](/Images/top_five_challenge.png)

How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

The tables above show the top five schools in the district based on the overall passing percentage. Although the overall percentage of THS decreased to 90.63%, the school still in 2nd place as it did prior to dismissing the 9th grade data. However, it is noted that it nearly dropped to 3rd placed by Griffin High School, who had an overall passing percentage of 90.60%. This would be a difference of approximately 0.03% before THS is dropped a place.



How does replacing the ninth-grade scores affect the following:

### Math Scores by Grade (Complete Data) &nbsp; Reading Scores by Grade (Complete Data)
![Math Scores by Grade (Complete Data)](/Images/math_scores_by_grade_PyCity_Schools.png)   &emsp;&emsp;&emsp; ![Reading Scores by Grade (Complete Data)](/Images/reading_scores_by_grade_PyCity_Schools.png)


### Reading Scores by Grade (Removed Data) &nbsp; Reading Scores by Grade (Removed Data)
&emsp;![Math Scores by Grade (Without THS 9th Grade Data)](/Images/math_scores_by_grade_challenge.png)   &emsp;&emsp;&emsp;&emsp; ![Reading Scores by Grade (Complete Data)](/Images/reading_scores_by_grade_challenge.png)

  Math and reading scores by grade
  
 There are no real changes in terms of data when comparing grades in THS. The only diffrence now is that the 9th grade column has "nan" to say it is not a number. All other grades are uneffected by the change in data.
  
### Spending per Student and Class Performance (Complete Data)
  ![School Spending (Complete Data)](/Images/spending_per_student_challenge.png)
### Spending per Student and Class Performance (Removed Data)
![School Spending (Removed Data)](/Images/spending_per_student_PyCity_Schools.png)
  
### School Size and Class Performance (Complete Data)
![School Size (Complete Data)](/Images/student_body_size_PyCity_Schools.png)
### School Size and Class Performance (Removed Data)
![School Size (Removed Data)](/Images/student_body_size_challenge.png)

   
### School Type and Class Performance (Complete Data)
![School Size (Complete Data)](/Images/school_type_PyCity_Schools.png)
### School Type and Class Performance (Removed Data)
![School Size (Removed Data)](/Images/school_type_challenge.png)
   
Looking at the tables above. When comparing between the complete data set and data set with removed data, we can see no notable difference when comparing between the school performance and spending per student, school size, or school type. This may be due to the fact such little change occurred to the school itself when the data was taken out, that adding it to larger data set that would make it compare more to the original results, making it indistinguishable to the original data.


## Summary
: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

Overall. the changes made by taking out the THS 9th grade data has had a minimal impact on the data. The district was impacted by a decrease in passing percentages. With the data taken out, the district the passing rates went down 0.2% in math, 0.1% in reading, and 0.3% overall. Even as a school, the change in passing rates for THS has been minimal even with the school missing about a quarter of their grades. With the missing data, THS had a decrease rate of passing with a drop of 0.08% difference in math, 0.29% decrease in reading, and a 0.32% decrease in overall passing rates. As mentioned before, this would indicate that the 9th grade data of THS was slightly higher on then THS as a whole. The third noticeable change would be with ranking where THS nearly dropped to third place, dropping from a overall passing rate of 90.95% to 90.63%, with only an approximate difference of 0.03% before losing its ranking in 2nd. Lastly, the last notable change would be the fact no specific information may be determined about the 9th with it taken way. When looking at the "Scores by Grade" tables, it is noticed that "nan" is placed on the information for the 9th grade. If the completed data set that included THS 9th grade data was not already obtained, there would be no way to determine what the 9th grade data could possibly contain.
