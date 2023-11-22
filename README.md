# BoomBikes Bike Sharing Assignment

## **Problem Statement**

A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.

In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

- Which variables are significant in predicting the demand for shared bikes.
- How well those variables describe the bike demands

Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors.

**Business Goals**:

You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information

The Company **BoomBikes** has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. Thereby to sustain in the current market scenario, it needs a business strategy to increase it's revenue once pandemic lockdown ends. Thus this assignment targets 

- Identification of Key Driver variables for the demand of bikes
- Understand these drivers to increase the sales
- Take strategic decisions to generate profits by maximising sales

## Conclusions

- The equation of the best fit line is given by:<br>
  **cnt** = 4491.3033 + (998.5631 x **yr**) + (1125.0534 x **temp**) - (213.0869 x **hum**) - (276.1097 x **windspeed**) + (343.4570 x **summer**) + (526.3388 x **winter**) + (239.1522 x **September**) - (131.7794 x **Sunday**) - (349.2905 x **Light Rain or Snowy**) - (214.7093 x **Misty and Cloudy sky**)
- The Absolute Difference between R2 Score of train dataset (**0.837**) and R2 Score of test dataset (**0.803**) is  **0.034** indicates that our model is a good fit.
- Significant variables driving the bike demand are **temperature**, **yr**.
- Bike demand is also affected by other variables such as **hum**, **windspeed**, **summer**, **winter**, **September**, **Sunday**, **Light Rain or Snowy**, **Misty and Cloudy sky**.

## Technologies Used

- [Python](https://www.python.org/) - version 3.10.4
- [Pandas](https://pandas.pydata.org/) - version 2.1.2
- [Numpy](https://numpy.org/) - version 1.24.4
- [Matplotlib](https://matplotlib.org/) - version 3.8.1
- [Seaborn](https://seaborn.pydata.org/) - version 0.13.0
- [Statsmodels](https://www.statsmodels.org/stable/index.html) - version 0.14.0
- [Scikit-Learn](https://scikit-learn.org/stable/) - version 1.0.2

## Acknowledgements
The project was built using help and guidance based upon
- Live sessions of upGrad on Industry Relevance of Linear Regression Models
- UpGrad tutorials on Linear Regression

## Contact

Created by [@sharmaankit091](https://github.com/sharmaankit091)
