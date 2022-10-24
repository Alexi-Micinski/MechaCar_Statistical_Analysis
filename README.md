# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG

<img width="505" alt="Screen Shot 2022-10-24 at 2 48 21 PM" src="https://user-images.githubusercontent.com/106785377/197626390-bf55e0ce-625b-44f9-a9a1-2ecda82266ae.png">

The intercept, vehicle length, and ground clearance provided a non-random amount of variance to the mpg values in the dataset. In other words, these there variables are statistically unlikely to provide random amounts of variance to the linear model.

The slope of the linear model is not considered to be zero because the vehicle length and the ground clearence have significant linear correlation with the mpg. The other three variables have a random effect on the model.

This linear model may not predict mpg of MechaCar prototypes effectively because the intercept is significant. This could mean the significant features may need scaling or transforming to improve the model's predictive power. It could also mean that there are other variables that can explain the variablility of the dependent variable that are not included in the model.

## Summary Statistics on Suspension Coils

Total summary:

<img width="405" alt="Screen Shot 2022-10-24 at 3 51 21 PM" src="https://user-images.githubusercontent.com/106785377/197636615-80ae251d-7924-4d7b-a011-3fe902df7a0c.png">

Lot summary:

<img width="551" alt="Screen Shot 2022-10-24 at 3 51 05 PM" src="https://user-images.githubusercontent.com/106785377/197636576-d612820f-f20e-4f45-afe2-62a1ccc7d36b.png">

The variance of the suspension coils is 62.3 PSI according to the total summary. This meets the design specifications. However, by breaking the data down by lot, we can see that Lot3 has a PSI variance of 170.3, which does not meet the design specifications. Lot1 and Lot2 do meet the design specifications as they have PSI variance below 100 PSI.
