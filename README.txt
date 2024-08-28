# Project Name
> Supervised Model creation for demand of Shared Bikes


## Table of Contents
* [General Info](#general-information)
* [Process]
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- This assignment is a programming assignment wherein you have to build a multiple linear regression model for the prediction of demand for shared bikes.

- What is the background of your project?
	A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 

- What is the business problem that your project is trying to solve?
	BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.
	They wants to know:
	- Which variables are significant in predicting the demand for shared bikes.
	- How well those variables describe the bike demands
It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 

- What is the dataset that is being used?
	Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. The data set has been provided in .csv format.



## Conclusions
- he final training set had R^2 value as 0.829 which is near to test set i.e. 0.774. So, we can conclude that the result is pretty good, with some loss in performance for unseen data

- Based on the model we can conclude 3 important feature affecting the demand of shared bike:
	1. Temperature (With rise in Temperature, demand of shared bikes increases)
	2. Light Snow/Rainfall (With rise Light Snow/Rainfall, demand of shared bike decreases)
	
	3. Year (With each passing year the demand of shared bikes increases)

- Major Inference from EDA
	1. with rise in Temperature, the number of bike rental increases.
	2. Similarly, with rise in Feel of Temperature, the number of bike rental increases
	3. Slight decline in number of bike rental with rise of Humidity where majorly Humidity ranges roughly from 40 to 80
	4. With rise of wind speed, there is a decline in number of bike rental
	5. Majority of bike rental happens where the weather is Clear, Few clouds, partly cloudy and the rental gradually decreases as the weather deteriorates.
	6. During Heavy rainfall/snow there is no bike rentals
	7. There is a steep rise in number of bike rentals in 2019 compared to 2018 to be precise post March 2019
	8. Majority of bike rental has been observed in fall season and least during “spring”


## Process
- Data Collection: We imported the loan dataset provided by upgrad
- Data Processing: Data Cleaning if required, Feature Selection, Feature Scaling, Encoding Categorical Variables
- Feature Engineering: Creating multiple new features from existing feature
- Splitting the Dataset: Using Train-Test Split in 70-30 ratio.
- Model Training: Choose the model, Fit the model
- Model Evaluation: Predict on Test Data, Evaluate Performance R^2

## Technologies Used
- Python 3.11.7
- Seaborn version: 0.12.2
- Pandas version: 2.1.4
- NumPy version: 1.26.4
- Jupyter notebook - Version: 7.0.8
- Work/PDF
- train_test_split from sklearn.model_selection
- MinMaxScaler from sklearn.preprocessing
- statsmodels.api
- variance_inflation_factord from statsmodels.stats.outliers_influence
- r2_score from sklearn.model_selection 

## Acknowledgements
Give credit here.
- This project was inspired by Upgrad

## Contact
Created by [@sroy-git, Sourish Roy] - feel free to contact me!
