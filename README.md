# Suprise Housing - House Price Prediction
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

## Table of Contents
* [General Information](#general-information)
* [Business Goal(#Business-Goals)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:

Which variables are significant in predicting the price of a house, and

How well those variables describe the price of a house.

 
## Business Goals
You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.
Also, determine the optimal value of lambda for ridge and lasso regression.
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Determine the optimal value of lambda for ridge and lasso regression.
- The r2_score of lasso is slightly higher than ridge for the test dataset , So we will choose lasso regression over the rudge regression in order to meet the business goal

                        Ridge Regression  Lasso Regression
        R2 score(Train)            0.88             0.88

        R2 score(Test)             0.87             0.86

## Technologies Used
- library - version 1.0
- library - version 2.0
- library - version 3.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- Puneeth VS


## Contact
Created by [@pvoodhar] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
