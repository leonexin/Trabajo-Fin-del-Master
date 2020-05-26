## Introduction

This repository contains the code and a note of my project from the master's program. In this project, 4 experiments were carried out with 4 different models of deep learning to teach a model that is able to recognize the categories of video materials in the following genres: "Drama", "Chase", "Shootings", "Love and Joy", "Fighting".

## Requirements
* Python3
* Nvidia GPU

##Dataset and Results
Saved trained models, used data set for training and testing can be found at the [GoogleDrive](https://drive.google.com/open?id=1-I8PNd2ubaU4GyXxNVVaPNvSloZ8vcm3)

## Built With

*[Python](https://www.python.org/) - A programming language that lets you work quickly and integrate systems more effectively.

*[TensorFlow](https://www.tensorflow.org/) - The core open source library to help you develop and train ML models.

## Results
* Own CNN model - 0.6 - accuracy, 1.33 - loss
* Pretrained VGG19 with retained last layer block5_conv* - 0.81 - accuracy, 0.61 - loss
* Fine tuning using pretrained VGG19 model with dropout layer - 0.83 - accuracy, 0.6 - locc
* Fine tuning using pretrained VGG19 model without dropout layer - 0.62 - accuracy, 1.03 - loss

##### The results are obtained using a test data set
