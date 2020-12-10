# Blind-KNN Introduction

This repository is a simplified of one of my dissertation topics and papers, the use of K-Nearest Neighbors to be able to classify where radio frequency (RF) signatures come from in relation to its source, a technique that can be used for indoor localization, or the ability to determine a user's position in an indoor environment. 

The purpose of the current project is to be able to take some of the work we've done in the past, which was done in R, and to be able to show the concepts of KNN, cross-validation, and A/B (hypothesis) testing. I will be using Python with the Pandas, Numpy, SciPy, and Sklearn libraries for this project.

## Project Links
1. [Classification (KNN, Cross-Validation, A/B Testing)](https://github.com/inm2/Blind-KNN/blob/main/KNN%20Classification.ipynb)

## Journal Paper
To read the full journal, click here: https://ieeexplore.ieee.org/document/9044410

## Resources
[For this project, I already have our cleaned data source that we used for the project. I have the database uploaded to this repository as a .csv file.](https://github.com/inm2/Blind-KNN/blob/main/KnnData2.csv) 

## Explanation of Project

To explain the original project, here is a quote from our paper:

> Indoor position estimation has been cited as not being accurate due to noisy environments. Variations of the knearest neighbor (kNN) algorithm have been used to mitigate this noise. In this paper, the concept of using the fingerprinting process with the radiation pattern of an antenna is explored. The contents of the paper focus on finding the distance between an RFID reader and a tag. Using the relative angle of the antenna with respect to a reference point, a model is introduced. Received signal strength index (RSSI) readings from the backscattered signal of the RFID tag were measured in a 7-foot x 4-foot grid. The resulting data points were placed in the relative angle correction KNN (RAC-KNN) algorithm. Both regression and classification models of the RAC-KNN were implemented. As a result, the classification model yielded an 85% prediction rate of the distance estimation and the regression model resulted in a 0.2-foot average error.

## Explanation of Column Names
- x.coord = X-coordinate of grid used for testing  
- y.coord = Y-coordinate of grid used for testing  
- angle =  Current angle to the tranmitter  
- distance = Measured distance from receiver to transmitter   
- RSSI = Recieved Signal Strength Index, an indicator of how strong a signal is receieved from a transmitter to receiver  
- rel = Angle relative to the transmitter  
- dist1 = Distance range in which the receiver was placed (Classifier)  


