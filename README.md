# School_District

## Overview of the School District Analysis:
The school board has notified Maria and her supervisor that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards and have turned to Maria for help. She has asked you to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Once you’ve replaced the math and reading scores, Maria would like you to repeat the school district analysis that you did in this module and write up a report to describe how these changes affected the overall analysis.

* Deliverable 1: Replace ninth-grade reading and math scores
* Deliverable 2: Repeat the school district analysis
* Deliverable 3: A written report for the school district analysis (README.md)

## Results:
After replacing the ninth graders' math and reading scores with NaN, the following resulted for Thomas High School:

* The overall passing percentage for Thomas High School dropped to 65%
* The overall passing percentage for the entire district dropped to 64.9%
* Thomas High School as a whole was not longer a top five school

After ommitting the ninth graders of Thomas High School from the calculations, the following changes occured:

* The overall passing percentages of Thomas High School decreased by 0.11%
* The average scores of Thomas High School for math and reading increased by 0.06
* For the spending range of $630 to 644 per student, the overall passing percentage decreased by 0.1%
* School rankings are unchanged. Thomas High School is still the second best performing school in the district with an overall passing rate of 90.63% among their tenth through twelfth graders.

The Effects of School Budget and School Size
* The Average Scores and Passing Percentages do not increase as spending per student increases. Cabera High School, the top performing school in the entire school district, received $68 less per student than Johnson High School, the lowest performing school. This implies that there is no correlation, and there is ommitted variable bias as more relevant factors than funding that decide average student scores.

* When considering school sizes, the "large" schools, or schools over 2,000 students, have the lowest passing percentages and average scores. On the other hand, the difference in performance between "medium" and "small" schools is approximately 1%. Since all District schools in this dataset are characterized as "large" schools, this might be an indication that students in this district learn and perform better in smaller settings.


Charter vs. District Schools
* Charter schools generally performed better than District Schools, as the top five schools with the highest overall passing percentages are all Charter schools. District Schools on the other hand make up the bottom five. Charter schools in this dataset were typically characterized as "small" and "medium" size schools, and have a 36% higher overall passing percentage than District schools.


Average Scores by Grade Level
* After analyzing the average scores for math and reading by grade level for each school, it is found that a students grade level does not affect their scores as much as the school that they attend. The average scores within each school only varries by 1-2% depending on grade level.

## Summary:

Ultimately, it is not possible to determine the extent of the potential academic dishonesty or identify specific indivuals to exclude from the dataset. Due to this, the entire ninth grade of students from Thomas High School have had their scores omitted from the results, which is unfortunate because a full set of data is ideal for the most accurate results.

By replacing the ninth graders' scores with NaN, Thomas High School's overall passing percentages and average scores drastically dropped. The district as a whole has also saw its average math and reading scores decrease. Also the overall passing percentage for students decreased as a result. Furthermore, Thomas High School lost its placement as a top five school within this District. However, after updating the total student counts to exclude the Thomas High School ninth graders and omitting their scores from the dataset, Thomas High School regained its high average scores and retained its position as the number two school in the District
