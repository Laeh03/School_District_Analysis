# School_District_Analysis
Maria is the chief data scientist for a city school district. She has requested an analysis of school spending and standardized test scores. 
Throughout this project i helped the school board and mayor make strategic decisions regarding future school budgets and priorities.
Overall, the goal was to find obvious trends in the school performances.

---

 ## Challenge Overview
Some of the students were caught with academic dishonesty from Thomas High School. 
The school district discovered that the standardized test scores for ninth grade students at Thomas High School were incorrect, and they requested 
for updated data summaries. It was best to only replace the ninth grade math and reading scores at Thomas High School 
while keeping all other data associated with this student group.

## Resources
- Data Source: schools_complete.csv, students_complete.csv
- Software: Python 3.9, Anaconda Navigator 4.10, Jupyter Notebook 6.1.3


### School District Summary
![image](https://user-images.githubusercontent.com/64225504/127786851-6fc1fbe7-1a3a-43bb-8640-00b418928a83.png)

When looking over the average scores and passing percentages among the 15 high schools in the school district, the average math score dropped .1, 
the average reading score stayed the same, the percentage passing math dropped 1%, the percentage passing reading dropped 1%, and the overall passing percent dropped 1%.
The only change in data is with Thomas High School. The overall math and reading passing numbers decreased.


### Top Five Performing Schools
![image](https://user-images.githubusercontent.com/64225504/127786891-b4122836-6fc7-4457-9c49-711d8f786308.png)

### Bottom Five Performing Schools
![image](https://user-images.githubusercontent.com/64225504/127786907-5d7a71d3-8554-4210-b3be-15437cc6cae6.png)


When comparing the performing schools, the score replacements did affect the ranking of the top five performing schools. 
Thomas High School ranked second place in the top five performing schools with a 91% overall passing, and after replacing both math and reading scores, 
Thomas High School was taken out of the top five category. Now they display a 68% overall passing. These changes did not replace Thomas High School 
among the bottom five performing schools, Those ranks remained the same.


### School Spending Summary
![image](https://user-images.githubusercontent.com/64225504/127786930-044d49fc-3472-46ce-97c0-17066bd220e8.png)


When reviewing the School Spending Summary, this data change impacted the spending ranges for passing percentages. 
According to the summary above, The $630-644 bin saw a decrease in the passing percentages since Thomas High School was in that spending range.
Though, interestingly enough the average math and reading scores for that range remained the same.

  
 ### School Size Summary
![image](https://user-images.githubusercontent.com/64225504/127786979-12082b75-ad85-4a45-94e6-d463bfb77296.png)

    
When reviewing the School Size summary, removing the ninth grade scores did not affect the average math and reading scores, 
but it did affect the passing percentages for medium-sized schools (1,000-2,000). 
In this category, % passing math, % passing reading, and % overall passing dropped 6% each. 
Before the data change, the School Size summary showed that medium-sized school had a high performance (91% overall passing) compared to small (90% overall passing)
and large schools (58% overall passing). Given the data change, medium size school are the second in performance (90% overall passing).
  
  
  ###  School Type Summary
![image](https://user-images.githubusercontent.com/64225504/127786986-8219c27b-403b-4af2-b1b2-6c5710fd7eb6.png)


The Charter schools saw a increase in the passing percentages since Thomas High School was in that school type.
Although, the average math and reading scores for that range remained the same.
Removing the scores resulted in a increase in charter school's passing percentages. 
Before the data change, charter schools had very high passing percentages,
after the data change, charter schools now have a 90% passing math, 93% passing reading, 92% overall passing. 
On the plus side, these rates are still far superior when compared to district schools.
