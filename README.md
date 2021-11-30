# MechaCar_Statistical_Analysis
## Linear Regression to Predict MPG
- This linear regression showed us that vehicle length and ground clearance had the most significant impact on mpg and provide non-random variance to the mpg values in the dataset. 
- The slope of the linear model is not zero.
- We can also tell thislinear model predicts mpg of MechaCar prototypes effectivly because the multiple R-squared is .7149 or about 71%.
- See screenshot below for all details:

![Screenshot (165)](https://user-images.githubusercontent.com/86331828/143964626-4917efc1-3461-4a0f-997d-1e9f9df11a9a.png)

### Summary Statistics on Suspension Coils
- First we summarized the data to find the mean, median, variance and standard deviation of the data. 
- Then we used the group_by function to get the mean, median, variance and standard deviation broken down by lot. With this data we can see that   two of the three lots (lot 1 and lot 2), do meet the requirements. Lot 3 however, does not. 
- See image below for all details: 

![Screenshot (167)](https://user-images.githubusercontent.com/86331828/143982101-ca5a49e2-7297-49a3-b0be-f7cfdda9f766.png)

### T-Tests on Suspension Coils
- We performed t-tests to determine if all manufacturing lots and each lot individually different from the population mean of 1500 pounds per square inch. 
- We looked at the PSI across all manufacturing lots and then we looked at the PSI for each manufacturing lot individually. 
- We found that lots 1 and 2 both had accurate PSI of 1500 but lot 3 had a psi of 1496.14 which means that lot 3 was throwing off the mean when we looked at the information all together. We can narrow our issue down to lot 3.
- See image below for all details:

![Screenshot (169)](https://user-images.githubusercontent.com/86331828/143982908-6b87e123-58d9-4334-b51e-43bc42d8bcde.png)

### Study Design: MechaCar vs Competition
- MechaCar vs competition will compare cost, fuel efficiency and maintenance cost. 
- The null hypothesis is that MechaCar will outperform all other competition in cost, fuel efficiency and maintenance cost.
- We will use t.tests, summarize(), group_by and linear regression to compare these metrics.
- We will need the cost, fuel efficiency and maintenance cost for multiple MechaCars and also for the competition. 
