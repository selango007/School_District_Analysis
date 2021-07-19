# 1.0 Overview of the school district analysis
The overview of this project is to re-analyze the school destrict report due to some inconsistencies in the results declared by Thomas High School for the 9th graders. The re-nalysis excludes the results for Thomas High School 9th graders from analysis.


# 2.0 Results
Below is the results for the school district upon re-analysing the data excluding the 9th graders from Thomas High School.

# 2.1 How is the district summary affected?
Referring to the district_summary_df, Below are the impact on District Summary:

A. The total students analyzed is reduced by 461 (from 39,170 to 38,709)
B. The Average Math Score before exclusion was 79.0, after exclusion it is reduced to 78.9
C. There is no impact on Average Reading Score.
D. The Math Passing % reduced by 0.2% (reduced from 75.0 to 74.8)
E. The Reding Passing % reduced by 0.3% (reduced from 86.0 to 85.7)
F. The Overall Passing % reduced by 0.1% *reduced from 65% to 64.9%)

# 2.2 How is the school summary affected?
Referring to the per_school_summary_df:

A. The Average Math Score for THS before exclusion = 83.41 and after exclusion = 83.35. The average score for math is reduced by 0.06
B The Average Reading Score for THS before exclusion = 83.84 and after exclusion = 83.89. The average score for reading is increased by 0.05
C. There is a huge impact on the Math Passing %, Reading Passing % and Overall Passing %
                        Math Passing %          Reading Passing %       Overall Passing %
        Before Change   93.27                   97.30                   90.94
        After Change    66.91                   69.66                   65.07

# 2.3 How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
A. Before the change, THS was at the TOP of the list in terms of overall passing % (97.30%) when compared to other schools. 
B. After the changem, THS is right at the BOTTOM of the list in terms of overall passing % (69.66%) when compared to other schools.


# 2.4 How does replacing the ninth-grade scores affect the following:
2.4.1   Math and reading scores by grade
Math and Reading scores by grade didn't have any impact except for the 9th graders for Thomas High School standa "NaN" and couldn't be claculated. Rest of the scores for each grade across other schools remains the same.

2.4.2 Scores by school spending
It is observed that there is no impact on the scores by school spending after excluding 9th graders score for Thomar High School.

2.4.3 Scores by school size
It is observed that there is no impact on the scores by school size after excluding 9th graders score for Thomar High School.

2.4.4. Scores by school type
It is observed that there is no impact on the scores by school type after excluding 9th graders score for Thomar High School.

# Summary
Overall the School District Summary had impact on the following elements:
A. The Average Math Score reduced by 0.1
B. The Math Passing % reduced by 0.2% (reduced from 75.0 to 74.8)
C. The Reding Passing % reduced by 0.3% (reduced from 86.0 to 85.7)
D. The Overall Passing % reduced by 0.1% *reduced from 65% to 64.9%)

It did have big impact on the school summary. However there are no impact to the scores by school spending, school size and school type.
