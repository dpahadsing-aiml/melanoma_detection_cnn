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
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC).
- The notebook on the assignment includes the following :
    - Data Reading/Data Understanding 
    - Dataset Creation - create train & validation dataset from the train directory with a batch size of 32. Also, resize images to 180*180.
    - Dataset visualisation - visualize one instance of all the nine classes present in the dataset 
    - Model Building & training - creating a custom CNN model for classification of images present in the dataset, including rescaling images to normalize pixel values between (0,1) and choosing an appropriate optimiser and loss function for model training and Training the model for ~20 epochs
    - Chosing an appropriate data augmentation strategy to resolve underfitting/overfitting 
    - Model Building & training on the augmented data
    - Examining the current class distribution in the training dataset and handling class imbalances by rectifying class imbalances present in the training dataset with Augmentor library.
    - Model Building & training on the rectified class imbalance data and Training the model for ~30 epochs


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- The class rebalnce largely improved the overall accuracy during training.
    - the training accuracy improved from 60% to 89~90%
    - the validation accuracy improved from 52 ~ 54% to around 85 ~ 86%
- The overfitting was reduced by use of Dropouts after the convolution layer and the dense classification layer.
    - the gap between the training and validation reduced to ~4%
- Validation Accuracy of the model was hugely improved from 52 ~ 54% to around 85~86% by using data augmentation and class rebalancing.
- Data augmentation added variations of the original image which helped the model generalize the learning.
- Class imbalance can result in bad model performance, which can be addressed by adding a reasonable nos. of augmented images to each class, so that the effect of class imbalance is reduced.




<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used

#### Programming Language & Environment
- Python          
- Jupyter Notebook / Google Colab



<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements



## Contact
Created by [@dpahadsing-aiml]


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->