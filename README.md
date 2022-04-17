# MechaCar_Statisical_Analysis
Module 15

**Deliverable 1**

**Linear Regression to Predict MPG**

![image](https://user-images.githubusercontent.com/96017493/163722045-6a4562fb-99a6-4286-92f5-084dd40ea014.png)

1)**Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?**

Vehicle Length and Ground Clearance provide non-random amounts of variance. This conclusion is the result of their P-Values. Vehicle Length has a P-Value of 5.08e^-8 ,and Ground Clearance has a P-Value of 5.21e^-8. Both of these P-values are far less than the standard P-value of 0.05. It is for this reason that we can reject the null hypothesis and assume that our results are non-random. 

2)**Is the slope of the linear model considered to be zero? Why or why not?**

The p-value of our model is 5.35e^-11, which is far below the standard p-value of 0.05. This implies that we can reject the null hypothesis, which implies that our slope is not zero. 

3)**Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?**

Yes, this model effectivley predicts mpg of MechaCar. This conclusion is the result of having a R-squared value of 0.71. This tells us that there is a strong correlation between our independent variables with the dependent variable. 




**Deliverable 2**
**Summary Statistics on Suspension Coils**

**total_summary**

![image](https://user-images.githubusercontent.com/96017493/163723770-9cf4e611-be8d-4fc9-a476-8636b4a5391a.png)

**lot_summary**

![image](https://user-images.githubusercontent.com/96017493/163723819-ca2dca2c-c9d2-47fc-9c25-97a9e1712990.png)

**Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?**

Yes. The variance for the lots total is 62.29 which is below the recommended 100psi. When looking into the individual lots, there is one lot that far exceeds the 100PSI requirement. Lot1 and Lot2 have variances well under the 100psi however, lot3 has a variance of 170.29. Lot3 does not meet the design specifications for suspecnsion coils. 

**Deliverable 3**

**T-Tests on Suspension Coils**

![image](https://user-images.githubusercontent.com/96017493/163725122-28af63b2-6399-4dab-9f63-ec0cc57b9f41.png)

![image](https://user-images.githubusercontent.com/96017493/163725158-9c93dc51-8092-41ce-8247-0bb00c92495a.png)

![image](https://user-images.githubusercontent.com/96017493/163725192-99a15ccb-6e20-4c6e-bae2-9f1ef74fe411.png)

![image](https://user-images.githubusercontent.com/96017493/163725221-4571c5af-6fa2-4643-844c-0340b84075cf.png)

**t-test findings**

Based on using the standard p-value of 0.05 standard for rejecting the null hypothesis; we will fail to reject the null hypothesis when using data from all lots. We will also fail to reject the null hypothesis for lot1 and lot2. This implies that there is no difference in the mean values. Lot3 however, has a p-value of 0.04 which is less than the 0.05 standard. This implies that we can reject the null hypotheisis and that there is a difference in the mean value. 



**Deliverable 4**

**Study Design: MechaCar vs Competition**

1)**What metrics are you going to test?**

I would like to compare finincal data with the competitor. Metrics that I would like to compare are cost of manufacturing and sale price. Comparing this data with our competitor can help us make decisions regarding marketing our product. One approach might be to create a better product and market it as a luxery alternative to the competitor. 

Fuel efficiency, and horsepower are also metrics of interest. Comparing how we compare in power and mpg can help us to market the vehicle. For example if our product has more horsepower but not fuel efficient,we can market our car this way. We can target consumers that desire a more powerful verhicle. 

I would also like compare sales based on cities. Again, this can be a major marketing tool. This gives us an opportunity to find, and exploit advertising opportunities to increase sales. 

2)**What is the null hypothesis or alternative hypothesis?**

The null hypothesis would be that there is no difference in the data with our competitors. Our alternative hypothesis would be that there is a difference in the data. 

3) 



