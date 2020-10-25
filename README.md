# MechaCar Statistical Analysis
## Overview


## Results
### Linear Regression to Predict MPG
- The variables that provided a non-random amount of variance to the mpg values in the dataset are the `vehicle length` and `ground clearance` (as well as the intercept).
- The slope of the linear model is not considered to be zero because the p-value is less than 0.05 (5.35e-11), which is statistically significant. Therefore, we have sufficient evidence to reject the null hypothesis.
- Yes, this linear model predicts the mpg of the MechaCar prototypes effectively as the r-squared value is close to 1, at 0.7149 showing a strong correlation between the independent variables and mpg.  
<br>

### Summary Statistics on Suspension Coils
The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch (PSI). 


**Manufacturing lots in total**
- The current manufacturing data meets this design specification with a variance of 76.23 PSI.<br>

**Each manufacturing lot individually**
- Not all lots meets this design specification individually. Lots 1 and 2 meet this design specification with a variance of 1.15 PSI and 10.13 PSI, respectively. While Lot 3 has a variance of 220.01 PSI, which did not meet this design specification.
<br>

### T-Tests on Suspension Coils
**Across all manufacturing lots**
- According to the results of the t-test on the suspension coils, the mean PSI across all manufacturing lots is 1499.531 PSI, with a p-value of 0.5117. The p-value is much higher than the 0.05 statistical significance level and the PSI is therefore, found to be **not statistically different** from the population mean of 1,500 PSI. We can conclude that we failed to reject the null hypothesis.<br>

**Each manufacturing lot individually**
- Lot1: The mean is 1500.018 PSI, with a p-value of 0.9048. The p-value is much higher than the 0.05 statistical significance level and the PSI is therefore, found to be **not statistically different** from the population mean. We can conclude that we failed to reject the null hypothesis.<br>
- Lot2: The mean is 1499.571 PSI, with a p-value of 0.3451. The p-value is much higher than the 0.05 statistical significance level and the PSI is therefore, found to be **not statistically different** from the population mean. We can conclude that we failed to reject the null hypothesis.<br>
- Lot 3: The mean is 1499.004 PSI, with a p-value of 0.637. The p-value is much higher than the 0.05 statistical significance level and the PSI is therefore, found to be **not statistically different** from the population mean. We can conclude that we failed to reject the null hypothesis.
<br>

### Study Design: MechaCar vs Competition
There are numerous metrics that would be of interest to a consumer when choosing to purchase a vehicle such as fuel economy (mpg), safety rating, cost, horsepower, greenhouse gas emissions, maintenance frequency, and maintenance cost. Here is a short description of a statistical study that could quantify how the MechaCar performs against the competition. 

#### Metrics
For the purpose of this statistical study, these metrics will be tested:
- Fuel economy
- Greenhouse gas emissions

#### Null Hypothesis & Alternative Hypothesis
Ho: Cars with better fuel economy (mpg) will have no effect on greenhouse gas emissions.
Hα: Cars with better fuel economy (mpg) will have less emission greenhouse gas emissions.

#### Statistical Test
I would use an ANOVA to test the hypothesis. This way I can determine if there is a statistical difference between the distribution means of from MechaCar’s sample and the various other competition’s samples.

#### Data needed
The data needed to run the statistical test are listed below:
-	Fuel economy (mpg) data
-	Greenhouse gas emissions data
-	MechaCar and various other competition car manufacturer data

The data table should look something like this:
