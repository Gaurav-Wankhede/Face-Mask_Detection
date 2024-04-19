# Face Mask Detection using OpenCV and MobileNet 🎭🔍

Welcome to my project! I have developed a face mask detection system using OpenCV and MobileNet. This project is designed to promote mask-wearing by providing a machine learning tool that can detect face masks on people in images and webcam streams. 📸💻

## Project Overview 📝

This project employs TensorFlow and OpenCV to detect human faces and proper mask wearing. It's trained on MobileNetV2, a state-of-the-art lightweight deep learning model on image classification, making the app computationally efficient to deploy to help control the spread of diseases. 🦠🌐

## Problem Statement 🎯

The system aims to promote wearing masks by providing a classifying machine learning tool using OpenCV and TensorFlow to detect facemasks on people. The objective is to create a system which is easy to implement in any existing organizational system and to identify the person on image/video stream wearing a face mask with the help of computer vision and deep learning algorithm. 🖥️🔬

## Methodology 📚

The methodology for the project is divided into 3 steps:

1. **Dataset Collection**: The dataset was collected from Google and Kaggle Repository and was split into training and testing data after its analysis. 🗂️
2. **Training a model to detect face masks**: A default OpenCV module was used to train the model to identify face mask. 🎭
3. **Detecting the person not wearing a mask**: After training the model, it was deployed through MobileNet to detect person with or without masks. 🚫🎭

## Scope and Feasibility 🌐

With the increasing risk of contagious diseases all over the world, a system to replace humans to check masks on the faces of people is greatly needed. This system satisfies that need and can be employed in public places like railway stations, malls, offices, hospitals/healthcare organizations, airports, sports venues, entertainment and hospitality industry, and densely populated areas. 🏥🏢🏟️

## Hardware & Software Requirements 💻

Implementation of this system needs a PC with RAM of 8 GB or above, minimum storage of 250 GB and Architecture of 32 or 64 bit. Software requirements will be operating system windows or linux or mac os based. Programming language will be python implemented in command prompt for data pre-processing and model training. 🖥️🐍

## Methodology (ML Algorithm Description) 🧠

This system is capable to train the dataset of both persons wearing masks and without wearing masks. After training the model the system can predict whether the person is wearing the mask or not. It can access the webcam and predict the result. Python modules used in the project are OpenCV, TensorFlow Framework, Keras, Numpy, and Matplotlib. 📊📈

## Implementation 🛠️

The implementation part involves installing the dependencies present in requirement.txt file, collecting dataset from various Google and Kaggle, data pre-processing, training the model, and finally model deployment and output. 📝🔧

## Model Deployment 🚀

In this part, we will use openCV for face detection. We will define a function using all three objects and will return the function with attributes location and prediction. Location gives the x,y coordinates of rectangle surrounding the face and prediction gives the accuracy of person wearing the mask. The result will be percentage of each category predicted. Finally, we use color attribute for more comprehension of the result. If the label says, mask then the value of green color is increased else the value of red color is increased. 🟢🔴

Now, let's run the model and see the output! 🎉
