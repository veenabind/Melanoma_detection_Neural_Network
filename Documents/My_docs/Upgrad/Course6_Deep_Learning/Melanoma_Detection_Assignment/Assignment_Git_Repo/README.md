# Melanoma Detection
> To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Provide general information about your project here.
The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC).
- What is the background of your project?
The dataset contains images of 9 different cancers. This project is about creating a neural network model to detect Melanoma Cancer images from other cancer images.
- What is the business probem that your project is trying to solve?
To build a CNN based model which can accurately detect melanoma. 
- What is the dataset that is being used?
The dataset consists of 2357 images of malignant and benign oncological diseases

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Model 1 - CNN layers without dropout - This one resulted in overfitting. Gave good accuracy for train data, but underfitted for validation data
- Model 2 - CNN layers with dropout - This one resulted in improved validation accuracy, but still there was overfitting with training data. 
- Model 3 - CNN layers with image augmentation - Class imbalance was handles using image augmentation and this one resulted in ~90% accuracy for training data and ~80% accuracy for validation data.

 
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- library - pandas, numpy, matplotlib, tensorflow, keras, sklearn

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by...
- References if any...
- This project was based on [this tutorial](https://www.example.com).


## Contact
Created by [@veenabind] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->