<h1 align="center">Hi 👋, I'm yousif</h1>
<h3 align="center">A passionate AI student</h3>

<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://instagram.com/yousif_bahnasy" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="yousif_bahnasy" height="30" width="40" /></a>
</p>

<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://www.w3schools.com/cpp/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" alt="cplusplus" width="40" height="40"/> </a> <a href="https://pandas.pydata.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/pandas/pandas-original.svg" alt="pandas" width="40" height="40"/> </a> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> <a href="https://scikit-learn.org/" target="_blank" rel="noreferrer"> <img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit_learn_logo_small.svg" alt="scikit_learn" width="40" height="40"/> </a> <a href="https://seaborn.pydata.org/" target="_blank" rel="noreferrer"> <img src="https://seaborn.pydata.org/_images/logo-mark-lightbg.svg" alt="seaborn" width="40" height="40"/> </a> <a href="https://www.tensorflow.org" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/tensorflow/tensorflow-icon.svg" alt="tensorflow" width="40" height="40"/> </a> </p>

# Slash Fashion Classifier

## Overview
Slash Fashion Classifier is a machine learning project that aims to classify images into two categories: "accessories" and "fashion". It utilizes convolutional neural networks (CNNs) with transfer learning using the ResNet50 architecture.



## Dataset
The dataset consists of images categorized into "accessories" and "fashion". Before using the dataset, it undergoes preprocessing steps such as cropping and splitting into training, validation, and test sets.

## Project Structure
The project is organized as follows:
- Preprocessing: Contains functions for preprocessing the dataset, including cropping images and splitting them into training, validation, and test sets.
- model_training: Defines functions to create image generators, build the model architecture, and train and evaluate the model.
- requirements: Lists all Python dependencies required to run the project.
- slash_model.h5: Pre-trained model weights saved after training.

## Model Evaluation
The trained model is evaluated on the test set to measure its performance in classifying images into the respective categories. Evaluation metrics include loss and accuracy.

## Results
The model achieves an accuracy of [78%] on the test set.

