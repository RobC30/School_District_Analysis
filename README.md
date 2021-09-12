# School District Analysis
In the initial analysis, this project aims to provide crucial performance data of standardized school test results for analysing and reporting. The hopes of this project is to help create strategic decisions at the school & district level on student spending vs. student performace outputs.

However, it has come to our attention that academic dishonesty has been done, and all 9th Grade Math & Reading test results from Thomas High School have been altered. To create a fair environment for strategic decisions on all schools, it has been decided that we are to nullify their test results and reperform our analyis.

# Results
With the consideration of academic dishonesty, a total of __461__ 9th Grade students's test results from Thomas High School were nullified which only compromises __1.17%__ of the total students population.

## District Summary
This resulted in a slightly different district summary results. The _Average Math Score_ went down by __0.01__ point while the __Passing Math Percentage__ went down by __0.02%__. This in turn affected the __Overall Passing Percentage__ of the district, from __65.2%__, it decreased to __64.9%__.

<br>

image insert dist sum old vs new

<br>

## School Summary

insert top 5 school old vs new

For the school summary, the top 5 & bottom 5 performing schools remain the same. After the adjustment, there was a slight decrese in Thomas High School's statistics however it was not enough to affect its ranking. The top performing school is __Cabrera High School__ with an _Overall Passing Rate_ of __91.33%__ followed by __Thomas High School__ at __90.63%__. See image below for direct comparison of changes for __Thomas High School__.

insert ths old vs new

Here we can conclude that Thomas High School's statistcs have changed by roughly __±1%__ on all Math & Reading scores and percentages.

## Math & Reading Scores by Grade
The scores by Grade on both subjects remain the same except for the nullified scores of the 9th Grade students of Thomas High School which is now represented by NaNs.

insert scores by grade old vs new

## Scores by School Spending, School Size & School Type
Replacing the 9th Grade Students' scores did not change the results on these analyses. See images below for new results.

insert new stats


# Summary
Replacing the 9th Grade Students with NaNs resulted in vastly big changes in its statistics. Both its __Average Math & Reading Scores__ remain slightly similar with a discrepancy of less than __0.10__ points. The passing percentages however on both Math & Reading for Thomas High School dropped roughly __28%__ and its _Overall Passing Prencetage_ dropped to __65%__. This is beacuse we basically converted their scores into 0 with the same amount of students. 

For our final analysis however, we removed these students from the sample to be fair on the school's 10th, 11th & 12th Grade students. See images below for comparisons.

insert ths old vs nans





