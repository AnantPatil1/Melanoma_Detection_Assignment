# Melanoma Detection Assignment
> In this assignment, we have build a multiclass classification model using a custom convolutional neural network in TensorFlow. 


## Table of Contents
* [Problem statement](#problem-statement)
* [Project-pipeline](#project-pipeline)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#Acknowledgements)


## Problem Statement

### Business Understanding

The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

The data set contains the following diseases:

- Actinic keratosis
- Basal cell carcinoma
- Dermatofibroma
- Melanoma
- Nevus
- Pigmented benign keratosis
- Seborrheic keratosis
- Squamous cell carcinoma
- Vascular lesion


## Project Pipeline
- Data Reading/Data Understanding
- Dataset Creation
- Dataset visualisation
- Model Building & training 
- Chose an appropriate data augmentation strategy to resolve underfitting/overfitting
- Model Building & training on the augmented data
- Class distribution
- Handling class imbalances
- Model Building & training on the rectified class imbalance data


## Technologies Used
- Keras
- TensorFlow
- Python 3
- Pandas, Numpy, Matplotlib,
- Augmentor


## Conclusions

In the final model, there is no sign of underfitting/overfitting.
Class rebalanced improved the model performance on both training and validation data
In 30 epochs, the final model is able to achieve 76.8% training accuracy and 73.8% validation accuracy.
The low difference between the training accuracy and validation accuracy signifies that the final CNN model is able to generalize well.
Inclusion of batch normalization is degrading the accuracy of the final model, hence it is not used.

##Acknowledgements
- https://seaborn.pydata.org/
- https://plotly.com/
- https://www.tensorflow.org/
- https://matplotlib.org/
    
    






