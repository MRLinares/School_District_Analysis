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


![Readbygrade_pre](https://user-images.githubusercontent.com/108758105/186323738-a864645b-1b15-4607-87ca-5712734cc794.png) ![Readbygrade_post](https://user-images.githubusercontent.com/108758105/186323793-cbf72524-00be-407a-ba9b-377961395aa7.png)

Both Math and Reading scores by grade (above) reflect that Thomas High School ninth grade scores are no longer being evaluated via the value "nan" which represents the phrase "not a number".

Scores based on spending (below):

![scores_spend_pre](https://user-images.githubusercontent.com/108758105/186323999-ce2f8560-4482-4ea2-a48f-a370780470bb.png) ![scores_spend_post](https://user-images.githubusercontent.com/108758105/186324042-3727fe0c-9bab-4add-adbd-5ed5313b6fc2.png)


Scores based on school size:

![scores_size_pre](https://user-images.githubusercontent.com/108758105/186324152-070c4a10-a658-45be-ba8c-f36c34949de1.png) ![scores_size_post](https://user-images.githubusercontent.com/108758105/186325513-a0c2dbd1-64dd-4698-86a1-b4a02b74822f.png)
 

Scores based on school type:

![scores_type_pre](https://user-images.githubusercontent.com/108758105/186324225-5b4dc280-0a51-4c33-9f96-a41740a9c84b.png) ![scores_type_post](https://user-images.githubusercontent.com/108758105/186325551-6fdf37ae-1a95-4f3b-bcc9-78edf9bb3bdb.png)


The above metrics remain unaffected after new analysis.


# Summary


&nbsp;&nbsp;&nbsp;   After performing the new analysis, it became evident how drastic the effect would be on the data had the redacted ninth grade scores remained in my calculations.  Leaving the scores in would be the equivalent of giving the entire grade zeroes for math and reading which would severly drop the percentages for Thomas High School in all of my measurements so I simply ran all the code with the informtion entirely removed to give a better picture of the true data.

&nbsp;&nbsp;&nbsp;   The first thing I noticed was how little the data changed from the initial analysis once I corrected for the ninth grade data.  While the grade data was removed, the student count was not, so this showed that the "Per Student Budget" didn't change.  The academic dishonesty essentially wasted resources that could have been allocated to other grades and possibly boost their performance.

&nbsp;&nbsp;&nbsp;   Another thing I noted was a marginal drop in all averages and percentages.  In performance comparisons, the margins are so narrow that Thomas High School could possibly fall out of the top 5 or at least drop a level had the academic dishonesty neever occurred.

&nbsp;&nbsp;&nbsp;   The District Summary shows a marginal drop, but it is a view of nearly 40,000 students.  The larger the population size, the more any marginal differences actually point to change, meaning the academic dishonesty had an impact on overall district performance.

: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.






