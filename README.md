# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG

### (Questions asked to answer)

1. Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
Both vehicle.weight and spoiler.angle proivded non-random amounts of variance because the Pr(>|t|) values were greated than 0.05.

2. Is the slope of the linear model considered to be zero? Why or why not?
The p-value of our linear regression analysis is 2.277e-11, which is much smaller than our assumed significance level of 0.05.
Therefore, we can state that there is sufficient evidence to reject our null hypothesis, which means that the slope of our linear model is not zero.

3. Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
It effectively predicts MPG because our "Multiple R-squared" value is .7149 which means we are correct ~71% of the time.
We must also be cautious of "overfitting".

* Vehicle Length and Ground Clearance are statistically significant. These variables provide a non-random amount of variance to the MPG values in the dataset.

* The high significance level of the intercept implies that might be other factors that are significant to MPG. Since all available variables in this dataset were already passed in this regression, it can be inferred that additional research and data are necessary to uncover any unknown significant variables.

## Suspension Coils

The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per inch.

The variance of the suspension coils is within specification according to the summary table. 

  * The spec call for 100 and the var is 62.29 which is well within spec.

## Study Design: MechaCar vs Competition

To quantify how "MechaCar" may perform against the competition, a statistical study of metrics that maximize consumer utility can be performed. *In Economics, utility represents how much usefulness or enjoyment a consumer can obtain from consumption of a good or service.*

In this project, metrics that might affect the utility (of a vehicle) are:

* Purchase Price
* Fuel Efficiency (Highway and City)
* Maintenance Cost
* Safety Ratings
8 Horsepower
* Storage Capacity

**Assuming our significance level was the common 0.05 percent, our p-value is above our significance level.
Therefore, we do not have sufficient evidence to reject the null hypothesis, and we would state that the two means are statistically similar.**

The null hypothesis and alternative hypothesis for this proposed study are as follows:
      Ho: MechaCar would have high consumer utility and would perform well against competitors.
      Ha: MechaCar would not have high consumer utility and would not perform well against competitors.

After gathering the necessary data for the metrics listed above, Multiple Linear Regressions would be used to identify the statistically significant variables that affect sales of similar vehicles. 

The performace of MechaCar in these important categories will be compared to the mean performace of competitors through the analysis of variance (ANOVA) test.

If it is found that MechaCar would have high consumer utility and would perform well when positioned against competing vehicles, it is recommended to manufacture MechaCar. Otherwise, if the null hypothesis is rejected, it is not recommend to manufacture MechaCar.
