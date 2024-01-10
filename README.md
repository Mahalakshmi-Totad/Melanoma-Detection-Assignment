# Project Name
> To build a CNN based model which can accurately detect melanoma. 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

## General Information
- Provide general information about your project here.
- What is the background of your project?
- Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. 
- What is the business probem that your project is trying to solve?
- A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
- What is the dataset that is being used?
- This assignment uses a dataset of about 2357 images of skin cancer types. The dataset contains 9 sub-directories in each train and test subdirectories. The 9 sub-directories contains the images of 9 skin cancer types respectively.


## Conclusions
- Model was able to provide correct prediction on test dataset as seen above in Model Evaluation section
- Most of the problems in the data set were handled using different techniques like Agumentation and Class imbalance handling.
- And by using different filters with dropouts we can see that the best model has :
    - Training accuracy : 0.9493
    - Training loss: 0.1346
    - Validation accuarcy: 0.8441
    - Validation loss : 0.6681


## Technologies Used
- Tensorflow Keras
- Agumentation


