# Employee Churn - What keeps high-performers satisfied in a company?

## Overview
A company would like to keep their high performers by making sure they are happy while simultaneously get the most productivity from them. Why? High-performers are expensive to keep in the company and it is of interest to the company that To provide insight on this problem, it is of interest to examine some of the attributes of current and past employees. 

Some research questions and deliverables:
* Which people contribute the most for the company?
* What is consider to be a high-performer? How does it compare to average? low?
* For what reason(s) does a high performer leave the company?


## Summary
A random forest classifier was trained using employee data which had attributes such as their satisfaction level, number of projects assigned, average working hours, and salary. From using the default parameters supplied in sklearn, the random foreset classifier is able to correctly predict employee churn with a F1-score of 98% given the fact that the target class was imbalance for this dataset. 

Next, a Shapley analysis was done to look at how the random forest classifier makes the decision. In summary, various factors in this company that causes high-performers to churn are:

1. Large number of projects assigned.
2. Low salary, compared with low-performers.
3. High working hours per month.
4. Spent about 5 or 6 years at the company.

Many of the above factors are associated with low satisfaction level such as #1 and #3.
