# Melanoma Detection

**Problem statement:**
To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

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

NOTE:

* You don't have to use any pre-trained model using Transfer learning. All the model building processes should be based on a custom model.
* Some of the elements introduced in the assignment are new, but proper steps have been taken to ensure smooth learning. You must learn from the base code provided and implement the same for your problem statement.
* The model training may take time to train as you will be working with large epochs. It is advised to use GPU runtime in [Google Colab](https://colab.research.google.com/).

## General Information
- Understanding Data
- Creation of Dataset
- Visualisation of Dataset
- Building and Training the Model 
- Choosing the appropriate data Augmentation strategy to resolve underfitting/overfitting
- Building and Training the Model on Augmented Data
- Class Distribution
- Class Imbalance Handling 
- Model Building and Training on the class imbalance data

## Conclusions
#### What we have observed as final result by using:
- Augmentation
- Rebalance
- Dropout
- Batch Norm 
**Final Observation about Model Accuracy:**
- Final Train Accuracy = 0.6150
- Validation Accuracy = 0.5123
- Test Accuracy = 0.3644

## Technologies Used
- Pathlib
- Tensorflow
- Matplotlib
- Numpy
- Pandas

## Acknowledgements
- Developed as part of the Deep Learning module required for Post Graduate Diploma in Machine Learning and AI - IIIT,Bangalore

## Contact
Created by Amit Kumar [@4amitnarayan]