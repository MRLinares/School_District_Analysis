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


### Resources
Software: Python, Pandas, Anaconda, and Jupyter Notebook.\
Data: schools_complete.csv, students_complete.csv


## Results

&nbsp;&nbsp;&nbsp;  After performing the analysis, some changes were noted (Initial analysis images are on top or to the left):

![district_summary_pre](https://user-images.githubusercontent.com/108758105/186308885-f46765db-25fe-4ffd-8cc4-563e9181274a.png) ![district_summary_post](https://user-images.githubusercontent.com/108758105/186308977-c6293593-046c-470d-8903-9eb8d96c5fee.png)

After the new analysis, all scores and percentages, as it pertains to the District Summary, save "Avergage Reading Score", dropped marginally.


![school_summary_pre](https://user-images.githubusercontent.com/108758105/186309338-bf36d82d-a1a6-4d1a-9779-aa7fa75dd2f7.png) ![school_summary_post](https://user-images.githubusercontent.com/108758105/186309369-1d23675f-3569-4e41-9ce6-357e58ef94f5.png)

According to the School Summary, the Average Math and Reading Score show marginal changes, but there is a drastic drop in passing percentages by roughly 25 points for each category.

As it relates to performance relative to the other schools, including the ninth grade redacted scores places Thomas HS at the bottom level.


![school_summary_pre](https://user-images.githubusercontent.com/108758105/186309338-bf36d82d-a1a6-4d1a-9779-aa7fa75dd2f7.png) ![per_school_summary](https://user-images.githubusercontent.com/108758105/186311657-339f3fd8-16d2-48e3-99c1-360c30429f5a.png) 

After running the analysis removing the ninth grade data for Thomas High School, the numbers regress near their initial analysis figures.


![Mathbygrade_pre](https://user-images.githubusercontent.com/108758105/186323626-26e4aa37-45e6-46cc-9dbf-5b7f2ab28c93.png) ![Mathbygrade_post](https://user-images.githubusercontent.com/108758105/186323652-ba428d9f-b769-40d0-8c8b-9327e6f8bc72.png)

Math scores by grade


![Readbygrade_pre](https://user-images.githubusercontent.com/108758105/186323738-a864645b-1b15-4607-87ca-5712734cc794.png) ![Readbygrade_post](https://user-images.githubusercontent.com/108758105/186323793-cbf72524-00be-407a-ba9b-377961395aa7.png)

Reading scores by grade

![scores_spend_pre](https://user-images.githubusercontent.com/108758105/186323999-ce2f8560-4482-4ea2-a48f-a370780470bb.png) ![scores_spend_post](https://user-images.githubusercontent.com/108758105/186324042-3727fe0c-9bab-4add-adbd-5ed5313b6fc2.png)

Scores based on spending

![scores_size_pre](https://user-images.githubusercontent.com/108758105/186324152-070c4a10-a658-45be-ba8c-f36c34949de1.png) ![scores_spend_post](https://user-images.githubusercontent.com/108758105/186324176-01571840-84f1-4f93-95cc-62f178f2806b.png)

Scores based on school size

![scores_type_pre](https://user-images.githubusercontent.com/108758105/186324225-5b4dc280-0a51-4c33-9f96-a41740a9c84b.png) ![scores_spend_post](https://user-images.githubusercontent.com/108758105/186324245-61d59ae7-6dc5-4ae3-b00a-64ccbc8890be.png)

Scores based on school type




# RUBRICsch



Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.


# END RUBRIC



