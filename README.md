# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG
Write a short summary using a screenshot of the output from the linear regression, and address the following questions:

<img width="505" alt="Screen Shot 2022-10-24 at 2 48 21 PM" src="https://user-images.githubusercontent.com/106785377/197626390-bf55e0ce-625b-44f9-a9a1-2ecda82266ae.png">

The intercept, vehicle length, and ground clearance provided a non-random amount of variance to the mpg values in the dataset. In other words, these there variables are statistically unlikely to provide random amounts of variance to the linear model.

The slope of the linear model is not considered to be zero because the vehicle length and the ground clearence have significant linear correlation with the mpg. The other three variables have a random effect on the model.

This linear model may not predict mpg of MechaCar prototypes effectively because the intercept is significant. This could mean the significant features may need scaling or transforming to improve the model's predictive power. It could also mean that there are other variables that can explain the variablility of the dependent variable that are not included in the model.
