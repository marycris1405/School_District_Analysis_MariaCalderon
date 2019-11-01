# School District Analysis
Test Data for Analysis, Reporting and presentation to provide insights about performance trends and patterns. 
Analyze Data on student funding and students' standardized test scores.

# Resources
* Jupyter Notebook
* school_complete.csv
* student_complete.csv

# Insights
Here are the following discoveries on the information provide of school and students. 

#### District Summary
<img width="960" alt="data-4-7-8-district_summary" src="https://user-images.githubusercontent.com/44789805/67728483-9f11a100-f9aa-11e9-8300-e7ccc1d49be2.png"> 

The District summary can provide us information general information as the Total Number of School, Total Number of Students, Average Scores and the Percentage of the students passing the exam. 

#### Per School Summary
<img width="960" alt="data-4-8-7-per_school_summary_format" src="https://user-images.githubusercontent.com/44789805/67728867-1dbb0e00-f9ac-11e9-877f-e941dec47184.png">

General information by school and the number of students that took the exams.

#### Math Scores by Grades
<img width="960" alt="data-4-10-4-ninth_grade_reading_scores_df_formatted" src="https://user-images.githubusercontent.com/44789805/67728942-68d52100-f9ac-11e9-894d-7f592a298bf2.png">

From the reading scores we can see the average score that each school got depending their grade.

#### Reading Scores by Grades 

#### Spending Ranges per Students in the Exams
<img width="960" alt="data-4-11-4-spending-formatted" src="https://user-images.githubusercontent.com/44789805/67728982-93bf7500-f9ac-11e9-9efb-7ca89064d298.png">

In the following image we want to understand the relationship between the spending ranges per students and the results with the exam. 
The school with less spending per student has the higher passing scores. 

#### Relationship Between the Size of the School and the Scores
<img width="960" alt="data-4-12-4-size_summary_formatted" src="https://user-images.githubusercontent.com/44789805/67729014-b2257080-f9ac-11e9-96c1-4218a128c36d.png">

We want to understand if there is any relationship between the passing test on the school size. The small and medium exam has the higher rate (95%) of passing the exam. 
The main reason could be the less students have one class the higher chance that students will concentrate better and present a better exam.

#### Scores Depending the School Type
<img width="960" alt="data-4-13-1-school_type_df" src="https://user-images.githubusercontent.com/44789805/67729041-c8333100-f9ac-11e9-90c1-c9b443f02109.png">

We want to understand as well if the type of school could affect the average score of students.
By the image provided the higher rate of passing exam (95%) has the charter type school.
Charter school usually are accountable for academic results and they have to meet performance goal this main be the main reason that they have higher passing rate.

### Conclusions
We the analysis we understand better the behavior of exams depending the type, size and grade. 
In conclusion we understand that Charter School Type have the higher passing grades, this is because Charter School need to present results otherwise the school will be close.
Smaller classroom could help the student to concentrate better in result provide a better exam result.

## Challenge

It's discovered that the score averages for ninth grades form one high school are incorrect. The information needs to remove the math and reading scores for that high-school, but without removing those ninth-grade students from the analysis.

The best approach for it is the following:
* Remove all the math and reading scores of the ninth graders at Thomas High School.
* Remove the ninth-grade math and reading scores from Thomas High School.
* Keep all other data associated with the ninth-grade students and Thomas High School intact. 

### Observations
1. How is the district summary affected?
2. How is the school summary affected?
3. How does removing the ninth graders' math and reading scores affect Thomas High School's performance, relative to other schools?
4. How does removing the ninth-grade score affect the Math and Reading Scores by Grade, Scores by School Spenging, Scores by School Size, and Score by School Type?
