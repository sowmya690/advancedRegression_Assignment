# Advanced_Regression_HousePrice_Prediction
> Advanced Regression case Study for House Price Prediction


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

### Background
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below. 

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.


The company wants to know:
- Which variables are significant in predicting the price of a house, and
- How well those variables describe the price of a house
- Also, determine the optimal value of lambda for ridge and lasso regression.

### Business Goal 

Requirement is to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market


## Technologies Used
- pandas 
- numpy
- matplotlib
- seaborn
- sklearn
- Linear, Ridge and Lasso Regression

## Conclusions
- Train and Test score from linear model built for data clearly shows overfitting and hence it is required to use Advanced Regression methods
- After using Ridge Regression and Lasso Regression, we can state that their r2 values are nearly identical.
- When comparing complexity, it is preferable to use Lasso rather than Ridge since Lasso will choose the best features from the current variables, while Ridge will keep all the variables while lowering the coefficient of variables.

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->


## Contact
Created by [@sowmya690](https://github.com/sowmya690) - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
