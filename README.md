# **pandas-challenge**

## Background 
In this assignment, I used the concepts learned in Jupyter to complete the Pandas Challenge: PyCitySchools. The tasks were presented with real-world data for a city's school district. In the capacity given, I was to help the school board and mayor make strategic decisions regarding future school budgets and priorities. I was asked to analyze the district-wide standardized test results. I was given access to every student's math and reading scores and other key information within the dataset [schools_complete.csv](https://github.com/maddieemihle/pandas-challenge/blob/main/PyCitySchools/Resources/schools_complete.csv) and [students_complete.csv](https://github.com/maddieemihle/pandas-challenge/blob/main/PyCitySchools/Resources/students_complete.csv). My goal was to aggregate the data to showcase the obvious trends in school performance using skills learned in Pandas/Jupyter, such as: scripting, converting dependencies, analyzing, cleaning, and calculations. 

All data for this dataset was generated by _edX Boot Camp LLC_, and is intended for educational purposes only. 

### District Summary 
In this section, I was tasked to perform the necessary calculations and create a high-level snapshot of the district's key metrics in a DataFrame. 

    * Total number of unique schools
    * Total students 
    * Total budget 
    * Average math and reading scores
    * % passing math, reading, and overall passing 

### School Summary 
In this section, I was tasked to perform the necessary calculations and create a DataFrame that summarizes key metrics about each school. 

    * School name & type
    * Total students 
    * Total school budget
    * Per student budget 
    * Average math and reading scores
    * % passing math, reading, and overall passing
    * Highest-performing schools (by % overall passing)
    * Lowest-performing schools (by % overall passing)
    * Math and reading scores by grade 
    * Scores by school spending 
    * Scores by school size
    * Scores by school type 

## Observable Trends and Conclusions 
The PyCity Schools Data provides a high-level overview of key metrics for an entire school district and individual school summary. 

### District Summary: 
The total number of unique schools in the district is 15, with a total student population of 39,170. The total budget is $24,649,428. The average math score across the district is 79.0, while the average reading score is 81.9. The percentage of students passing math is 75.0%, and the percentage of students passing reading is 85.9%. The overall percentage of both combined math and reading is 65.2%. 

### School Summary: 
The school summary breaks down each school type, total students, total school budget, per student budget, average math and reading scores, and passing percentages (math, reading, overall). The detailed breakdown overall allows for comparisons between individual schools to give a better insight into how each functions independently and compared to others in the area. 

### Overall Summary: 
Based on the data and calculations performed in this challenge, the analyses made helped in making data-driven decisions to improve educational outcomes across the district. When looking at all the data, there are some observable trends and conclusions that can be seen. 

1. Impact of School Spending: 
    * Schools with higher spending per student do not necessarily have higher average scores or passing percentages. Some schools with moderate spending sometimes outperform those with higher spending. This could draw the conclusion that spending and monetary reserve do not always mean better teaching quality, school management, or student success. 

2. School Size and Performance: 
    * School size and performance tend to correlate. Smaller schools mostly have higher average scores and passing percentages compared to the larger schools. One conclusion for this could be that smaller schools have more personalized attention from teachers than larger schools with a higher student-teacher ratio. 


### Software Used: 
Coding was performed via Visual Studio Code using a Jupyter environment. 

### Refrences 
Data generated by _Mockaroo, LLC_(2022). Realistic Data Generator. Data for this dataset was generated by _edX Boot Camps LLC_, and is intended for educational purposes only.
