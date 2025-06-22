# Waste Material Segregation for Improving Waste Management

## Objective
The objective of this project is to implement an effective waste material segregation system using convolutional neural networks (CNNs) that categorises waste into distinct groups. This process enhances recycling efficiency, minimises environmental pollution, and promotes sustainable waste management practices.

## The key goals are:

Accurately classify waste materials into categories like cardboard, glass, paper, and plastic.
Improve waste segregation efficiency to support recycling and reduce landfill waste.
Understand the properties of different waste materials to optimise sorting methods for sustainability.


## Table of Contents
* [Data Understanding](#data-understanding)
* [Data Preparation](#data-preparation)
* [Model Building and Evaluation](#model-building)
* [Data Augmentataion](#data-augmentation)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## Data Understanding
- This is a programming assignment in which we build a CNN python model to segregate waste materials.
- Import necessary libraries
- We load and unzip data
  
## Data Preparation
- Load and pre-process the images
- Training and Testing directories
- Visualise sample images
- Encoding different classes
- Creating validation and final training sets
  
## Model Building and Evaluation
- Normal model building with 3 CNN layers
- Model Training
- Testing model on the test set
- Build models using transfer learning (with VGG16 and ResNet50V2). Then training and evaluation on the test set

## Data Augmentation
- Create a Data Augmentation Pipeline
- Train and Evaluate the model on the new augmented dataset
  
## Conclusions (Major)
- The normal convolution model does not give accuracy on test set better than 64%
- The transformation technique with base model as VGG16 provides much better test data accuracy of 76%
- We get even better test data accuracy of 84% with base model as ResNet50V2
- Also, loss in test data set; normal CNN model > base model as VGG16 > base model as ResNet50V2
- The test accuracy is even worse in the augmented dataset: 57%
 
  
## Acknowledgements

- This project was inspired by ML-AI couse at UpGrad and IIIT-B
- References: UpGrad and IIIT-B
- This project was based on [CNN Assignment]([https://learn.upgrad.com/course/5811/segment/60414/369869/1115042/5565470]).


## Contact
Created by [@seetarampandeygit]  - feel free to contact me!
