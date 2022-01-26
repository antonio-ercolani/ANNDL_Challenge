# ANNDL_Challenge
Challenges hosted on CodaLab for the Artificial Neural Networks and Deep Learning course @ PoliMi 2021/2022

## Members
[Antonio Ercolani](https://github.com/antonio-ercolani)  
[Francesco Romanò](https://github.com/romano-francesco)

# Image Classification challenge
In this challenge we were provided with a dataset of 17728 256x256 RGB photos of leaves belonging to 14 different classes:
0: "Apple"
1: "Blueberry"
2: "Cherry"
3: "Corn"
4: "Grape"
5: "Orange"
6: "Peach"
7: "Pepper"
8: "Potato"
9: "Raspberry"
10: "Soybean"
11: "Squash"
12: "Strawberry"
13: "Tomato"

The full dataset can be consulted [here](https://github.com/antonio-ercolani/ANNDL_Challenge/tree/main/Image_Classification_Challenge/dataset/training)
### Task and results
The task was to create a classifier of leaves using a Deep Learning approach, in particular CNN based models. During the challenge we have tried different solutions, all the major experiments are available for consultation in the folder [Experiments](https://github.com/antonio-ercolani/ANNDL_Challenge/tree/main/Image_Classification_Challenge/Experiments)

The metric used during the competition was the Mean Accuracy, computed as MeanAccuracy = Σ1≤i≤N(predictionsi == targetsi) / N , where N is the total number of images in the test set.
Our final model performed a Mean accuracy of 0.93 on the public test set of the challenge, while on the private test set used for the final evaluation we reach a Mean Accuracy of 0.91.
We provide a [full report](https://github.com/antonio-ercolani/ANNDL_Challenge/blob/main/Image_Classification_Challenge/Report.pdf) of the procudure used during the developement phase as well as the [notebook](https://github.com/antonio-ercolani/ANNDL_Challenge/blob/main/Image_Classification_Challenge/Notebook_best_model.ipynb) of our final model

# Multivariate Timeseries Forecasting challenge
In this challenge we were provided with a dataset of 7 different time series of 7 different variable, and we had to provide predictions in the future of 864 samples. Here you can find the [dataset](https://github.com/antonio-ercolani/ANNDL_Challenge/tree/main/Multivariate_Timeseries_Forecasting_Challenge/dataset)
### Task and results
As mentioned above the task was to predict future 864 samples of the 7 channels, using a Deep Learning approach, in particular we implement Recurrent models which use Long Short Term Memory unit (LSTM) in order to work with sequential data. We also consider a monodimensional convolutional to compare the two approaches results. The metric used during the competition was the Root Mean Squared Error (RMSE).

Our final model performed a RMSE of 3.85 on the private test set of the challenge. To have less noisy evaluation during the process we applied a 10-fold cross validation over our models during the developement.
We provide a [full report](https://github.com/antonio-ercolani/ANNDL_Challenge/blob/main/Multivariate_Timeseries_Forecasting_Challenge/ANNDL_Challenge_Time_Series_Forecasting.pdf) of the procedure as well as our final [notebook](https://github.com/antonio-ercolani/ANNDL_Challenge/blob/main/Multivariate_Timeseries_Forecasting_Challenge/Final_notebook.ipynb) with the implementation
