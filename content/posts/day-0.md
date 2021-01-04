---
title: "Day 0"
date: 2021-01-03T23:18:33-08:00
---

Today was a light day. I did a bunch of reading for grad school. For context, while working I'm pursuing a Master's in Health Data Science from the University of Denver. One of the huge perks that I'm finding consistently throughout the program is that not only am I learn a lot about data science, but also everything ties in to healthcare in some way.

## Readings
The readings that I focused on today was a literature review of how data mining can be used in healthcare. Data mining is the process of extracting information from data through analysis, machine learning, and other techniques. Every single model and statistical method that was covered in the literature review had an example that connected back to healthcare. This was seen by having a certain type of model 

## SQL
Today, I read two more chapters from *Practical SQL*. The two chapters covered were on statistical methods in SQL and in using dates in SQL.

Pertaining to statistical methods, I learned how to use the `corr(Y, X)` function to measure the Pearson correlation coefficient for two columns. I also learned you can do 2-dimensional regressions using `regr_slope` and `regr_intercept`. `regr_slope` can be used to define a relationship by saying that for every one unit of increase there is the independent variable, there will be a `regr_slope` amount of change in the dependent variable. The R^2 value dictates what percentage of the variation in the dependent variable can be explained by the independent variable. I also learned about the `rank` and `dense_rank` functions and the penchant towards using `rank`.

In terms of dates/times/timestamps/intervals, I learned about the PostgresSQL-specific `date_part`function and how its different from the `extract` function. I also learned a bunch about time zones and how they apply in SQL.

