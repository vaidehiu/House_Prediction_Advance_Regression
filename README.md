# House Price Prediction using advance regression algorithms
> A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. 
> This is Business stragegy of real estate core in general.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- The data set consists of 1140 row and 81 columns
- 'train.csv' is data used in the problem
- Analysing this is core to find most influencing factors in price of house 
- This will help US housing company to purchase house when the price is down in their new venture of Australian market by studying the behavior of people and other factors that is documented in csv


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Univariate conclusion:
   - Number of years ago Garage built in the data is around 15-45yr
   - Number of years ago House built in the data is around 15-58yr
   - Most people have garage cars from 1-2
- Bivariate conclusion:
   - KitchenQual Excellent has greater price
   - MSZoning shows Residential Low Density and Floating Village Residential have higher price than Commerical place
   - If house has road access which are Paved then price is higher
   - If home is very new "Home was not completed when last assessed" then price is higher found from SaleCondition feature
   - If house has Roof of shed it has higher price
   - Sale price of houses whose Neighborhood is IDOTRR->Iowa DOT and Rail Road and MeadowV->Meadow Village are very less compared to others
- Multivariate conclusion:
  - GrLivArea ,GarageCars ,GarageArea and TotalBSMTSF and 1st Flr SF have greater influence on target variable Sale Price
- RFE Model
  - Not ideal model .R2 is very low after application of RFE 
- Ridge and Lasso are good.
- Lasso is better slighly performs better on getting mean squared error less.
- Behavior of Lasso and Ridge on alpha and neg_mean_square_error
- Ridge
    - r2 of train 0.9378379406798446
    - r2 test  0.914664719097858
    - The MSE of the model on the train dataset for optimum alpha is 0.062162059320155366
    - The MSE of the model on the test dataset for optimum alpha is 0.08533528090214204</b>
- Lasso
     - r2 of train 0.9328993288182069
     - r2 test  0.9154027790933243
     - The MSE of the model on the train dataset for optimum alpha is 0.06710067118179312
     - The MSE of the model on the test dataset for optimum alpha is 0.08459722090667571</b>
 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- NumPy - version 1.20.1
- Pandas - version 1.2.4
- Matplotlib - version 3.3.4
- Seaborn - version 0.11.1
- statsmodels - version 0.12.2
- scikit-learn - version 0.24.1.

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
This project was created as a assignment required for Executive PG Programme in Machine Learning & AI - IIIT, Bangalore


## Contact
Reach out the creators on,
- Linkedin:
    - [Vaidehi Rao](https://www.linkedin.com/in/vaidehi-u-026a09150/)
- Github:
    - [Vaidehi Rao](https://github.com/vaidehiu)  
