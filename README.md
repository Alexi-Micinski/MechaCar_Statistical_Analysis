# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG

<img width="505" alt="Screen Shot 2022-10-24 at 2 48 21 PM" src="https://user-images.githubusercontent.com/106785377/197626390-bf55e0ce-625b-44f9-a9a1-2ecda82266ae.png">

The intercept, vehicle length, and ground clearance provided a non-random amount of variance to the mpg values in the dataset. In other words, these there variables are statistically unlikely to provide random amounts of variance to the linear model.

The slope of the linear model is not considered to be zero because the vehicle length and the ground clearence have significant linear correlation with the mpg. The other three variables have a random effect on the model.

The linear model has an R-squared value of 0.7149, indicating strong evidence that mpg predictions are determined by the model.

However, this linear model may not predict mpg of MechaCar prototypes effectively because the intercept is significant. This could mean the significant features may need scaling or transforming to improve the model's predictive power. It could also mean that there are other variables that can explain the variablility of the dependent variable that are not included in the model.

## Summary Statistics on Suspension Coils

Total summary:

<img width="405" alt="Screen Shot 2022-10-24 at 3 51 21 PM" src="https://user-images.githubusercontent.com/106785377/197636615-80ae251d-7924-4d7b-a011-3fe902df7a0c.png">

Lot summary:

<img width="551" alt="Screen Shot 2022-10-24 at 3 51 05 PM" src="https://user-images.githubusercontent.com/106785377/197636576-d612820f-f20e-4f45-afe2-62a1ccc7d36b.png">

The variance of the suspension coils is 62.3 PSI according to the total summary. This meets the design specifications. However, by breaking the data down by lot, we can see that Lot3 has a PSI variance of 170.3, which does not meet the design specifications. Lot1 and Lot2 do meet the design specifications as they have PSI variance below 100 PSI.

## T-Tests on Suspension Coils

All lots:

<img width="395" alt="Screen Shot 2022-10-24 at 4 23 25 PM" src="https://user-images.githubusercontent.com/106785377/197641238-02f75d8f-dbee-4e4f-b6be-0c54371f508c.png">

Lot1:

<img width="401" alt="Screen Shot 2022-10-24 at 4 24 48 PM" src="https://user-images.githubusercontent.com/106785377/197641291-f180d8e8-75de-4d51-bfa7-41201b8ce86e.png">

Lot2:

<img width="407" alt="Screen Shot 2022-10-24 at 4 25 05 PM" src="https://user-images.githubusercontent.com/106785377/197641326-a6cf007c-55ae-49ca-9018-5832e120d406.png">

Lot3:

<img width="404" alt="Screen Shot 2022-10-24 at 4 25 24 PM" src="https://user-images.githubusercontent.com/106785377/197641351-75ccde29-3e30-45de-8193-d8b0d2b9f6eb.png">

The p-value is above the common significance level of 0.05 for all lots combined, for lot 1, and for lot 2, meaning there is not enough evidence to reject the null hypothesis. This means that the mean of all three manufacturing lots and the mean of lot 1 and of lot 2 is statistically similar to the population mean. The p-value for lot 3 is below 0.05, meaning there is evidence to reject the null hypothesis. In other words, the mean of lot 3 is not statistically similar from the population mean.

## Study Design: MechaCar vs Competition

Using your knowledge of R, design a statistical study to compare performance of the MechaCar vehicles against performance of vehicles from other manufacturers.

- What metric or metrics are you going to test?
  - Cost
  - Fuel efficiency (MPG)
  - Maintainance (average cost per year)
  - Engine type (gas/electric/other, number of cylinders)
  - Drive type (2WD/4WD)
  - Number of available models

- What is the null hypothesis or alternative hypothesis?
  - First determine which factors are relevant to MechaCar.
  - Null hypothesis: MechaCar is priced correctly based on the relevant factors.
  - Alternative hypothesis: MechaCar is not priced correctly based on the relevant factors.

- What statistical test would you use to test the hypothesis? And why?
  - A multiple linear regression could be used to deterine which factors have the strongest predictive power for MechaCar car prices. 

- What data is needed to run the statistical test?
  - The cost would be the dependent variable and the other metrics/factors would be the independent variables, which would be tested for predictive power of the cost.


