# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG:

  1. The vehicle length and vehicle ground clearance are likely to provide non-random amount of variance. Meaning the vehicle length and ground clearance both significantly effects our MPG in the dataset. On the other hand, the vehicle weight, spoiler angle and AWD feature have p-value of greater than 0.05 meaning there is no statistically significant observed difference; it indicates a random amount of variance through the dataset.

2. Slope of the linear model: The slope of this linear model is not zero, because the p-value of our slope/intercept in our analysis is 5.08e-08, which is much smaller than the assumed significance level of >0.05. This also rejects the null hypthesis.

3. In our linear regression model, the r-squared is 0.68, meaning that 68 percent of the predictions made from this analysis about mpg of MechaCar prototypes will be correct while using this model. ![Deliverable_one](https://user-images.githubusercontent.com/96811934/172295093-38423712-7e67-4ade-b135-1a108a27b78e.png)


## Summary Statistics on Suspension Coils
  The variance of the coils is 62.29 PSI for the entirety of three lots, which is within the 100 PSI variance requirement. Individually, Lot1 (variance = 0.97) and Lot2 (variance = 7.46) are within the 100 PSI variance requirement. However, Lot3 (variance = 170.28) doesn't meet the criteria as it has a greater variance of the suspension coils than 100 psi. It is Lot3 that is disproportionately skewing the variance of other lots as well.
  
  ![total_summary](https://user-images.githubusercontent.com/96811934/172301763-53fbb9dc-018c-4012-b39e-955e280f2098.png)
![lot_summary](https://user-images.githubusercontent.com/96811934/172301776-6571d640-2a30-4ceb-80e7-94c9c8a5e123.png)
