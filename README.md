# Prediction of Bike Sharing Demand

A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues. They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

- Which variables are significant in predicting the demand for shared bikes.  

- How well those variables describe the bike demands  

We are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.

## Table of Contents

- [Prediction of Bike Sharing Demand](#prediction-of-bike-sharing-demand)
  - [Table of Contents](#table-of-contents)
  - [General Information](#general-information)
  - [Conclusions](#conclusions)
  - [Technologies Used](#technologies-used)
  - [Acknowledgements](#acknowledgements)
  - [Contact](#contact)

## General Information

- What is the background of your project?
  - It gives an hands on to solving real world problem using Linear Regression model and the steps that lead to creation of practical model
- What is the business problem that your project is trying to solve?
  - We are trying to root out key drivers which company can focus to increase there scales once things start re-opening post pandemic.
- What is the dataset that is being used?
  - Mentioned in [Acknowledgements](#acknowledgements)

## Conclusions

- **Temperature** is a very big factor in driving demand. Since the temperature for given dataset varies between 2-35 and most of the time its under 30 hence it means that temperature drops or its chilly outside people prefer less ride while on a pleasant day(15-28) the demand rises.
- **Year** as highlighted in Data understanding stage also, the demand increases gradually every year as word of mouth and operations expand.
- In case of **Light Snow , Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds** the demand drops a lot which again is logical since its hard to drive bike in that kind of weather
- Similarly on a **windy day** the bike is not preferred option

## Technologies Used

1. numpy
2. pandas
3. matplotlib
4. seaborn
5. sklearn
   1) train, test
   2) MinMax Scaler
   3) Linear Regression
   4) RFE
6. statsmodel
7. variance inflation factor

## Acknowledgements

- This project is outcome of assignment on Linear Regression
- The provided dataset was used from following publication
  - [1] Fanaee-T, Hadi, and Gama, Joao, "Event labeling combining ensemble detectors and background knowledge", Progress in Artificial Intelligence (2013): pp. 1-15, Springer Berlin Heidelberg, doi:10.1007/s13748-013-0040-3.

## Contact

Created by [@010693]
