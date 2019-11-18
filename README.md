# convolutional-neural-network_kaggle-competition

Here is the code of my first Convolutional Neural Network for my first Kaggle competition. 

## Getting started

In order to clearly see the code and the outputs, I strongly recommand you to go directly on my notebook on Kaggle at this [address](https://www.kaggle.com/fabien92r/roussel-projet-deep-learn-ensembling). You will also find the dataset. 

## Objectives

The goal of this notebook is to classify photos of animals (32x32 pixel images) with a CNN without using deeper neural networks as Resnet.

The given dataset is composed of a training set of 7200 pictures and test set of 1800 pictures(80%-20%).

## Appoach

Due to the bad quality of the images, I choose to resize them to 64x64 because it allowed to have more features and therefore more information at the expense of the calculation time. 

In order to taste assembling, I chose to defined 5 different models, each more or less complex. After using data augmentation on the training set, I train each model and create an ensemble model which take the five first and compute the average of the probabilites for each class for a given picture. 

I succeeded in obtaining 68% accuracy on the test set which is not very satisfying but is promising for the upcoming changes.

## Improvement of the models

*Upcoming..*

## Author

* **Fabien Roussel** - *Initial work* - [GitHub](https://github.com/FabienRoussel) [LinkedIn](https://www.linkedin.com/in/fabien-roussel/)