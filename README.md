# Project Name
> Outline a brief description of your project.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. 
- The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- For Ridge Regression: Train Score = 90.93 Test Score = 87.52
- For Lasso Regression: Train Score = 89.86 Test Score = 86.78
- Top 5 Variables in Ridge are: GarageFinish_RFn GarageFinish_Unf SaleCondition_Normal SaleCondition_Others SaleCondition_Partial
- Top 5 variables in Laso are: GarageFinish_RFn GarageFinish_Unf SaleCondition_Normal SaleCondition_Others SaleCondition_Partial
- Optimum value for Alpha Ridge = 10 Lasso = 0.001
- We can choose either of the regressions, in this case it would be slightly better to choose Lasso regression

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python Version 3.11.x
- Pandas
- Matplotlib
- Seaborn
- sklearn
- statsmodels

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- Youtube videos
- Upgrad live sesison on the case study
- Wikipedia for various subjective questions


## Contact
Created by [@pvjoshi19] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->