# MechaCar_Statistical_Analysis

### Overview

##### The objective of this analysis is to provide information about MechaCar production to assist the manufacturing team. For this analysis, I use two datasets containing information on miles per gallon and the MechaCar suspension coils. We will help Jeremy develop a statistical study to compare the performance of MechaCar vehicles relative to other manufacturers.

### Result

#### Linear Regression to Predivt MPG:

![miles-per-gallon-linear](https://user-images.githubusercontent.com/101905587/190862438-79eb7e80-a46b-496c-ab65-9e2224f9ede0.png)

##### Two variables resulted in a degree of non-random variance. Vehicle length and vehicle ground clearance are statistically likely to provide nonrandom variance values to the model. This means that the length and ground clearance of the vehicle has a significant impact on miles per gallon on the MechaCar prototype. In contrast, vehicle weight, spoiler angle and all-wheel drive have p-Values which indicate a random deviation from the data set.

##### This linear model has a r-squared value of 0.7149, which means that over 100 instances, this model would predict roughly the MechaCar mpg correctly 71 times.

### Summary Statistics on Suspension Coils

#### Total Summary Table

![t_summary](https://user-images.githubusercontent.com/101905587/190863291-88aa167f-9c04-4f49-8f4b-2ea386c59aa2.png)

#### Lot Summary Table

![lot_summary](https://user-images.githubusercontent.com/101905587/190863274-11bc6e50-b786-40c9-8849-1c1e4a7e675c.png)

##### For the production lot population as a whole, the coil variance is 62.29 PSI, which is well below the 100 PSI variance requirement. This is because the variance of the third lot is approximately 170.2 PSI, exceeding the design specified by more than double the amount aloft. As a result, the manufacturing team should be working with Lot 1 and Lot 2 compared to Lot 3.
