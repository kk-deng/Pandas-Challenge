# PyCitySchools - A Pandas Challenge

## Background
We have two csv files to analyze: `School district info` and `Student score summary`. A final report was generate to show multiple tables as per requirements.

## Report Details

### District Summary
This shows district's key metrics.

### School Summary
This includes key metrics about each school.

### Top Performing Schools (By % Overall Passing)
This includes top 5 performing schools based on % Overall Passing.

### Bottom Performing Schools (By % Overall Passing)
This inclues bottom 5 performing schools based on % Overall Passing. 

### Math Scores by Grade
This part lists the average Math Score for students of each grade level (9th, 10th, 11th, 12th) at each school.

### Reading Scores by Grade
This part lists the average Reading Score for students of each grade level (9th, 10th, 11th, 12th) at each school.

### Scores by School Spending
Based on average Spending Ranges (Per Student), a school's performance varies due to the difference of budgets.

### Scores by School Size
Based on different school size (Small, Medium, Large), a school's performance varies due to the difference of sizes.

### Scores by School Type
Based on the school type (Charter vs. District), a school's performance varies.

# Observable Trends
1. According to the report of Top/Bottom Performing Schools (By % Overall Passing), we can see that schools with higher overall passing rates (>90%) are all **Charter schools**. On the contrary, schools with lower overall passing rates (<54%) are all **District schools**.

<img src="https://github.com/kk-deng/Pandas-Challenge/blob/main/PyCitySchools/Images/1.%20top%20schools.png?raw=true" alt="1-top-schools" border="0"></a>

2. From the report of Math/Reading Scores by Grade, we can see that the math grades have **no significant relationship with the grade level** of students in the same school.

<img src="https://github.com/kk-deng/Pandas-Challenge/blob/main/PyCitySchools/Images/2.Graders.png?raw=true" alt="1-top-schools" border="0"></a>

3. From the report of Scores by School Spending, as the spending budget per students increases (from $584/student to $675/student), the overall passing percentage of math and reading decreases (from 90% to 54%).

<img src="https://github.com/kk-deng/Pandas-Challenge/blob/main/PyCitySchools/Images/3.Budget.png?raw=true" alt="1-top-schools" border="0"></a>

4. From the result of Scores by School Size, when the school has students more than 2000, the overall passing percentage drops from around 90% to 58%.

5. From the result of Scores by School Type, Charter schools have much higher overall passing percentages than District schools. 
