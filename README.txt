# Pneumonia Detection using Deep Convolutional Neural Network

## Overview

Pneumonia is a severe respiratory infection affecting millions globally, leading to high mortality rates, particularly among young children and the elderly. Early diagnosis is crucial for effective treatment. This project employs deep learning, specifically a modified VGG19 model, to accurately classify chest X-ray images as normal or positive for pneumonia.

## Dataset

The Chest X-Ray Images (Pneumonia) dataset is utilized, comprising 5,856 chest X-ray images categorized into normal and pneumonia-positive classes. 

## Model Architecture

The neural network model is based on the VGG19 architecture with key modifications. The model consists of 9 convolutional layers, 4 custom dense layers, and a sigmoid activation function for binary classification. Transfer learning, dropout layers, and hyperparameter tuning are incorporated to enhance performance.

## Experimental Design

The project aims to assess whether the modified VGG19 model outperforms previously used algorithms in pneumonia detection. Key modifications include data augmentation, custom model architecture, transfer learning, and hyperparameter tuning.

## Experiment Results

The model achieved a test accuracy of 91%, outperforming ResNet50 and InceptionV3.

Performance Comparison
Model	         Training Accuracy	  Validation Accuracy	  Test Accuracy
VGG19	             96.25%	                100%	            91%
ResNet50	         86.08%	                81.25%	         77.24%
InceptionV3	       97.97%	                93.75%	         9.26%


-> To run the code:

1) Either the .ipynb file present in the zip folder can be run using Jupyter Notebook on local machine, or can be opened on Google Colab to run it faster with a GPU.
  
   Below is the same notebook file Google Colab link for viewing the results:
   https://colab.research.google.com/drive/1o3KS1cJtNAvEApeOJY0o0PIOFDUhgTeU?usp=sharing

2) The code expects the dataset folder 'chest_xray' to be present in Google Drive's 'MyDrive' folder. 
   For this, we first uploaded the dataset folder to drive and then fetched the dataset by connecting to Google Drive account.
   
   Below is the dataset folder Google Drive link for accessing the dataset:
   https://drive.google.com/drive/folders/1qlOvi2X57JPxK7cFaFTQEM-mExai9MAL?usp=share_link
   
   If the above link to access the dataset doesn't works, then the dataset can be downloaded from Kaggle using the below link:
   https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia
   
   Note: The dataset will need to be imported to the Drive of the google account used, to run the project code.
   
   
   
   
   
   
   
