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
<img width="797" alt="Screen Shot 2019-10-31 at 10 42 12 PM" src="https://user-images.githubusercontent.com/44789805/68000872-cb8a1f00-fc2f-11e9-9726-1fb30540ff71.png">

General information by school and the number of students that took the exams.

#### Math Scores by Grades
<img width="433" alt="Screen Shot 2019-10-31 at 10 37 25 PM" src="https://user-images.githubusercontent.com/44789805/68000711-25d6b000-fc2f-11e9-8827-45237a040efe.png">

From the reading scores we can see the average score that each school got depending their grade.

#### Reading Scores by Grades
<img width="433" alt="Screen Shot 2019-10-31 at 10 37 35 PM" src="https://user-images.githubusercontent.com/44789805/68000730-30914500-fc2f-11e9-8a54-c8b784d07d6c.png">

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

### Questions
1. How is the district summary affected?
2. How is the school summary affected?
3. How does removing the ninth graders' math and reading scores affect Thomas High School's performance, relative to other schools?
4. How does removing the ninth-grade score affect the Math and Reading Scores by Grade, Scores by School Spenging, Scores by School Size, and Score by School Type?

### Observations

#### District Summary
<img width="934" alt="Screen Shot 2019-10-31 at 9 22 26 PM" src="https://user-images.githubusercontent.com/44789805/67999775-d25a6700-fc1a-11e9-8b46-b9b36ebc8d04.png">

The main information such as the Total Schools and Total Students remain the same the difference we see are:
* Average Math Score that decrease from 79 to 78.9
* % Passing Math decrease from 75 to 74
* % Passing Reading decrease from 86 to 85
* Overall Passing scores now is 79

#### Per School Summary
<img width="788" alt="Screen Shot 2019-10-31 at 10 46 07 PM" src="https://user-images.githubusercontent.com/44789805/68001035-5a973700-fc30-11e9-93a8-98c0c9134770.png">

The information remains the same, just Thomas High School should present some changes.

#### Math Scores by Grades
<img width="342" alt="Screen Shot 2019-10-31 at 10 48 25 PM" src="https://user-images.githubusercontent.com/44789805/68001110-a9dd6780-fc30-11e9-859e-be009ce7af66.png">



#### Reading Scores by Grades
<img width="342" alt="Screen Shot 2019-10-31 at 10 49 05 PM" src="https://user-images.githubusercontent.com/44789805/68001133-c11c5500-fc30-11e9-8051-84074817eb17.png">

#### Spending Ranges per Student in the Exams
<img width="829" alt="Screen Shot 2019-10-31 at 9 25 07 PM" src="https://user-images.githubusercontent.com/44789805/67999839-0d5c9a80-fc1b-11e9-8249-2792b6fc2e2e.png">

Spending information remains the same.

#### Relationships Between the Size of the School and the Scores
<img width="764" alt="Screen Shot 2019-10-31 at 9 25 52 PM" src="https://user-images.githubusercontent.com/44789805/67999845-164d6c00-fc1b-11e9-934d-f450838c1793.png">

With the changes made in Thomas High School the Passing Score of Medium Size School Decrease from 95% to 90%.

#### Scores Depending the School Type
<img width="719" alt="Screen Shot 2019-10-31 at 9 26 05 PM" src="https://user-images.githubusercontent.com/44789805/67999854-1fd6d400-fc1b-11e9-8168-c0b605986dd2.png">

The percentage of overall passing of the Charter School Type decrease from 95% to 92%.

### Conclusions

The changes made to the Thomas High School change the results of the Passing Exam. By removing the information just the scores should be affected, the rest of the infomation such as the Speding per Students and the School Size have remain the same. 
