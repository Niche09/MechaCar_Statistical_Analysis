## Linear Regression to Predict MPG

<img width="604" alt="image" src="https://user-images.githubusercontent.com/106127571/188497916-5da349e5-19f8-4d4c-af9f-7fcf6b7aa895.png">


<img width="617" alt="image" src="https://user-images.githubusercontent.com/106127571/188497976-2e73d4b2-bea4-418b-9fa3-a075e91f749a.png">

Given the above output it appears that the vehicle ground clearance and the vehicle length are likely to provide non-random amounts of variance
to the model. The slope of the output is not zero; the p-value of 5.35 e-11 is smaller than the assumed significance level of 0.05%. This model does
effectively predict MPG of the prototypes effectively because the r-squared value is 0.7149 which means that approxiamtely 71% of all MPG predications
will be the model.



## Summary Statistics on Suspension Coils


<img width="482" alt="image" src="https://user-images.githubusercontent.com/106127571/188500582-ba71efd7-ecdd-4abb-8747-a0fbf2b41c0c.png">


<img width="593" alt="image" src="https://user-images.githubusercontent.com/106127571/188501048-10e45ff9-8aee-4f8f-a4c5-bdc180cbf60b.png">


When looking at all the coils of the production lot, the variance of the coils is 62.29 PSI, which falls within the 100 PSI requirement.
Most consistently Lot 1 and Lot 2 have variances of 0.98 and 7.47 which are well within the 100 PSI requirement. Lot 3 has a larger variance of
170.29 which is disproportiante to the other lots.


## T-Tests on Suspension Coils

<img width="492" alt="image" src="https://user-images.githubusercontent.com/106127571/189011458-fa01981e-fff8-4755-baa3-91525ba4e666.png">


<img width="554" alt="image" src="https://user-images.githubusercontent.com/106127571/189011833-906dee20-0132-4d37-8c58-4cc6d39582b7.png">


<img width="545" alt="image" src="https://user-images.githubusercontent.com/106127571/189011954-05041d20-765e-4950-aa71-ce45344cb1c9.png">

With regards to all of the manufacturing lots the mean is 1498.78 which is less than the presumed population mean of 1500 pounds per square inch.
Lot 1 has the true sample mean of 1500, so there is no statistical difference between the sample mean and presumed population mean.
Lot 2 has a sample mean of 1500.02 and the sample mean and population mean of 1500 are statistically similar.
Lot 3 has the sample mean of 1496.14, so something in this lot is contributing to it varying from the other two lots.


## Study Design: MechaCar vs Competition


Metrics
---------
-Engine Type - Gas, Electric, Hybrid

-MPG/Gas Effeciency

-Selling Price

-Resale Price/ Value

-Safety Ratings

-Maintenance Costs

Hypothesis
-------------
-Null: MechaCar is priced well given the above metrics.

-Alternative: MechaCar is not priced well given the above metrics. 

Test
-----
In order to determine which factors have the highest correlation with the selling price, a multiple linear regression should 
be used.
