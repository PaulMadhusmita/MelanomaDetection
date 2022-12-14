# Project Name
To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis


## General Information
The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

The data set contains the following diseases:

Actinic keratosis
Basal cell carcinoma
Dermatofibroma
Melanoma
Nevus
Pigmented benign keratosis
Seborrheic keratosis
Squamous cell carcinoma
Vascular lesion

## Scope:

Build a baseline CNN model first and tune it on the validation set.

Check for underfitting / overfitting of model and improve it using Augmentation of the training data.

Check for class imbalance of the model and improve it generating more images of each class.

# Conclusion:

Handling class imbalance has definitely helped in improving the accuracy for both Train & Test set. Including Normalization, Augmentation , dropouts and class rebalance has helped overcoming overfitting & underfitting Yet the model has accuracy ~ 70%, and there scope of further improvement which cant be achieved by adding more covulation layers and dropout layers

# Technologies Used

Tensorflow 2.9.2
Keras 2.9.2
Matplotlib 
numpy 
pandas

# Acknowledgements
Give credit here.
- This project was inspired by Upgrad - Convolutional Neural Network Assignment


#Contact
Created by [@PaulMadhusmita] - feel free to contact me!

