# Melanoma Detection Assignment
> Research and apply techniques to build a multiclass classification model using a custom convolutional neural network in TensorFlow.
> Subject is to determine the classification of skin cancer.


## Table of Contents
1. [General Info](#general-information)
2. [Describer data class](#data-type-of-skin-cancer)
3. [Approach Method](#approach-method)
4. [Conclusions](#conclusions)
5. [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
>
- Based on the knowledge learned about neural networks. We will use the CNN network as a classification tool to identify diseases based on images.
> 
- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

## Data type of Skin-cancer
- The data set contains the following diseases:

> Actinic keratosis
Basal cell carcinoma
Dermatofibroma
Melanoma
Nevus
Pigmented benign keratosis
Seborrheic keratosis
Squamous cell carcinoma
Vascular lesion

## Approach method
- Our approach is as follows:
>1. Load data and get an overview of its size
>2. See through data imbalances. 
>3. Check if the classes of the training and testing sets are the same or not
>4. Build a basic CNN model for preliminary evaluation of the model
>5. Continue to develop the above model by adding layers: Batch normalization and Dropout
>6. Perform data balancing, data generation.
>7. Use the model in step 5 to re-evaluate the results.
>8. Build a new model without sequence layers and compare with the model in step 7.
>9. Analysis of 2 obtained models
>10. Conclusion

## Conclusions
- The two most optimal modles have quite good results on the training and validation sets, but when applied to the actual test data, the results are not good.
- Subjective reasons may be due to relatively little data provided. The fact that Augment data is not really good
- Objective reasons may not have designed the appropriate model

## Acknowledgements
- Learn about skin cancer classification and classification techniques with neural networks


## Contact

Created by : Pham Van Thai: phamthai.ats@gmail.com</br>Feel free to contact us!
- We do not have any constraints about License on the use of our results. You can use it for free.