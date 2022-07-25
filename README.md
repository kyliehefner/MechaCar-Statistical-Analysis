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


## T-Tests on Suspension Coils

![image](https://user-images.githubusercontent.com/102445183/180699387-981e3a6d-c7c8-45c3-9b25-7bcb4ab8010b.png)   
The results (shown above) from the one-sample t-test comparing the PSI from the sample of all manufacturing lots and the population mean PSI show a p-value of 0.05734, slightly higher than our 0.05 significance level. Therefore, we cannot reject the null hypothesis, and conclude that there is no statistical difference between the sample mean PSI of all lots and the population mean PSI.

![image](https://user-images.githubusercontent.com/102445183/180699622-a06803d5-675e-4196-8734-5a8c56b94e8b.png)   
The results (shown above) from the one-sample t-test comparing the PSI from the Lot 1 sample and the population mean PSI show a p-value of 0.9982, much higher than our 0.05 significance level. Therefore, we cannot reject the null hypothesis, and conclude that there is no statistical difference between the sample mean PSI of Lot 1 and the population mean PSI.

![image](https://user-images.githubusercontent.com/102445183/180699802-c16a9e75-bb99-4f39-bd16-1884cd36b89e.png)   
The results (shown above) from the one-sample t-test comparing the PSI from the Lot 2 sample and the population mean PSI show a p-value of 0.6115, much higher than our 0.05 significance level. Therefore, we cannot reject the null hypothesis, and conclude that there is no statistical difference between the sample mean PSI of Lot 2 and the population mean PSI.

![image](https://user-images.githubusercontent.com/102445183/180699856-76213b48-be7a-4dc4-855b-929ad266892f.png)   
The results (shown above) from the one-sample t-test comparing the PSI from the Lot 3 sample and the population mean PSI show a p-value of 0.03966, lower than our 0.05 significance level. Therefore, we reject the null hypothesis, and conclude that there is a statistical difference between the sample mean PSI of Lot 3 and the population mean PSI.


## Study Design: MechaCar vs Competition

One test that I would use to compare the performance of MechaCars and their competition is a pair two-sample t-test on the highway fuel efficiency. I would use a pair t-test because there are two populations (MechaCars and the competition's cars) and I would be taking a random sample from each, recording the highway fuel efficiency of each car in the sample. I would then apply a base 10 log to the data in order to normalize it, and use the means of the highway fuel efficiency in the pair t-test.

Null Hypothesis: The difference between the mean highway fuel efficiency of MechaCars and the competitor's cars is equal to zero.   
Alternative Hypothesis: The difference between the mean highway fuel efficiency of MechaCars and the competitor's cars is not equal to zero.
