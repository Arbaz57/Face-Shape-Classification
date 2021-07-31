# Face-Shape-Classification

Human face can be classified into five major categories such as Round, Heart, Square, Diamond, Oval.

![alt text](https://github.com/Arbaz57/Face-Shape-Classification/blob/main/face-shapes.jpg?raw=true)

In this project we will use Different CNN Models to classify shapes into these categories.

Below is the link for our dataset

https://www.kaggle.com/niten19/face-shape-dataset

Our data set consists of 5000 images for five categories.

We will be using 800 images for training and 200 images for testing

<div>
        <table>
            <caption>Accuracy for different models</caption>
            <thead>
                <tr>
                    <th>Model</th>
                    <th>Accuracy</th>
                    <th>Validation Accuracy</th>
                </tr>
                <tr>
                    <td>0.25 Drop Out</td>
                    <td>0.20</td>
                    <td>0.20</td>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>L1 Regularization</td>
                    <td>0.20</td>
                    <td>0.20</td>
                </tr>
                <tr>
                    <td>Inception V3</td>
                    <td>1.00</td>
                    <td>0.80</td>
                </tr>
            </tbody>
        </table>
    </div>



**_Note: In our dataset instead of Diamond we have Oblong  as a feature._**








