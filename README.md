# HOUSE PRICE PREDICTION USING ADVANCE REGRESSION 
> Building Ridge and Lasso Regression models for House price prediction. 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:
- Which variables are significant in predicting the price of a house, and
- How well those variables describe the price of a house.
- Also, determine the optimal value of lambda for ridge and lasso regression.

## Conclusions
- Significant Variables in the Prediction of House Prices:
            - TotalSF
            - GrLivArea
            - TotalBsmtSF
            - OverallQual_9
            - GarageArea
            - Neighborhood_Crawfor
            - OverallQual_8
            - GarageArea 
            - LotArea
            - OverallCond_9
            - GarageCars    
            - Neighborhood_StoneBr
            - SaleCondition_Partial 
-How well those variables describe the price of a house?
            - For each square feet increase on TotalSF, TotalBsmtSF, LotArea, & GrLivArea, price increases somewhere between 0.06 to 0.14 times. 
            - If the OverallQual Score is 9 for a house, the price increases by 0.07 to 0.13 times.
            - If the Neighbourhood is Crawfor, price increases between 0.5 to 0.6 times.
            - GarageArea and GarageCar increase affects the price hike by 0.4 times
            - If the SalesCondition is Partial, it increases the price by 0.5 times.
            - StoneBr Neighbourhood also increases the price by 0.06 times.
            
- Optimal value of lambda for Ridge Regression = 4.0
   
- Optimal value of lambda for Lasso = 0.0001


## Technologies Used
- numpy - version 1.20.1
- pandas - version 1.2.4
- matplotlib - version 3.3.4
- seaborn - version 0.11.1


## Contact
Created by [@Jahana-s] - feel free to contact me!
