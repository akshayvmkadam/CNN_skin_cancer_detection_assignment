# Melanoma Detection Assignment
> In this assignment, we will build a multiclass classification model using a custom convolutional neural network in TensorFlow.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. 
- A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
- Approach: Build a CNN based model which can accurately detect melanoma.
- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.
- The data set contains the following diseases:
    - Actinic keratosis
    - Basal cell carcinoma
    - Dermatofibroma
    - Melanoma
    - Nevus
    - Pigmented benign keratosis
    - Seborrheic keratosis
    - Squamous cell carcinoma
    - Vascular lesion

## Conclusions
- The model continues to overfits but by rebalacing the class, it does resolve the same.
- As the training accuracy increases linearly over time, the validation accuracy also increases in training process.
- As the training loss decreases with epochs, the validation loss decreases significantly.
- The difference in accuracy between training and validation accuracy is less.
- The final CNN model, trained on rebalanced class data with adding extra layers, neurons and dropouts has a training accuracy of 0.9170 and validation accuracy of 0.7832.


## Technologies Used
- pandas
- numpy
- tensorflow
- matplotlib.pyplot
- Augmentor
- Google-Collab


## Acknowledgements
- This project was inspired by Upgrad MS course for ML and AI
- This project was based on [this course](https://www.upgrad.com/masters-in-ml-ai-ljmu/).


## Contact
Created by [@akshayvmkadam] - feel free to contact me!
