# MAT502 ADVANCED STATISTICS PROJECT
Analysis to find the relationship between consumption of beverages and the sleeping routine of the individuals


Student Details:
- AU2040004 Priya Jani
- AU2040025 Yagnesh Patel
 

## Motivation

We need a good night's sleep for our physical and emotional health. Yet, how we live our lives, especially the beverages we choose to drink, can significantly impact how well and how long we sleep. Humans consume a variety of liquids, including caffeinated beverages like soda, coffee, and tea. While some people think certain drinks improve their sleep, others believe they disturb their sleep cycles. If there is a connection between them, we want to know about it.
We can learn how certain drinks affect our sleep by understanding the relationship between drinking habits and sleeping patterns, which is an exciting field of research. By looking at this correlation, we may find out which drinks are most likely to disrupt our sleep patterns and which are most helpful for getting a good night's rest.



## Objective

Our main objective is to find out the correlation between beverages and the sleep patterns of individuals. 
Some other objectives are to check whether any column of the dataset behaves randomly or not. Also, apart from narrowing the relationship between beverages and sleep, we would like to check if some other relations come into play while working on the process. 


# Methodology-Sampling Methods and Experiment Design-Hypothesis, Data Collection

- We have used convenience sampling for our case study. Convenience sampling is a non -probability sampling strategy that involves choosing participants based on their accessibility, availability, and desires to participate in a study, making data collection easy.
- We have collected responses from 72 people and asked questions on the basis of our topic.
- We have done data preprocessing and encoding to convert categorical data to numerical values.
- We have done data visualization to get more insights from the data.


## Hypothesis:

- NULL Hypothesis (H0): There is no significant association between tea consumption and an individual's sleeping patterns.
- Alternative Hypothesis (H1): Tea consumption and an individual's sleeping patterns are significantly associated.

## The results:

- Chi-square statistic: 66.88
- p-value: 1.221e-09
- Degrees of freedom = 12

As the p-value<0.01 is highly significant, the NULL hypothesis is rejected, meaning there is a significant association between tea consumption and an individual's sleeping patterns for the data we collected.
Similarly, we did it for all the beverages and found that beverage consumption affects the sleeping routine of an individual.
For all the tests, we can see that p-value is lower than 0.01 for all the tests, highly significant, meaning there is a significant association between beverage consumption and an individual's sleeping patterns for the data we collected.


## Conclusion

- From the first hypothesis test, we can conclude that tea consumption affects the sleeping routine of an individual.
- From the second hypothesis test, we can conclude that coffee consumption affects the sleeping routine of an individual.
- Hence performing a chi-square test of independence on all the beverages,  we can conclude that overall beverage consumption affects the sleeping routine of an individual.
- From the correlation matrix also, we can conclude that beverage consumption affects the sleeping routine of an individual.
- Also, there could be a possible bias in the results as age could be one of the factors affecting the results. As we had more responses from the people of the age group 20-30 years, it can be the case that it may overshadow the other age groups and lead to different results.

