# Starbucks analysis: Predicts whether or not someone will respond to an offer.
### Table of Contents 
1. [Project Motivation](#Project-Motivation)
2. [Description](#Description)
3. [Installation](#Installation)
4. [Libraries](#Libraries)
5. [File Descriptions](#File-Descriptions)
6. [Result](#Result)

## Project Motivation
I curious that how to find the preferred offer that customer want by using the Starbucks dataset.

## Description
One of the main problems that the company faces when sends out an offer to the customers is the company doesn't know which offer be preferred by customers. Hence the company sends out an offer without knowing what offer that customer desires.

This project predicts whether offer is responded or not responded by an individual customer. This means that the company can implement this prediction to help the company find which offer is preferred by an individual customer and sends out an offer correctly. The project implements the XGBoost classifier and Starbucks dataset to training the model. 

The project implements the XGBoost classifier and Starbucks dataset. The Starbucks dataset comprised Portfolio, Profile, and Transcript datasets. These datasets are used to train the XGBoost model.

## Installation

The XGBoost need to be installed.

```conda install -c conda-forge xgboost```

run the command ```conda update pandas``` before reading in the files. To make pandas read ```transcript.json``` file correctly.

And the project code should run with no issues using Anaconda versions 4.9.x, python versions 3.x., and seaborn versions 0.11.x </br>

## Libraries
* pandas
* numpy
* json
* sklearn
* scipy
* math
* statsmodels
* matplotlib
* seaborn
* xgboost

## File Descriptions
```data/```: The folder that contains dataset (json format). <br/>
```data/portfolio.json```: The data of each Starbucks offer. <br/>
```data/profile.json```: The demographic data of each customer. <br/>
```data/transcript.csv```: The customer behavior on the Starbucks rewards mobile app. <br/>
```images/```: The folder that contains images for explanation. <br/>
```readme.md```: README file. <br/>
```starbucks_project.ipynb```: The jupyter notebook file where the code and visualization are presented.

## Result

The prediction can tell a company what offers are preferred by an individual customer. 
The customer demographic and offer details are put to the model to make a prediction.
