# About the Repo
This is the Github repo for the segmentation and classification models used in the study titled <i>SEGMENTATION AND CLASSIFICATION OF KIDNEY GLOMERULI USING DIFFERENT MACHINE LEARNING MODELS </i>, by Rellos A., Villaflor F., and Yonzon S.

# Dataset Information
The dataset used in this study was obtained from a paper by Bueno et al. (2020) entitled "<i>Glomerulosclerosis identification in whole slide images using semantic segmentation</i>". (DOI: https://doi.org/10.1016/j.cmpb.2019.105273)

# Accessing the Dataset
The dataset used in the training, testing, and validation of the models used in this study is available on the Mendeley Data website:
https://data.mendeley.com/datasets/k7nvtgn2x6/3

<br>
The augmented classification dataset can be accessed via this link:
https://www.dropbox.com/s/ypvbhkgt4sb40sy/dataset_b.zip?dl=0

<b><i>The dataset link above should be used to train the classification models.</i></b>

# Loading the Classification Dataset
The training data can be loaded into the model via a curl command or loaded manually.

```!curl -L "https://www.dropbox.com/s/ypvbhkgt4sb40sy/dataset_b.zip?dl=0" > dataset_b.zip; unzip dataset_b.zip; rm dataset_b.zip```


# Required Libraries
These are the libraries necessary to train the models:

<b> EfficientNet-B0: </b>

Keras

Livelossplot

Numpy

OS module

Tensorflow

<br>

<b> SqueezeNet: </b>

Keras

Livelossplot

Numpy

OS module

Tensorflow

<br>

<b> VGG-16: </b>

Keras

Livelossplot

Numpy

OS module

Tensorflow
