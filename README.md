# Project Name
> Multiple Linear Regression - Demand for Shared Bikes




## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
Problem Statement & Objective:
A US bike-sharing provider BoomBikes aspires to understand the demand for shared bikes among the people following Covid-19 pandemic.

Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demands
We are required to model the demand for shared bikes with the available data to understand how exactly the demands vary with different features. This will be a multiple linear regression model for the prediction of demand for shared bikes.

Steps for the model are below:
S1:Data Understanding and Data Loading
S2:Pre-processing Steps (Dropping Columns and Mapping of categorical values)
S3:EDA (Univariate, Bivariate and /or Multivariate analysis)
S4:Create dummy variables for all categorical variables where no. categories > 2
S5:Train Test Split
S6:Missing value imputation
S7:Scaling
S8:Feature Selection
S9:Model Building
S10:Evaluation (Train and Test Data) - R2 and Adjusted R2

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
We have developed a multiple linear regression model to predict demand of shared bikes.
The equation for the model is 

𝑐𝑛𝑡=0.1994 + 0.2336×𝑦𝑒𝑎𝑟 ⎯0.0975×ℎ𝑜𝑙𝑖𝑑𝑎𝑦 + 0.4910×𝑡𝑒𝑚𝑝 ⎯0.1479×𝑤𝑖𝑛𝑑𝑠𝑝𝑒𝑒𝑑 -0.2842×𝐿𝑖𝑔ℎ𝑡𝑠𝑛𝑜𝑤𝑟𝑎𝑖𝑛 -0.0802×𝑀𝑖𝑠𝑡𝑦Cloudy -0.0521×july + 0.0768×sep - 0.0672×𝑠𝑝𝑟𝑖𝑛𝑔 + 0.0465×𝑠𝑢𝑚𝑚𝑒𝑟 + 0.0817×𝑤𝑖𝑛𝑡𝑒𝑟

The model performance is evaluated as follows

### Train R2 = 0.835
### Train Adjusted R2 = 0.832

### Test R2 = 0.8053
### Test Adjusted R2 = 0.795

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Pandas
- Numpy
- Statsmodels
- Sklearn
- matplotlib
- seaborn

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->


## Contact
Created by [@nbsrini] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->