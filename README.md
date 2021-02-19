# MechaCar_Statistical_Analysis

## Summary Statistics on Suspension Coils
### Total_summary
<img src = 'https://github.com/osbornej-tech/MechaCar_Statistical_Analysis/blob/main/images/total_summary.png'>

### Lot_summary
<img src ='https://github.com/osbornej-tech/MechaCar_Statistical_Analysis/blob/main/images/lot_summary.png'>

### Question 
The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not? 
  - The Current manufacturing data does not meet the specification for all manufacturing lots because Lots 1 and 2 mean meet the standard because they have low standard deviation when compared to the total standard deviation is high. On the other hand, Lot 3 does not meet the specification because its standard deviation is 13.05 compared to the other lots with lower Standard deviation. 
  
### All Manufacturing and Lot1 T-Test Summary
<img src ='https://github.com/osbornej-tech/MechaCar_Statistical_Analysis/blob/main/images/all_manufacturing_lot1.png'>

## T-Tests on Suspension Coils
### T-test for Lot 2 and Lot3
<img src ='https://github.com/osbornej-tech/MechaCar_Statistical_Analysis/blob/main/images/Lot2_Lot3.png'>

### Summary
The T-test on suspension coils demonstrate that Lots 1 and 2 are not statistically different from the population mean whose p-values are 1 and 0.60 respectively. Lot 3 is statistically signifcant as the p-value is 0.04.

## Study Design: MechaCar vs Competition
According to the Linear Regression Model Summary that assess the mechanics of the cars in the data set, the fields vehicle_length and ground clearance were statistically significant as the p value was less than .05.

Assessing the vehicle weight and mpg are crucial factors to assess as individuals hope to have a vehicle that are fuel efficient. Furthermore, as a manufacturer it is important for MechaCar to identify parts makers that allow their product to be efficient and effective in increasing mpg. 

What metric or metrics are you going to test? compare vehicle weight and mpg for MechaCar and other Manufacturers.

What is the null hypothesis or alternative hypothesis? There is no correlation between weight and mpg. The alternative hypothesis is that there is a correlation between weight and mpg.

What statistical test would you use to test the hypothesis? And why? I will utilize correction function 'cor()' in R to test this hypothesis. 

What data is needed to run the statistical test? We will need the weight and mpg data of MegaCar and its competitors. We will utilize a sample 'sample_n()' of dataset to ensure that we have a equal representation of their dataset.

### MechCar Linear Regression Model Summary
<img src ='https://github.com/osbornej-tech/MechaCar_Statistical_Analysis/blob/main/images/Linear_regression_model_summary.png'>
