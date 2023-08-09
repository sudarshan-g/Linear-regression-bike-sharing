# Linear-regression-bike-sharing

## Table of Contents
* [Brief overview](#brief-overview)
* [Problem Statement](#problem-statement)
* [Dataset](#dataset)
* [Libraries used](#libraries-used)
* [Final Model Stats](#final-model-stats)
* [Author](#author)

## Brief overview
Build a Linear regression model to estimate the bike demand based on various meteorological survey data and other variables such as holidays/weekdays etc.

## Problem Statement
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 

In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demands
Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 

`Business Goal:`
You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.

## Dataset
Available under: \dataset\day.csv

## Libraries used
- Numpy - `1.24.3`
- Pandas - `1.5.3`
- Matplotlib - `3.7.1`
- Seaborn - `0.12.2`
- Sklearn - `1.2.2`
- statsmodels - `0.14.0`
  

## Final model stats
**cnt** = `1010.0584` 
\+`2028.9952` X _yr_ + `4103.2348` X _temp_ - `589.1049` X _mnth_Jul_ + `539.6480` X _mnth_Sep_
\+ `676.2652` X _wthr_mostly_clear_ - `1897.6647` X _wthr_snowrain_light_ - `987.1736` X _season_Spring_
\+ `460.0991` X _season_Winter_

`Findings/Observations`: The test data `R-Squared` and `Adjusted R-Squared` are `0.8091` and `0.8018` respectively. This is pretty close to the training dataset's `R-squared` and `Adjusted R-squared`
\- `0.818` and `0.815`

## Author
[Sudarshan](mailto:sudarshan_g@outlook.com)
