# Doctor_Visits

### An Analysis of the Factors Affecting the Number of Hospital Visitors through the Zero-Inflated Poisson Model

### Problem
Find out how each variable affects the number of Doctor visitors in two weeks.

### EDA
- More than 80% of total data with zero visitors
- People in their 20s are the highest at 1200, and the elderly and teenagers are around 800.
- Most visits did not affect daily life, but a small number of 14-day people were seen as inpatients.
- Overall, there were many low-income people, but the number of low-income insurance subscribers was very small at about 4%.

#### For the number of visitors for two weeks, the Poisson model is generally used, but the zero value of the response variable is close to 80%, and the difference between the mean and variance is more than twice, so the zero expansion Poisson model will be used.
