# Analysis-of-image-classification-using-tensorflow-example-
to analyze the basic methods and their functioning , using fashion MNIST dataset

What is image classification?
A common use of machine learning is to identify what an image represents. For example, we might want to know what type of animal appears in the a photograph.

Training, labels, and inference
During training, an image classification model is fed images and their associated labels. Each label is the name of a distinct concept, or class, that the model will learn to recognize.

Given sufficient training data (often hundreds or thousands of images per label), an image classification model can learn to predict whether new images belong to any of the classes it has been trained on. This process of prediction is called inference.

To perform inference, an image is passed as input to a model. The model will then output an array of probabilities between 0 and 1


Here I have created the multiclass image classification using Tensorflow and Keras , with fashion_mnist dataset 

you can download the dataset externally also from kaggle : https://www.kaggle.com/zalando-research/fashionmnist

Customize model

The pre-trained models we provide are trained to recognize 1000 classes of image.  

You can use a technique known as transfer learning to re-train a model to recognize classes not in the original set. For example, you could re-train the model to distinguish between different species of tree, despite there being no trees in the original training data. To do this, you will need a set of training images for each of the new labels you wish to train.
