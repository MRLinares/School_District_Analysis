# School District Analysis

## Overview

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  After an initial analysis, it was discovered that academic dishonesty was evident in the ninth grade of Thomas High School.  A new analysis will consist of removing those datapoints and running the analysis with the new information.

### Data Needed:

* Complete student count with respective identifiers and scores.
* Complete list of schools with respective budgets, total student population size, and school type.
* Total number of students who passed math.
* Total number of students who passed reading.
* Total number of students who passed both, math and reading.
* Totals for passing for each school.
* Overall Total Budget and totals for each individual school.
* Overall average scores for reading and math and averages for each individual school.
* Overall passing percentages for reading, math, and both (reading and math)
* Passing percentages for each individual school.
* Per Capita spending for each school.
* Descriptive statistics for spending to analyze based on spending ranges.


## Results

&nbsp;&nbsp;&nbsp;  After performing the analysis, some changes were noted (Initial analysis images are on top):

![district_summary_pre](https://user-images.githubusercontent.com/108758105/186308885-f46765db-25fe-4ffd-8cc4-563e9181274a.png) ![district_summary_post](https://user-images.githubusercontent.com/108758105/186308977-c6293593-046c-470d-8903-9eb8d96c5fee.png)

After the new analysis, all scores and percentages, as it pertains to the District Summary, save "Avergage Reading Score", dropped marginally.


![school_summary_pre](https://user-images.githubusercontent.com/108758105/186309338-bf36d82d-a1a6-4d1a-9779-aa7fa75dd2f7.png) ![school_summary_post](https://user-images.githubusercontent.com/108758105/186309369-1d23675f-3569-4e41-9ce6-357e58ef94f5.png)

According to the School Summary, the Average Math and Reading Score show marginal changes, but there is a drastic drop in passing percentages by roughly 25 points for each category.

As it relates to performance relative to the other schools, including the ninth grade redacted scores places Thomas HS at the bottom level.


![school_summary_pre](https://user-images.githubusercontent.com/108758105/186309338-bf36d82d-a1a6-4d1a-9779-aa7fa75dd2f7.png) ![per_school_summary](https://user-images.githubusercontent.com/108758105/186311657-339f3fd8-16d2-48e3-99c1-360c30429f5a.png) 

After running the analysis removing the ninth grade data for Thomas High School, the numbers regress near their initial analysis figures.



# RUBRICsch


O

Results: Using bulleted lists and images of DataFrames as support, address the following questions.

&nbsp;&nbsp;&nbsp;How is the district summary affected?

&nbsp;&nbsp;&nbsp;How is the school summary affected?

&nbsp;&nbsp;&nbsp;How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

&nbsp;&nbsp;&nbsp;How does replacing the ninth-grade scores affect the following:

&nbsp;&nbsp;&nbsp;Math and reading scores by grade

&nbsp;&nbsp;&nbsp;Scores by school spending

&nbsp;&nbsp;&nbsp;Scores by school size

&nbsp;&nbsp;&nbsp;Scores by school type

Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.


# END RUBRIC


## Resources
Software: Python, Pandas, Anaconda, and Jupyter Notebook.\
Data: schools_complete.csv, students_complete.csv
