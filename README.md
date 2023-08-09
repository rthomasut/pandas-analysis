# School District Data Analysis

As the Chief Data Scientist for the city's school district, our goal is to assist the school board and mayor in making informed decisions about school budgets and priorities. Our initial focus is on analyzing district-wide standardized test results to identify trends in school performance.

## District Summary

We begin by calculating and presenting key metrics for the entire district in a DataFrame:

- Total number of schools
- Total number of students
- Total budget
- Average math score
- Average reading score
- Percentage passing math
- Percentage passing reading
- Overall passing percentage

## School Summary

Next, we summarize essential metrics for each school in a DataFrame:

- School name
- School type
- Total students
- Total school budget
- Per student budget
- Average math score
- Average reading score
- Percentage passing math
- Percentage passing reading
- Overall passing percentage

## Top Performing Schools

Identify and display the top 5 schools based on % Overall Passing:

- Schools sorted by % Overall Passing in descending order
- Results saved in a DataFrame named "top_schools"

## Bottom Performing Schools

Identify and display the bottom 5 schools based on % Overall Passing:

- Schools sorted by % Overall Passing in ascending order
- Results saved in a DataFrame named "bottom_schools"

## Math and Reading Scores by Grade

Analyze average math and reading scores for each grade level (9th, 10th, 11th, 12th) at each school:

- Separate DataFrames for math and reading scores by grade

## Scores by School Spending

Examine school performance based on average spending ranges per student:

- Utilize provided code to create spending bins
- Group schools based on spending range
- Analyze metrics within each spending range
