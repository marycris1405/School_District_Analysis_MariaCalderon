# School District Analysis
Test Data for Analysis, Reporting and presentation to provide insights about performance trends and patterns. 
Analyze Data on student funding and students' standardized test scores.

# Resources
* Jupyter Notebook
* school_complete.csv
* student_complete.csv

# Insights
Here are the following discoveries on the information provide of shcool and students. 

<img width="960" alt="data-4-7-8-district_summary" src="https://user-images.githubusercontent.com/44789805/67728483-9f11a100-f9aa-11e9-8300-e7ccc1d49be2.png"> 

For the following image we have the summary of the information provided such as the Total Number of School and Total Number of Students. 

<img width="960" alt="data-4-8-7-per_school_summary_format" src="https://user-images.githubusercontent.com/44789805/67728867-1dbb0e00-f9ac-11e9-877f-e941dec47184.png">

The following chart provide us general information for each school. 

<img width="960" alt="data-4-10-4-ninth_grade_reading_scores_df_formatted" src="https://user-images.githubusercontent.com/44789805/67728942-68d52100-f9ac-11e9-894d-7f592a298bf2.png">

From the reading scores we can see the average score that each school got depending their grade.

<img width="960" alt="data-4-11-4-spending-formatted" src="https://user-images.githubusercontent.com/44789805/67728982-93bf7500-f9ac-11e9-9efb-7ca89064d298.png">

Spending ranges per students depending on the average score and its percentge of passing the exam.

<img width="960" alt="data-4-12-4-size_summary_formatted" src="https://user-images.githubusercontent.com/44789805/67729014-b2257080-f9ac-11e9-96c1-4218a128c36d.png">

We want to understand if there is any relationship between the passing test on the school size.

<img width="960" alt="data-4-13-1-school_type_df" src="https://user-images.githubusercontent.com/44789805/67729041-c8333100-f9ac-11e9-90c1-c9b443f02109.png">

As well we want to understand if the type of school affect the score as well. 

### Conclusions

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
