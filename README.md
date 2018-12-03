# 475project
The final project of EECS 475 from Northwestern University

Content:

Author:

Time:

version:

## 1. Background

## 2. Convolutional Neural Network
Convolutional neural network (CNN) is a class of deep, feed-forward artificial neural network applied to analyzing visual  imagery using a variation of multilayer perceptrons designed to require minimal preprocessing. In our project, a CNN called  AlexNet was applied, which improves it performance by deepening its model.  
We acquired 29,000 color pictures of American sign language (ASL) from the database, 1,000 for each of 29 characters  (including alphabet A to Z, space, delete and nothing). 800 pictures for each character are randomly selected to train the  models, while the rest are used for testing it. The results indicates that the models performed well.  
However, when applied to ASL photo taken by ourselves, the models did not achieve a high accuracy. As far as we are concerned,  several factors including illumination intensity, color of the background, position and size of the hand may  contribute to the uncertainties.
## 3. Gray Processing
In order to improve the performance, we transformed all RGB images used for training and testing into grayscale images with  weighted average. Taken photos are processed with the same method. The results turned out to be significantly better than  those without preprocessing.
## 4. Real-time Recognition
By making use of computer vision (CV), we realized real-time recognition of ASL, where the sign languages are photographed by  the camera of the computer and simultaneously recognised by the trained models. That function enables inputing a sequence of  characters into the computer by performing ASL.
