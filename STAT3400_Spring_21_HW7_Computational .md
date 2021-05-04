# Computational Homework #7

**Due by midnight on Monday March 5, 2021**. Answer all of the following problems. These problems should be completed in this notebook (using the R kernel). Computational questions may require code, plots, analysis, interpretation, etc. Working in small groups is allowed, but it is important that you make an effort to master the material and hand in your own work. 

**Note that there is no theoretical portion of the HW this week. Use this time to work on your projects!**

### Problem #1

#### (a) Using the divusa data, fit a regression of with divorce as the response and unemployed, femlab, marriage, birth, and military as predictors. Compute the condition number and interpret its meaning.




```R

```

#### (b) For the same model, compute the VIFs. Is there evidence that collinearity causes some predictors not to be significant? Explain your answer.


```R

```

#### (c) Does the removal of insignificant predictors from the model reduce the collinearity? Investigate.


```R

```

### Problem #2

Use the prostate data with lpsa as the response and the other variables as predictors. Implement the following variable selection methods to determine the "best" model:

1. Backward Elimination
2. AIC
3. Adjusted $R^2$.


```R
library(faraway)
data(prostate)
```

### Problem #3

Use the teengamb data with gamble as the response and the other variables as predictors. Implement the following variable selection methods to determine the "best" model:

1. Backward Elimination
2. AIC
3. Adjusted $R^2$.


```R
library(faraway)
data(teengamb)
```

### Problem #4

Use the divusa data with divorce as the response and the other variables as predictors. Implement the following variable selection methods to determine the "best" model:

1. Backward Elimination
2. AIC
3. Adjusted $R^2$.


```R

```
