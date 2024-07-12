# Validation
A simulated dataset to teach the principals of selection system validation

AJ Thurston

This work © 2024 by [Andrew J. Thurston](https://ajthurston.com) is licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)

## Overview

Note, purposefully vague on numbers

## Intended Use

selection battery based on composites of job knowledge test scores, interview rating composite, conscientiousness and emotional stability composites, and tenure

## Features

- Relationships between most variables are consistent with real-world applications, for example, employee tenure and age are highly correlated.
- Incumbent characteristics align with real-world data, for example, this sample of firefighters had a much higher representation of male employees and is more likely to be military veterans than the general population.
- When possible, relationships between variables are simulated from on meta-analytic $\rho$ estimates.
- Creating a composite of job knowledge test scores to predict performance appraisal ratings results in a $\R^2$ of ~.1.
- Creating the suggested selection battery to predict performance appraisal ratings results in a  $\R^2$ of >.3.
- Few mean differences in the predictors of the suggested selection battery result in mean differences when comparing males vs. females and white vs. all other racial/ethnic groups.
- While there are some statistically significant differences by sex and race/ethnicity, few mean differences are practically significant and some cut in favor of protected classes.
- Adverse impact against is present for females and racial/ethnic minorities when using only the job knowledge test as a predictor of performance appraisal, much lower than the .80 selection ratio standard.
- Inclusion of the full selection battery reduces adverse impact against females and racial/ethnic minorities, well above the .80 threshold and close to 1.00 for both sex and race/ethnicity selection ratio comparisons.
- The psychometric properties

## Limitations
- Currently no missing data
- Correlations between some demographics and 