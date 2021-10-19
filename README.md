## Overview

The goal of this study was to develop a supervised machine learning model that could predict credit risk properly.
 I utilized six distinct approaches to finish this job, which are as follows:

 
- SMOTE Oversampling
- Cluster Centroid Undersampling
- Naive Random Oversampling
- Smoteenn Sampling
- Easy Ensemble Classifying
- Balanced Random Forest Classifying
 

I divided my data into training and testing datasets and generated accuracy scores, confusion matrices, and classification reports as a consequence of each of these approaches.

## Results


### SMOTE Oversampling

* 66.2 percent of accurace score.
* 1 percent of precision high risk.
* 100 percent of precision low risk.
* 66 percent of recall high risk.
* 66 percent of recall low risk.

<img width="570" alt="Review_1" src="https://user-images.githubusercontent.com/83256206/137973709-309f8207-151d-42cc-9294-b051e2419a5a.png">

### Cluster Centroid Undersampling

* 51.3 percent of accurace score.
* 0 percent of precision high risk.
* 100 percent of precision low risk.
* 61 percent of recall high risk.
* 42 percent of recall low risk.


<img width="571" alt="Review_2" src="https://user-images.githubusercontent.com/83256206/137973733-a81a93e0-7f80-4c13-b58b-c4c53f9d8b38.png">


### Naive Random Oversampling

* 67.4 percent of accurace score.
* 1 percent of precision high risk.
* 100 percent of precision low risk.
* 72 percent of recall high risk.
* 63 percent of recall low risk.

<img width="569" alt="Review_3" src="https://user-images.githubusercontent.com/83256206/137973766-78549d79-5d2d-421d-8c20-d71a0171e071.png">

### SMOTEENN Sampling

* 68.1 percent of accurace score.
* 1 percent of precision high risk.
* 100 percent of precision low risk.
* 76 percent of recall high risk.
* 60 percent of recall low risk.


<img width="566" alt="Review_4" src="https://user-images.githubusercontent.com/83256206/137973797-cbf0d610-9c55-42db-a6ba-afa41b041ea1.png">


### Easy Ensemble Classifying

* 92.3 percent of accurace score.
* 6 percent of precision high risk.
* 100 percent of precision low risk.
* 91 percent of recall high risk.
* 94 percent of recall low risk.

<img width="565" alt="Review_5" src="https://user-images.githubusercontent.com/83256206/137973841-603d6e8d-8a8e-4826-b23b-009656322e3f.png">

### Balanced Random Forest Classifying

* 64.8 percent of accurace score.
* 56 percent of precision high risk.
* 100 percent of precision low risk.
* 30 percent of recall high risk.
* 100 percent of recall low risk.

<img width="568" alt="Review_6" src="https://user-images.githubusercontent.com/83256206/137973865-ef0f8ba2-b578-4952-ba8c-c069c4606047.png">



## Summary

This study aims to identify the best model for determining whether a loan is high risk or not. As a result, we need to develop a model that allows the least number of high-risk loans to pass unnoticed. The recall rate for high risk is the corresponding statistic for this. The following models received the highest scores when compared to the others:

1. Easy Ensemble Classifying --> 91%
2. Smoteen Sampling --> 76%
3. Naive Random Oversampling --> 72%

While this is the most relevant figure from this research, recall rate for low risk loans is also essential since it reveals how many low risk loans are identified as high risk. The following models received the highest scores when compared to the others:

1. Balanced Random Forest Classifying --> 100%
2. Easy Ensemble Classifying --> 94%

We can look at the accurary score after we've weighed these two data against the others to get a sense of how well the model performs in general. The following models had the highest accuracy scores:

1. Easy Ensemble Classify --> 92.3%
2. Smoteen Sampling --> 68.1%
3. Balanced Random Forest Classifying --> 64.8%

The Easy Ensemble Classifying model is the model that I would propose for forecasting high risk loans after factoring in these three major data.
