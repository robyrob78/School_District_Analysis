# School District Analysis

## School District Analysis Overview
The purpose of this analysis was to analyze the grade data for Thomas High School to determine whether or not there was any academic dishonesty within their records. During this analysis, we replaced the 9th grade math and reading scores(the grades in question) with empty values to see how it affected the rest of the data.

# Results

__The following results reflect the data changes after the 9th grade reading and math scores for Thomas High School were assigned blank values__

* The district summary was affected as follows:
  * Average math score dropped from 79.0 to 78.9
  * The math passing percentage dropped from 75% to 74.8%
  * The reading passing percentage dropped from 86% to 85.7%
  * The overall passing percentage dropped from 65 to 64.9%

* The school summary for Thomas High School was affected as follows
 * The Average math score dropped from 83.42 to 83.35
 * The Average reading score went up from 83.85 to 83.9
 * The overall passing percentage dropped from 90.95 to 90.63
 
## How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
 * Initially, after replacing the scores, Thomas Highschool's passing math %, passing reading % and overall passing % dropped significantly down to 66.9%, 69.7%, and 65.1% respectively. This made Thomas High School, one of the lowest perfomring schools in the district. However, upon recalculating those percentages based on 10-12th grader data and leaving out the blank 9th grader data, Thomas High School's scores rose back up, all above 90%. 
 
## How does replacing the ninth-grade scores affect the following data?
* Math and reading scores by grade: 9th grade scores not availabe for Thomas High School
* Scores by school spending: Thomas High was not affected
* Scores by school size: There was no significant change
* Scores by school type: There was no significant change
 
 # Summary
Initially, upon replacing the 9th grade scores at Thomas High School with NaNs, their scores dropped significantly. Their passing math % dropped from 93% to 67%. Their passing reading % dropped from 97% to 70%. Their overall passing % dropped from 91% to 65%. However, these percentages included the 9th grade students who all had blank values in their scores. This artificially tanked the schools performance. Upon recalculating the school's passing percentages using 10th-12th grade data and eliminating the empty student values that were still being counted, the school's performance was on par with its numbers before we removed the 9th grade data. In conclusion, there is no evidence of academic dishonesty. 

