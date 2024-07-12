# Validation
A simulated dataset to teach basic principals of selection system validation.

![](firefighting.jpeg)

## Overview

This dataset represents what may be collected in a predictive validation of a selection system for a firefighting department. More details are available in the validation technical report project Word document. The department is currently using a job knowledge test for hiring but has been collecting data for a larger battery including an interview, personality assessments of conscientiousness and emotional stability, and organizational tenure to supplement the job knowledge test. The full list of variables is below, with details available in the codebook:

- Employee ID number
- Year hired
- Sex
- Race/ethnicity
- Age in years
- Veteran status
- Self-reported disability status
- Job tenure in months
- Job knowledge dimensions (3)
- Conscientiousness scale (4 items)
- Emotional stability scale (4 items)
- Interviewer ratings (3)
- Latest annual performance rating

Note, the description is purposefully vague on precise estimates (e.g., $R^{2}$ values) to prevent cheating, but estimates are available to verified faculty on request.

## Intended Usage

This dataset is intended for the instruction of advanced undergraduate or graduate students who have some basic familiarity with R programming and industrial-organizational psychology or are taking a class in personnel decisions or selection.

## Features

- Responses to psychometric inventories are simulated from continuous distributions but formatted as Likert-type format (e.g., 1 = Strongly disagree; 5 = Strongly agree).
- Relationships between most variables are consistent with real-world applications, for example, employee tenure and age are highly correlated.
- Incumbent characteristics align with real-world data, for example, this sample of firefighters had a much higher representation of male employees and is more likely to be military veterans than the general population.
- When possible, relationships between variables are simulated from on meta-analytic $\rho$ estimates.
- Creating a composite of job knowledge test scores to predict performance appraisal ratings results in a $R^{2}$ of ~.1.
- Creating the suggested selection battery to predict performance appraisal ratings results in a  $R^{2}$ of >.3.
- Expectancy charts clearly show a stronger relationship between the battery and job performance vice the job knowledge test alone.
- Few mean differences in the predictors of the suggested selection battery result in mean differences when comparing males vs. females and white vs. all other racial/ethnic groups.
- While there are some statistically significant differences by sex and race/ethnicity, few mean differences are practically significant and some cut in favor of protected classes.
- Adverse impact against is present for females and racial/ethnic minorities when using only the job knowledge test as a predictor of performance appraisal, much lower than the .80 selection ratio standard for females in particular.
- Inclusion of the full selection battery reduces adverse impact against females and racial/ethnic minorities, well above the .80 threshold and close to 1.00 for both sex and race/ethnicity selection ratio comparisons.
- The psychometric properties of multiple-item inventories reflect expected and desirable values, for example, item-total correlations are high.
- The project document includes a recommended grading rubric, a recommended section for splitting the project with one or two partners, and a peer evaluation form.

## Limitations
- Currently there are no missing data, but I plan on introducing it in the next version with a focus on missing data for the psychometric inventories.
- A couple correlations between some demographics and psychometric inventories can be statistically significant, but are modest, this is an artifact of attempting to create precise adverse impact ratios.
- Differential correlations, differential prediction, and Johnson-Neyman regions of significance have not been evaluated, but will be in the next iteration.
- Year hired and tenure were simulated independently, so it's possible an employee could have been hired in 2024 with years of experience; a future version will ensure these are aligned logically.

## License
This work © 2024 by [Andrew J. Thurston](https://ajthurston.com) is licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)