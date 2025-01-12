# Melanoma Detection Assignment
> To build a CNN based model which can accurately detect melanoma


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. 
It accounts for 75% of skin cancer deaths. 
A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). 
All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

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
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions

Based on the plots, it appears that overfitting has been significantly reduced.

Validation Accuracy: 
The validation accuracy now closely follows the training accuracy, 
indicating that the model is generalizing well to unseen data. 
The gap between training and validation accuracy has narrowed considerably.
Validation Loss: The validation loss continues to decrease and remains relatively close to the training loss, 
suggesting that the model is not overfitting to the training data.
Did class rebalancing help?

It's difficult to definitively say whether class rebalancing alone helped without more specific information. 
However, given the improved overall performance and the reduced overfitting, 
it's likely that class rebalancing played a positive role. 
By addressing class imbalances, the model can learn more effectively from all classes, 
leading to better generalization.

Additional Considerations:

Augmentation: 
The data augmentation techniques implemented likely played a significant role in reducing overfitting. 
By introducing more variations in the training data, 
the model becomes more robust and less prone to memorizing specific training examples.
Model Architecture: 
The chosen CNN architecture might also have a significant impact on the model's performance and tendency to overfit. 
Experimenting with different architectures can help further improve results.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
pathlib
tensorflow
matplotlib.pyplot
numpy
pandas
os
PIL
tensorflow

## Contact
Created by [@githubusername] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
