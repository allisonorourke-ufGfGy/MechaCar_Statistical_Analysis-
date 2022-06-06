# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG
![image1](
* In this analysis we are able to make the conclusion that the vehicle length and the ground clearence have a statistical significant influence on the miles per gallon. This is because they have a p-value of less than .05. This means they can be considered statistically significant and can be used to reject the null hypothesis. Alternativly, the vehicle weight, spoiler angle, and AWD have p-values greater than .05 so they are not able to reject the null hypothesis at the 95% confidence interval. Thus, they are not able to be proven to be statistically significant towards the mpg. 
* The p-value for this model is 5.35e-11. This is smaller than the assumed significance level which is .05%. This means that there is sufficient evidence to reject the null hypothesis which in turn means the slope of the line is not 0.
* This linear model has an r-squared value of 0.7149, which means that approximately 71.5% of all mpg predictions will be determined by this model. Essentially, his multiple regression model does predict mpg of MechaCar prototypes effectively.

## Summary Statistics on Suspension Coils
![image2]
![image3]
The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

When looking at the summary for the varience across all lots we are able to see that the variance is 62.29 PSI, which fits within the 100 requirement. Even when it is broken down into the different lots we are able to see that Lot 1 and 2 have variances of 0.98 and 7.47 respectively. Lot 3 however have a variance of 170.29 PSI which is where most of the variance is coming from.

## T-Tests on Suspension Coils
![image4]
With a p-Value of 0.06 there is not enough evidence to support rejecting the null hypothesis. The mean of all three of these manufacturing lots is statistically similar to the presumed population mean of 1500. 
* For Lot 1, it has a p-value of 1 which means there is not enough evidence to support rejecting the null hypothesis and that there is no statistical difference between the observed sample mean and the presumed population mean (1500).
* For Lot 2, there is a p-Value of 0.61 which means the null hypothesis cannot be rejected and the sample mean and the population mean of 1500 are statistically similar.
* For Lot 3, the sample mean is 1496.14 and the p-Value is 0.04, which means we can reject the null hypothesis that this sample mean and the presumed population mean are not statistically different.

## Study Design: MechaCar vs Competition
Using your knowledge of R, design a statistical study to compare performance of the MechaCar vehicles against performance of vehicles from other manufacturers.

To look at the difference between the companies there are a number of different variables we could look at. Some for example could be Saftey rating, maintenance cost annuly, MPG, and resale value. I would like to propose that we do a test to determine how MechaCar does againt other cars.

* Null hypothesis: There is no different between the MechaCar company's vehicale and other manufactures vehicles.
* Alternative hypothesis: The safey rating of  MechaCar company's vehicale is higher compared to other manufactures vehicles.

The statistical test that we would use is the t-test.
