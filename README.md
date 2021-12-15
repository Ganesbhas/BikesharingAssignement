# Project Name
> Bike Rental Linear Regression Assignment 


## Table of Contents
* [General Info](#general-information)
* [Business Goal](#Business-Goal)
* [Linear Regression](#Multiple-Linear_Regression)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- A US bike-sharing Company wants to understand the factors affecting the demand for shared bikes in the American market. The service provider firm has gathered a large dataset on daily bike demand based on various meteorological surveys and people's styles,to find which variables is significant in predicting the demand for shared bikes across the American market.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Business Goal
-To model the demand for shared bikes with the available independent variables, which will be used by the management to understand how exactly the demands vary with different features.This helps in manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 

## Multiple Linear Regression
- All the relationship between independent and target variable is identified and studied. The outlier treatment and univariate analysis of all the columns is done.
- The Dummy variables for the categorical variables are created along with test and train data.
- The Best suited linear regression model is identified using the RFI, P-value,VIF. Also tested with the test data 


## conclusions
- The temperature,year & Rain are most important feature which has high relationship with the demand of bikes.
- Cnt = 0.240 Const + 0.235 (yr- 2019) + 0.422 (temp) -0.119(windspeed) -0.065 (Spring) + 0.049 (Summer) + 0.097(Winter) -0.044(December) -0.053(January)  -0.047(November) + 0.078(September)  -0.289(Light Snow) - 0.077 (Mist)

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->




<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->