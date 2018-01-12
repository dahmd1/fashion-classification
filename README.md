# fashion-classification
Multi-class classification of the Fashion-MNIST dataset (provided by the Zalando research team)
 using Neural Networks.

## Developing environment
* Anaconda 5.0.1
* Python 3.6

## Dataset
The dataset used is available here :
https://www.kaggle.com/zalando-research/fashionmnist/data

## Getting started
To get the code running you need to install the following libraries using pip or conda
* Keras
* scikitimage
* scikitlearn

## Demo
A pretrained cnn model  (best_cnn.h5) is available download it and run the demo Jupyter Notebook
(fashion_classification_demo.ipynb).

## Algorithm Description
Implementation of several neural networks models (MLP and CNN).

## Benchmark

| Model | Accuracy | Average inference time (in seconds) |
|MLP : 3 fully connected layers, 669 K parameters| 0.899 |0.595|
|CNN : 4 convolutional layers,190K parameters| 0.9183 |0.022|

## Acknowledgments
 The code is based on some prior work including :
https://arxiv.org/abs/1409.1556
