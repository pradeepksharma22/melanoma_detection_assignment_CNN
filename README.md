# Melanoma detection assignment 
> To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.






## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

> The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.


- The data set contains the following diseases:
    - Actinic keratosis
    - Basal cell carcinoma
    - Dermatofibroma
    - Melanoma
    - Nevus
    - Pigmented benign keratosis
    - Seborrheic keratosis
    - Squamous cell carcinoma
    - Vascular lesion
> Using CNN to classify 9 different skin cancer diseases. This will certainly reduce manual effort and prioritize treatment as timely detection of these diseases is the key.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Augmentation strategy applied to overcome the class imbalance and reducing overfitting, underfitting issues
- Images are normalized between 0-1 and resized to 180*180
- seborrheic keratosis shows minimum number of samples and pigmented benign keratosis have higher number of samples
- Dropout layers are included to reduce overfitting
- The Final model gives below accuracies after 30 epochs
    - Training accuracy - 85.42% 
    - Validation accuracy -  79.14%  

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Pandas - version 1.3.5
- Numpy - version 1.21.6
- tensorflow - version 2.8.2
- keras - version 2.8.0
- matplotlib - version 3.2.2
- seaborn - version 0.11.1
- Augmentor - version 0.2.10

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- This project was based on CNN model to classify skin cancer diseases accurately and is done as a part of Deep Learning module for the Executive PG Programme in Machine Learning & AI - IIIT,Bangalore.


## Contributors
- <a href="https://github.com/pradeepksharma22/">Pradeep Kumar Sharma</a>


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->