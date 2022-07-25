# MechaCar Statistical Analysis

## Linear Regression to Predict MPG

![image](https://user-images.githubusercontent.com/102445183/180677865-133706a8-a729-485a-990d-0573d1d67952.png)   
According to the summary results of the multiple linear regression (shown above), vehicle length and ground clearance both had significant impact on the miles per gallon of MechaCar prototypes. The probabilities that the coefficients for vehicle length and ground clearance contributed a random amount of variance were very low. Their p-values of 2.6e-12 and 5.21e-08 respectively were well below our 0.05 significance level.

Our overall multiple linear regression p-value is 5.35e-11, well below our 0.05 significance level. Therefore, we can conclude that we should reject our null hypothesis and that the slope of our multiple linear regression is not zero.

Furthermore, our multiple r-squared value of 0.7149 indicates that roughly 71% of the changes in mpg of the MechaCar prototypes is explained using this multiple linear model. At 71%, our model effectively predicts the mpg of MechaCar prototypes.

## Summary Statistics on Suspension Coils

![image](https://user-images.githubusercontent.com/102445183/180697195-81d03aef-1649-45b9-b6e5-f57ada069d37.png)   
The total variance of MechaCar suspension coils is 62.3 pounds per square inch (shown above), which does not exceed the design specifications of a maximum 100 pounds per square inch.

![image](https://user-images.githubusercontent.com/102445183/180697220-c27fcb7a-d965-466c-b32c-6a5a8affca5b.png)   
However, looking at the summary statistics for each lot individually (shown above), Lot 3 shows a variance of 170.3 pounds per square inch, well above the specified maximum allowed. In comparison, Lots 2 and 3 both show very low variances in their MechaCar suspension coils, 0.9896 and 7.469 pounds per square inch respectively.
