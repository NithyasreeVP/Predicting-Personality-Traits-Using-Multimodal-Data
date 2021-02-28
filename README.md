
# Predicting Personality Traits Using Multimodal Data
Fachpraktikum Machine learning and Computer vision laboratory for Human Computer Interaction <br>
Author 1: Nithyasree Vivekanandham Pushpalatha - st169653@stud.uni-stuttgart.de <br>
Author 2: Priyadarshini Krishna Shobha - st169614@stud.uni-stuttgart.de


## Reference
1. Main paper to be cited ([Juan et al., 2016](http://www.eecs.qmul.ac.uk/mmv/datasets/amigos/doc/Paper_TAC.pdf))


```
@article{correa2018amigos,
  title={Amigos: A dataset for affect, personality and mood research on individuals and groups},
  author={Correa, Juan Abdon Miranda and Abadi, Mojtaba Khomami and Sebe, Niculae and Patras, Ioannis},
  journal={IEEE Transactions on Affective Computing},
  year={2018},
  publisher={IEEE}
  doi={10.1109/TAFFC.2018.2884461}
}
```
## Abstract

With the increase need of personalisation, the recognition of personality traits have become crucial in making human computer interaction more user friendly and realistic. The ability to detect the personality from neuroscientific data emphasizes on the importance of neurobiological basis of personality. This paper focuses on classifying the personality traits using the AMIGOS dataset. The physiological and gaze features are extracted from the given dataset and three different machine learning models are trained to predict the Big-Five personality traits. The importance of multimodal data in personality recognition are briefly discussed and the performance of the classifier in terms of F1-Score and accuracy for both individual and fusion modalities are presented.


# Introduction

The aim of this project is to predict personality traits based on multimodal data using AMIGOS dataset consisting videos and biological signals like Electroencephalogram (EEG), Galvanic Skin Response (GSR) and Electrocardiogram (ECG). We firstly extract the gaze features from videos and physiological features from biological signals. Next, we apply machine learning algorithms like Random Forest (RF), Support Vector Machines (SVM) and eXtreme Gradient Boost (XGBoost) and different feature selection methods to personality recognition framework which performs binary classification of the Big-Five personality traits in the individual setting.

## Requirements

* Python 3
* BioSPPy
* PyEMD
* SciPy
* scikit-learn
* XGBoost
* OpenFace

## Dataset:

This is provided by the department (from [Juan et al., 2016]) and is present in the GPU1 of the department.

## Overview:

Personality recognition frame-work

![Flow_chart1](/uploads/624def57ab1599fd8d9f31d2c16d9dfc/Flow_chart1.png)


## Repo Usage:

For detailed explaination of how to use the repository, please refer the Project_How_To document


## Acknowledgement:
<body> <a> Reference Repository </a> <a href="https://github.com/pokang-liu/AMIGOS/blob/master/main.py"> -  Repo </body> <br>
<body> <a> Code for equation of circle </a> <a href="https://www.geeksforgeeks.org/equation-of-circle-when-three-points-on-the-circle-are-given/"> -  Pupil Diameter </body> 


 

