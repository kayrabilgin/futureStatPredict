# Future Statistics Prediction
***

The system which predicts the future user statistics of a mobile application using the machine learning algorithms, is designed. There are 2 main objectives of this system. 

● Prediction of the number of users for the next 6 hours using the latest 24 hour’s data.

● Total number of users will be observed 24 hours later than the latest data point using the latest 5 day’s data.


## Table of Contents
1. [General Info](#general-info)
2. [Requirements](#technologies)
3. [How to Run](#installation)

## General Info
The future user statistics of a mobile application is predicted in a pipelined system. Scikit-learn library is used for creating pipelines. Scalers are used for standardization as a step of all pipelines. In some cases, a function for converting series to supervised learning is used as a step as well. The last step of the pipelines is the machine learning algorithms. These pipelines are used to satisfy the objectives. In addition, total duration and the memory usage of the overall system is returned by the system.

## Requirements

* app.csv
* futureStatPredict.ipynb

## How to Run

After the futureStatPredict.ipynb jupyter notebook and the app.csv data are opened in the same environment, all the cells should be run to see the results of different pipelines. 
