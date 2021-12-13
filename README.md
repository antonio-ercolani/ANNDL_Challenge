# ANNDL_Challenge
Challenges hosted on CodaLab for the Artificial Neural Networks and Deep Learning course @ PoliMi 2021/2022

## Members
[Antonio Ercolani](https://github.com/antonio-ercolani)  
[Francesco Romanò](https://github.com/romano-francesco)

## Image classification challenge
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
