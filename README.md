# PracticalMachineLearningProjectProject
Note: To view  the html page online, please visit this RPbub link:
http://rpubs.com/mchenini/353207
or look at the PDF file: barbellLiftsExercisePredction.pdf

## Overview
Using devices such as Jawbone Up, Nike FuelBand, and Fitbit it is now possible to collect a large amount of data about personal activity relatively inexpensively. These type of devices are part of the quantified self movement - a group of enthusiasts who take measurements about themselves regularly to improve their health, to find patterns in their behavior, or because they are tech geeks. One thing that people regularly do is quantify how much of a particular activity they do, but they rarely quantify how well they do it.

In this project, we will use data from accelerometers on the belt, forearm, arm, and dumbell of 6 participants. They were asked to perform barbell lifts correctly and incorrectly in 5 different ways.

The data consists of a Training data and a Test data (to be used to validate the selected model).

The goal of your project is to predict the manner in which they did the exercise. This is the "classe" variable in the training set. You may use any of the other variables to predict with.

**Note:** The dataset used in this project is a courtesy of "Ugulino, W.; Cardador, D.; Vega, K.; Velloso, E.; Milidiu, R.; Fuks, H. Wearable Computing: Accelerometers' Data Classification of Body Postures and Movements"

## Model building
For this project we will use two different algorithms, classification trees and random forests, to predict the outcome.

1. classification trees
2. random forests
3. Generalized Boosted Model

## Applying the best model to the validation data

By comparing the accuracy rate values of the three models, it is clear the the 'Random Forest' model is the winner.


