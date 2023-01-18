# Melanoma Detection Assignment

### Problem statement
**To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.**

> The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.


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


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC).
- The notebook on the assignment includes the following :
    - Data Reading/Data Understanding 
    - Dataset Creation - Create train & validation dataset from the train directory with a batch size of 32. Also, resize images to 180*180.
    - Dataset visualisation → Create a code to visualize one instance of all the nine classes present in the dataset 
    - Model Building & training - Creating a custom CNN model for classification of images present in the dataset, including rescaling images to normalize pixel values between (0,1) and choosing an appropriate optimiser and loss function for model training and Training the model for ~20 epochs
    - Chosing an appropriate data augmentation strategy to resolve underfitting/overfitting 
    - Model Building & training on the augmented data
    - Examining the current class distribution in the training dataset and handling class imbalances by rectifying class imbalances present in the training dataset with Augmentor library.
    - Model Building & training on the rectified class imbalance data and Training the model for ~30 epochs


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Data has non-liniear relationship and data transformation was carried out to account for the same.
- Between Ridge and Lasso, Lasso Regressor performed slighlty better.
- Validation of assumptions of linear regression was successful
- Model performance between Training and Test data set was comparable.
- Hence it can be concluded as a good machine learning model with generalization and no overfitting.




<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used

#### Programming Language & Environment
- Python           - version 3.9.13
- Jupyter Notebook - version 6.4.12

#### Libraries
- numpy            - version 1.23.2  for array manipulation
- pandas           - version 1.4.3   for data manipulation
- matplotlib       - version 3.5.3   for plotting
- seaborn          - version 0.11.2  for plotting
- scikit-learn     - version 1.1.2   for advanced regression related work

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements



## Contact
Created by [@dpahadsing-aiml] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->