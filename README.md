# bike_sharing_prediction_model
> Outline a brief description of your project.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.

- They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:
    Which variables are significant in predicting the demand for shared bikes.
    How well those variables describe the bike demands

## Business Understanding
- The objective is to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- We are considering the below features as significant as they have a low p-value and low VIF
    - temp
    - yr
    - winter
    - workingday
    - misty
    - Jul
    - hum
    - windspeed
    - light rain

- temp has the highest positive co-efficient of 0.6578 while light rain has the higest negative co-efficient of -0.2274.
The slope of the hyper plane can be represented as follows:

y = 0.6578 X temp + 0.2266 X yr + 0.1075 X winter + 0.0231 X workingday - 0.0465 X misty - 0.1016 X Jul - 0.1695 X hum - 0.1795 X windspeed - 0.2274 X light rain + 0.2011


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- numpy
- pandas
- matplotlib
- seaborn
- sklearn
- statsmodel

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was created by Leon Richard D'souza as part of curriculum by IIIT-B ML & AI course


## Contact
Created by [@dsouzaleon] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->