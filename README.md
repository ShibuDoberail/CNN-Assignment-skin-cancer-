# CNN-model-for-skin-cancer
This project is to build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

## Table of contents 
The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.
- Importing all the important libraries
- Data reading from google drive and understanding
- Load using keras.preprocessing
- modle-1
- model-2
- model-3
- The data set contains the following diseases:
Actinic keratosis
Basal cell carcinoma
Dermatofibroma
Melanoma
Nevus
Pigmented benign keratosis
Seborrheic keratosis
Squamous cell carcinoma
Vascular lesion

## Conclusions
- Batch Size 32 have been used and images have been resized to 180 x 180.
- Total three custom models have been build in the notebook.
- Model 1: First model shows a sign of Overfitting with high accuracy but low validation accuracy.
- Model 2: Second model shows a sign of Underfitting with low accuracy. It is possibly due to the data imbalanced.
- Model 3: Final model showing promising results with good accuracy and validation accuracy. Augmentor library has been used to increase the sample data since there was data imblance.

## Acknowledgements
I would like to thank Upgrad and IIIT Bangalore.


## Contact
Created by Shibu Doberial 
