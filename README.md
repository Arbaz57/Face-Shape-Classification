# Face-Shape-Classification

Human face can be classified into five major categories such as Round, Heart, Square, Diamond, Oval.

![alt text](https://github.com/Arbaz57/Face-Shape-Classification/blob/main/face-shapes.jpg?raw=true)

In this project we will use Different CNN Models to classify shapes into these categories.

Below is the link for our dataset

https://www.kaggle.com/niten19/face-shape-dataset

Our data set consists of 5000 images for five categories.

We will be using 800 images for training and 200 images for testing



**CNN model with 0.25 dropout:** loss: 1.6096 - accuracy: 0.2032 - val_loss: 1.6095 - val_accuracy: 0.2000

**CNN model with L1 regularization:** loss: 11.1937 - accuracy: 0.2032 - val_loss: 11.2870 - val_accuracy: 0.2000

**CNN model with Inception_V3 for feature learning:** loss: 0.0013 - acc: 1.0000 - val_loss: 0.8679 - val_acc: 0.7643

**_Note: In our dataset instead of Diamond we have Oblong  as a feature._**








