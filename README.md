# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG

### Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
* Vehicle Length and Ground Clearance
   
### Is the slope of the linear model considered to be zero? Why or why not?
* No, because our p-value is much lower than 0.05 and we can reject the null hypothesis. 
    
### Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
No, because the distribution of the residuals is too far apart.

![deliverable01](https://user-images.githubusercontent.com/85706721/136715867-36d2813d-84a3-4b36-bc9f-d863895dd9b1.png)

## Summary Statistics on Suspension Coils

Lot Summary|Total Summary
:-------------------------:|:-------------------------:
![LotSummary](https://user-images.githubusercontent.com/85706721/136717292-e6855c6e-139b-46db-bc0d-24cd1b36317b.png)|![TotalSummary](https://user-images.githubusercontent.com/85706721/136717297-9cd0e2e6-d5f0-43b6-8ac4-95d63cd2e3a5.png)

In total the variance of the suspension coils does not exceed 100 pounds per square inch as dictated by the design specifications for the MechaCar suspension coils, but Lot3 does exceed it at 170 pounds per square inch.  This can be seen in the variance column above.

## T-Tests on Suspension Coils

### T-Test Result Acros All Manufacturing Lots
![t-test](https://user-images.githubusercontent.com/85706721/136717636-970313a2-bb65-4c94-a72c-73d8a02ce422.png)

### T-Test Results Acros Each Manufacturing Lot
![3t-tests](https://user-images.githubusercontent.com/85706721/136718185-f270ea1f-bec6-41bd-92b3-d60db0e52260.png)

Using the p-value of the T-test result we see that lot 1 and 2 have a close mean because the p-value is above 0.05, but lot 3 has a p-value below 0.05 meaning the null hypothesis cannot be rejected and reinforces the variance in coil PSI>

## Study Design: MechaCar vs Competition

I would compare the horsepower to weight ratio of MechaCar to the competition.  The null hypothesis would be there is no statistically significant relationship between the amount of horsepower and the weight of the vehicle.  The test would require horsepower and weight data from all MechaCar vehicles and competitors of each MechaCar vehicle.  We could test this hypothesis with linear regression of horsepower and vehicle weight.
