## Udacity's Data Scientist Capstone Project: Dog Breed Classifier


### Project Overview
This project uses Convolutional Neural Networks (CNNs) and transfer learning in order to build a pipeline to process real-world, user-supplied images. Convolutional Neural Networks (CNNs) are commonly used to analyse image data. Transfer learning is a technique that allows to reuse a model across different tasks. The objective is that given an image of a dog, the algorithm will identify an estimate of the canine’s breed. If supplied an image of a human, the code will identify the resembling dog breed. If the algorithm can't identify the image as a human or dog, it will tell so.


### Libraries

    Keras
    OpenCV
    Matplotlib
    Numpy

### Contents
The project is organized along the following steps:

    Intro
    Step 0: Import Datasets
    Step 1: Detect Humans
    Step 2: Detect Dog
    Step 3: Create a CNN to Classify Dog Breeds (from Scratch)
    Step 4: Create a CNN to Classify Dog Breeds (using Transfer Learning)
    Step 5: Write Your Algorithm
    Step 6: Test Your Algorithm

### Findings

* The model achieved a test accuracy of 81.34%, which is above the 60% established accuracy threshold.
* The model predicted the same two or three breeds when identifying an image as human. Therefore more variety is needed concerning the type of breeds the model predicts for humans. 
* Some of the breeds have similar colors and shapes but differ in size, as is the case between a Beagle and a Pointer or American Foxhound. Therefore the model needs to pick up subtle differences between similar breeds. 
* The model could use some improvements on its ability to classify pictures with noise. This is probably due to the images it was trained on.
