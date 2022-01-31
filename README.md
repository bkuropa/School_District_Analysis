# School_District_Analysis.
## Overview of the school district analysis
  This analysis is focused on a set of schools and students that correspond to a specific school board evaluating students' abilities to perform in math class and reading skills.  The analysis exists on two levels: the school board level and the individual student level.  There is a detailed analysis of test scores from several perspectives including "private" versus "public" schools, school size, as well as age groups.
  There is also a problem with some of the data that requires cleaning.  This corresponds specifically to one school's grade 9 students who are suspected to be cheating on the standardized tests:  Grade 9 at Thomas High School.  This data must be considered and cleaning efforts must record the changes in the overall scores that are represented in the reports.


## Results
  There is some basic cleaning that was initially done with the data which includes removing all titles associated with students including Dr. and Mrs. for example.  
  When performed properly, the Math Percent drops and is recorded as 74.76 percent.  This was previously in the 80s due to the grade 9 recordings showing up higher in value and therefore boosting the average.  There are 1525 students from that school in total and 1174 grade 10 to 12 students once the grade 9s are removed from the data.  
  
  ![image](https://user-images.githubusercontent.com/19878877/151739045-ab8b2486-7021-44f7-9652-51c5b90b6cd7.png)
![image](https://user-images.githubusercontent.com/19878877/151739084-68fdf844-2a36-4914-98cb-33de27f13250.png)
The above pictures describe the top 5 and the bottom 5 schools and it can be noted that the top schools are exclusively "Charter" schools and the bottom 5 are exclusively "District" schools.  This implies that this factor is a large determinant to performance.  
  Grades were largely similar age-wise from school-to-school which makes sense seeing as students are educated in a similar environment with (often) the same teachers throughout their time there.  
      Programatically, the use of "bins" were a frequent practice in the code and for example, was used to determine the amount of money that is used for each student in the schools (0 - 675).  It is implied through a table there is an inverse relationship between finance and grades but common sense would imply that these two are not correlated well.
      ![image](https://user-images.githubusercontent.com/19878877/151739538-1e6bcc28-8e45-4adb-8d58-30b74a5a0242.png)
  This however is the opposite finding with school size:  The smaller the school, the higher are the grades.  This of course implies that when each teacher has more time with each individual student, higher grades can be achieved.
  ![image](https://user-images.githubusercontent.com/19878877/151739616-2a4ca8d0-52ce-4233-8773-5258fb9de9e1.png)
  There is also a large drop in the % Passing Math overall in the $645 to $675 group from 77% down to 66% which is largely due to the loss of a whole grade that was recorded as being in the high 90s.
  ![image](https://user-images.githubusercontent.com/19878877/151740304-0b0d9092-903d-4b67-8090-65260423d8dc.png)
  Likewise, the medium size graph moved from an Overall Score of 91% down to 85.4% which is a large and noticable drop due to the removal of the 9th graders from this school.
  ![image](https://user-images.githubusercontent.com/19878877/151740395-390fd00c-2155-4d11-9c38-6acace361e54.png)


## Summary
  Overall, the report is supposed to inspire the school board to make changes to the school, the number of students in future schools and what areas to make improvements to.  Likewise, data accuracy is greatly improved as the false data is dropped from the set.

