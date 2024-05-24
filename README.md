# Shailendra Chouhan
## Multiclass classification model using a custom Convolutional Neural Network in TensorFlow.
Problem statement:
To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

The data set contains the following diseases: Actinic keratosis,Basal cell carcinoma,Dermatofibroma,Melanoma,Nevus,Pigmented benign keratosis,Seborrheic keratosis,Squamous cell carcinoma and Vascular lesion.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
  

<!-- You can include any other section that is pertinent to your problem -->

## General Information
In this work we have build a multiclass classification model using a custom convolutional neural network in TensorFlow. It is a CNN based model which can accurately detect melanoma. 
For the training and testing of the model,the dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). The data set contains the following diseases:

Actinic keratosis

Basal cell carcinoma

Dermatofibroma

Melanoma

Nevus

Pigmented benign keratosis

Seborrheic keratosis

Squamous cell carcinoma

Vascular lesion

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Conclusion 1 from the analysis:
  
 Basic Model was overfitting due to less number of images for training and prsence of class imbalance.
  
- Conclusion 2 from the analysis:
  
Data Augmentation techniques like random flipping, rotation etc helped in removing the overfitting but the overall accuracy of the model could not   be improved due to class imbalance.
  
- Conclusion 3 from the analysis:
  
  Augmentation of class data with addition of 500 images in each class improved the class balance significantly and it is reflecting in the good     training and validation accuracy.
  
- Conclusion 4 from the analysis:
  
  Batch Normalisation even with batch sizes of 32,64 and 128 doesn't seems to improve the validation accuracy. Batch normalisation was attempted   across layers but none of such experiments could result in stable model.
  
- Conclusion 5 from the analysis:

  Various combination of Convolutional layers had been attempted but model with 2 no. Convolutional layers of 32 filters, one with 64 filters and one   128 filters followed by flattened layer and dense layer with 256 neurons seems doing fine both on simplicity and accuracy parameters.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Pandas Version is: 2.1.4
- Numpy Version is: 1.26.4
- Tensorflow Version is: 2.16.1
- Keras Version is: 3.3.3

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- This project was based on course on AIML from IIIT, Bangalore.
- Would like to extend my sincere thanks to the course coordinator and all faculty members of the Institute.


## Contact
Created by [shailu20aug@gmail.com] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
