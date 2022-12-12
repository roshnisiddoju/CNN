# Project Name
> Melanoma Detection Assignment.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.
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


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Conclusion 1 from the analysis : We see that seborrheic keratosis data has very less samples, where as pigmented benign keratosis has more number of samples
- Conclusion 2 from the analysis : From the bar plot, it is obeserved that there is a class imbalance
- Conclusion 3 from the analysis : First model shows that with the train and validation accuracy, it is observed that the train accuracy is more while the validation accuracy is very less.This model is definetly overfitting. This overfitting might be because of class imbalance
- As we saw overfitting problem, in the next steps Im trying to implement data augmentation strategy to solve the class imbalance
- CNN model-3 using drop outs we saw that validation accuracy score increases

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python 3.2
- library - pandas
- library - numpy
- library - matplotlib.pyplot
- library - seaborn
- library - os
- library - pathlib
- library - PIL
- library - tensorflow
- library - Augmentor
- library - keras
- library - Adam
- library - Sequential



## Analysis done by Roshni Siddoju
The following file are added to the GIT
RoshniSiddoju_CNN_Assignment.ipynb