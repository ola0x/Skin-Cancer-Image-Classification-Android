# Skin-Cancer-Image-Classification-Android
* 10015 images were trained using Tensorflow with an accuracy of 73.3%, still improving 

### Clone the respository
* The trained model is in the assets folder

## Problem Statement
+ In Nigeria Skin cancer is common and appears due to the unprecedented growth of the skin cells inside the body. It reaches the outer layer of skin which is epidermis. It evolves as a blister or a cut in the skin.
+ The cost of cancer treatment in Nigeria ranges from N850,000 to N2,875,000; and between $10,000 (about N3,600,000 using N360 to $1) and $60,000 (N21,000,000). 
+ Basal cell and squamous cell carcinomas, the two most common forms of skin cancer, are highly curable if detected early and treated properly
+ The five-year survival rate for people whose melanoma is detected and treated before it spreads to the lymph nodes is 99 percent.
If we can detect the type of skin cancer in early stages, we can save almost every victim. This cancer classification model can help healthcare organizations especially in developing countries to improve their services and reduce their costs for the patients.

## What it does
A Machine learning model was created CNN(Convolutional neural network) using Transfer Learning, built under Keras with TensorFlow 1.14.0 as the backend and an android app to detect the seven major types of skin cancer namely:
+ Actinic keratoses and intraepithelial carcinoma / Bowen's disease (akiec)
* Basal cell carcinoma (bcc)
* Benign keratosis-like lesions (solar lentigines / seborrheic keratoses and lichen-planus like keratosis), (bkl)
* Dermatofibroma (df)
* Melanoma (mel)
* Melanocytic nevi (nv)
* Vascular lesions (angiomas, angiokeratomas, pyogenic granulomas and hemorrhage, vasc).

## How it was built
* We selected the skin cancer dataset from Harvard Dataverse (https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DBW86T)
* Based on the metadata, we separated the 10015 image files into sub categories and created training and validation datasets.
* Created the CNN model using transfer learning 

## What is Transfer learning
* Transfer learning is a machine learning method where a model developed for a task is reused as the starting point for a model on a second task
* The benefits of Transfer Learning are that it can speed up the time it takes to develop and train a model by reusing these pieces of already developed models. This helps speed up the model training process and accelerate results.
* [Furtther reading](https://medium.com/kansas-city-machine-learning-artificial-intelligen/an-introduction-to-transfer-learning-in-machine-learning-7efd104b6026)

## Technology Stack
* Keras
* TensorFlow - Google's DeepLearning Framework
* Model Architecture Inception v3 (mobilenet_100_224)
* Android Studio

## Features
* Offline Classification

## To know more about skin cancer visit
+ [Travcure](https://www.travcure.com/index.php/all-about-skin-cancer)