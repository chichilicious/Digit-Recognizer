# Visualisation of hidden Layers 

This repository contains implementation of a sequential model on the MNIST dataset along with the plot and visualization of hidden layers.

## Dataset

The MNIST database is a dataset of handwritten digits. It has 60,000 training samples, and 28,000 test samples. Each image is represented by 28x28 pixels, each containing a value 0 - 255 with its grayscale value.

## Model
This is a sequential model with three dense layers and some dropouts to avoid overfitting.

## Hidden layers Visualization
I've used the weights of my model to build a new model that is truncated at the layer I want to read. And then I used TSNE and Bokeh to extract and visualize the embeddings of hidden layer data.

![](https://github.com/chichilicious/Digit-Recognizer/blob/master/bokeh_plot.png)


