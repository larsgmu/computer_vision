# Visión por Computador - Computer Vision Lab

This is my repository for the lab part of the subject **Visión por Computador** at **UPV**. One could choose between different projects/problems form [this repository](https://github.com/RParedesPalacios/ComputerVisionLab), where I chose to do the following three projects. All the documentation and explanation is found in *Computer_Vision_Lab.pdf*, while the code/notebooks for each project is named according to the project name.

## Gender recognition
This project started with a code that already had images from "Labeled Faces in the Wild" dataset (LFW) in realistic scenarios, poses and gestures. The project was two parted, where the first part was to create a CNN model with >97% accuracy over test set, while the second part was to implement a model with >92% accuracy with less than 100K parameters. Projectfile: *gender.ipynb*

## Car Model identification with bi-linear models
In this project the goal was to understand the above Keras implementations:
* Name the layers
* Built several models
* Understand tensors sizes
* Connect models with operations (outproduct)
* Create an image generator that returns a list of tensors
* Create a data flow with multiple inputs for the model

The resulting model should be able to identify different car models with accuracy > 65%.

My solution/explanation is found in the documentation, and code is found in *car_model.ipynb*

## Image colorization
In the final project was about image colorization, how you can input a black/white image to your model and output a colorized version. The goals were to understand the above Keras implementations:
* How to load the inception net
* How to merge encoder and inception result

My explanation and how I did it is explained in the documentation, while the full code is in *image_colorization.ipynb*
