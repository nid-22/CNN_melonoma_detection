# Melonoma detection using Convolutional Neural Network

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)



## General Information
- This project aims to build a multiclass classification model using a custom convolutional neural network (CNN) in TensorFlow to accurately detect melanoma, a deadly type of skin cancer.
- The dataset used for this project consists of 2357 images of malignant and benign oncological diseases, including melanoma, obtained from the International Skin Imaging Collaboration (ISIC).
- The goal is to develop a solution that can evaluate images and alert dermatologists about the presence of melanoma, thereby reducing manual effort needed in diagnosis.
  
- Background:
Melanoma accounts for 75% of skin cancer deaths and can be deadly if not detected early. Early detection of melanoma is crucial for successful treatment. However, manual diagnosis of melanoma from images can be time-consuming and prone to errors. Therefore, building an accurate and automated detection model using machine learning techniques can assist dermatologists in diagnosing melanoma more efficiently.

- Business Problem:
The business problem addressed by this project is the accurate detection of melanoma from skin images using machine learning. By developing a CNN-based model, dermatologists can potentially diagnose melanoma more quickly and accurately, leading to earlier detection and better treatment outcomes for patients.

- Dataset Used:
The dataset used in this project consists of 2357 images of malignant and benign oncological diseases, obtained from the International Skin Imaging Collaboration (ISIC). The dataset contains images of various diseases, including melanoma, actinic keratosis, basal cell carcinoma, dermatofibroma, nevus, pigmented benign keratosis, seborrheic keratosis, squamous cell carcinoma, and vascular lesion. Each class has a different number of samples, with melanoma being one of the classes of interest due to its significance in skin cancer diagnosis.



## Conclusions
- By training a custom CNN model on the original dataset, it was observed that the model suffered from overfitting, as evidenced by a high training accuracy and low validation accuracy.
- Data augmentation techniques were applied to address overfitting and improve model generalization. After training the model on augmented data, there was a significant improvement in validation accuracy, indicating that the overfitting issue was mitigated.
- Class distribution analysis revealed that some classes had significantly fewer samples compared to others, indicating class imbalances in the dataset.
- Class imbalance was rectified using the Augmentor library, which generated additional augmented samples for classes with fewer samples. After training the model on the rectified class imbalance data, there was a notable improvement in model performance and class-wise accuracy.




## Technologies Used
- TensorFlow - version 2.0
- Augmentor - version 0.2.8


