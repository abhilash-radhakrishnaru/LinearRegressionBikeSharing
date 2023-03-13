# Linear Regression Assignment - Bike Sharing
Build a multiple linear regression model for the prediction of demand for shared bikes


## Table of Contents
* [About the company](#About-the-company)
* [Problem Statement](#Problem-statement)
* [Conclusions](#Conclusions)   
* [Technologies Used](#technologies-used)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## About the company
BoomBikes is a US bike-sharing provider. A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system services company headquartered in San Francisco, California. That explains the business model.

## Problem statement
BoomBikes has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. Company want to understand the factors affecting the demand for these shared bikes in the American market. Mainly the company wants to know:

Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demands

input :
day.csv file which contains the previous bikesharing data set
Readme.txt which contains the meta data information of day.csv file


- Provide general information about your project here.
- What is the background of your project?
- What is the business probem that your project is trying to solve?
- What is the dataset that is being used?

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
Equation for best fit line is

cnt = 0.0226 + (0.2573 * yr) + (0.0350 * working day) + (0.5761*temp) - (0.0304 * windspeed) + (0.0906 * summer_season) + (0.1692 * season_Winter) + (0.0792 * mnth_Sept) + (0.0590 * weekday_Sat) - (0.2649 * weathersit_LightShower) - (0.0801 * weathersit_Misty)

Recommendations to Boom Bike's bike
- Temp has a very high positive impact on the bike demand (coef of 0.5761)
- Lighsnow/rain weather has a negative impact on the bike demand. (0.2649)
- Bike demand is going high over the year (0.2573)
- Winter season has high positive impact on the bike demand(0.1692)
- Other variables which has an impact on the bike demand are
    working day(0.0350), windspeed(-0.0304), saturday(0.0590), summer(0.0906), misty weather(-0.0801) and sep month(0.0792).

## Technologies Used
- python
- pandas library
- matplotlib library
- missingno library
- numpy library
- seaborn library
- sklearn library
- statsmodels library

## Acknowledgements
Give credit here.
- This project was inspired by upGrad's assignment