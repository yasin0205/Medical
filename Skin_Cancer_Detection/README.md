# Melanoma Skin Cancer Detection Using Ensemble Deep Learning Model 

## Overview  
Skin cancer, particularly melanoma, is a life-threatening disease that requires early diagnosis for effective treatment. This project leverages deep learning techniques to develop an ensemble model for detecting melanoma from dermoscopy images. The model integrates **VGG19, ResNet50, and MobileNetV2** using a stacking ensemble approach, achieving high accuracy on the **ISIC 2020 dataset**.

## Features  
- **Ensemble Learning**: Combines multiple deep learning models for improved classification accuracy.  
- **Transfer Learning**: Utilizes pre-trained models (VGG19, ResNet50, MobileNetV2) to extract high-level features.  
- **Data Augmentation**: Improves model robustness using rotation, flipping, and zooming techniques.  
- **Class Imbalance Handling**: Oversampling is used to balance malignant and benign samples.  
- **High Accuracy**: Achieved **99.4% accuracy** in melanoma detection on the ISIC 2020 dataset.  



## Dataset  
- **Source**: [ISIC 2020 Dataset](https://www.kaggle.com/datasets/cdeotte/jpeg-melanoma-256x256)  
- **Size**: 32,126 images  
- **Classes**: Benign (98.24%), Malignant (1.76%)  
- **Preprocessing**: Resized to **224x224**, converted to **BGR**, and normalized  



## Results
Model	Accuracy	Precision	Recall	AUC
VGG19	99.2%	97.6%	96.5%	99.0%
ResNet50	99.5%	98.3%	97.2%	99.2%
MobileNetV2	91.0%	44.9%	94.0%	98.2%
Ensemble	99.4%	94.7%	97.3%	98.4%

##  Contributors
Md Mahbubur Rahman - Oslo Metropolitan University
Quang Dung Martin Phan - Oslo Metropolitan University
Mohammad Azizul Islam Yasin - Oslo Metropolitan University