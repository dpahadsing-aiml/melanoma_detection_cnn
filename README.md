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
- The dataset consists of housing data for 1460 sales.
- The notebook on the assignment includes data understanding, exploratory data analysis, data splitting for tarining and test, feature scaling, feature selection using RFE, model building using advanced regression involving data transformation & regularization (ridge and lasso), cross validation, hyperparameter tuning, model evaluation including validation of assumptions of linear regression- 


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