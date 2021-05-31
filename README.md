# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG

- An image of the results for the linear regression can be found [here](https://github.com/azarowj/MechaCar_Statistical_Analysis/blob/main/LinearRegression.png)
- Looking at the individual variable p-values of each variable, we can determine which variables provide a non-random amount of variance to the mpg values in the dataset. We can see that the intercept, vehicle length, and ground clearance all provide non-random amount of variance.
- The slope of the linear model is not considered to be zero. The null hypothesis of a linear regression is that the slope is equal to zero. The p-value in our linear regression is 5.35e-11, which is considerably smaller than our assumed significance level 0.05%. Therefore, we reject the null hypothesis, which means that the slope of our linear model is not equal to zero.
- We look to the r-squared value to determine how much of the variability of our dependent variable is explained using this linear model. In this case, the r-squared value is 0.7149. This means that about 71.5% of the variability is explained by the variables in this model. Our model contains 5 variables, but only 2 of them are significant. Even though we have a relatively high r-squared, and a very low p-value, this does not necessarily mean that this model will be good at predicting future values. While this model works well with this particular sample of data, it does not mean that it would work well with a different sample of data. It would be best to continue to work on and refine our regression model.

## Summary Statistics on Suspension Coils

- An image of the total summary dataframe containing the mean, median, variance, and standard deviation can be found [here](https://github.com/azarowj/MechaCar_Statistical_Analysis/blob/main/TotalSummary.png)
- An image of the lot summary dataframe showing the same summary statistics broken down by manufacturing lot can be found [here](https://github.com/azarowj/MechaCar_Statistical_Analysis/blob/main/LotSummary.png)
- When looking at the total summary dataframe, we would say that that the manufacturing data meets the design specification. The design specficiation in question being that the variance must not exceed 100 pounds per square inch. The varinace in total summary data frame is seen to be 62.3. However, when we look more closely, there is cause for concern. Lot 1's variance is approximately 1, which is astonishingly good. Lot 2's variance is about 7.5, which is still beyond acceptable. However, Lot 3's variance is seen to be 170. Lot 3 does not meet the design specification. The variances are so low in Lots 1 and 2 though, that it brings down the total variance to be within an acceptable range.

## T-Tests on Suspension Coils

- An image of the results for the t-test across all manufacturing lots can be found [here](https://github.com/azarowj/MechaCar_Statistical_Analysis/blob/main/AllLotsTTest.png).
- An image of the results for the t-test for manufacturing Lot 1 can be found [here](https://github.com/azarowj/MechaCar_Statistical_Analysis/blob/main/Lot1TTest.png)
- An image of the results for the t-test for manufacturing Lot 2 can be found [here](https://github.com/azarowj/MechaCar_Statistical_Analysis/blob/main/Lot2TTest.png)
- An image of the results for the t-test for manufacturing Lot 3 can be found [here](https://github.com/azarowj/MechaCar_Statistical_Analysis/blob/main/Lot3TTest.png)

## Study Design: MechaCar vs Competition
