# pandas-challenge

# Written Analysis

[Conclusions](https://github.com/caitlin-hartley/pandas-challenge/edit/main/README.md#Conclusions)


## Written Analysis

### The data contains information on students, including grade, gender, and test scores, as well as schools, including name, type, size, and budget. To begin with, there are some overall statistics calculated, such as the total number of students, total budget, average math and reading scores, and the % of overall passing scores, among other things. 
### Overview of the Data: ![Overview](https://github.com/caitlin-hartley/pandas-challenge/blob/main/images/overall_summary.png)

## School Summary:

### In the school summary, the data is broken down further by school name to look at the type of school, number of students per school, the school budget and capita, the number of students with passing math and/or reading scores, and the overall passing rate. This allows a look into statistics for each school and a school-by-school comparison. 
![SchoolSummary](https://github.com/caitlin-hartley/pandas-challenge/blob/main/images/school_summary.png)

## Highest and Lowest Performers:

### The analysis then looks at the top performing and bottom performing schools based on the % of overall passing grades, which is calculated as the number of students that pass math and reading over the total number of students per school. 
### Top: ![Top](https://github.com/caitlin-hartley/pandas-challenge/blob/main/images/highest_performing.png)
### Bottom: ![Bottom](https://github.com/caitlin-hartley/pandas-challenge/blob/main/images/bottom_performing.png)

## By Grade: 

### The student’s performance at each school is then split up by grade, calculating both average math and reading scores, with the result showing a consistency in scoring across grades 9th through 12th within each school. 

### Math: 
![Math](https://github.com/caitlin-hartley/pandas-challenge/blob/main/images/math_by_grade.png)
### Reading: 
![Reading](https://github.com/caitlin-hartley/pandas-challenge/blob/main/images/reading_by_grade.png)

## Spending and Size:

### The scores are then placed into bins based on spending per student, and then again based on school size. 

### Spending: ![Spending](https://github.com/caitlin-hartley/pandas-challenge/blob/main/images/scores_spending.png)
### Size: ![Size](https://github.com/caitlin-hartley/pandas-challenge/blob/main/images/scores_size.png)

## Types of Schools:

### Finally, the scores are compared based on whether the school is a District school or Charter school. 

### Types: ![Types](https://github.com/caitlin-hartley/pandas-challenge/blob/main/images/school_types.png)

## Conclusions:

### Overall, Charter schools perform better than District schools across all statistics: average math score, average reading score, % passing math, % passing reading, and % overall passing. In % overall passing, Charters school performed significantly better at 90.43% compared to districts schools at 53.67%. 

### Furthermore, small and medium sized schools perform similarly in all categories, whereas large schools perform worse. When looking at budget per student, surprisingly, students perform better when spending ranges per student are lower. Additionally, reading scores remain more consistent across the spending ranges. However, math scores seem to get lower as budget per student increases. Further investigation would be needed to understand what other variables could be correlating with student spending to cause this trend, such as spending going to other activities such as sports. Finally, as mentioned above, grades remain fairly consistent across grades 9-12 within schools. 

