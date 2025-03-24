# CNN_Melanoma_Detection

# Project Name
> To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
Melanoma is the most dangerous form of skin cancer, accounting for approximately 75% of all skin cancer deaths. Early detection significantly improves patient outcomes, as melanoma is highly curable when identified in its initial stages. However, manual examination by dermatologists can be time-consuming and subject to human error.

This project aims to develop a Convolutional Neural Network (CNN) model that can automatically detect melanoma from skin lesion images. By leveraging deep learning techniques, the model can potentially assist medical professionals in screening large numbers of images efficiently, reducing the workload and improving diagnostic accuracy.

The dataset used for this project is the ISIC (International Skin Imaging Collaboration) skin cancer dataset, which contains a diverse collection of dermoscopic images of skin lesions across multiple diagnostic categories. The dataset includes multiple classes of skin conditions, with melanoma being one of the primary focus areas.

## Conclusions
- The implemented CNN model achieved a training accuracy of approximately 55-60% and validation accuracy of 50-55%, indicating reasonable performance but with room for improvement.
- Data augmentation techniques significantly helped in addressing class imbalance and reducing overfitting, though the model still shows signs of slight underfitting.
- The model architecture demonstrated the ability to learn relevant features from skin lesion images, but adding more convolutional layers or increasing filter sizes could potentially improve performance.
- Extending the training duration and implementing more sophisticated regularization techniques might further enhance the model's generalization capabilities.

## Technologies Used
- TensorFlow 2.x
- Keras 2.x
- Python 3.7+
- Augmentor 0.3.0
- Matplotlib 3.x
- NumPy 1.x
- Pandas 1.x

## Acknowledgements
- This project was inspired by the need for automated skin cancer detection tools in medical settings.
- The dataset used in this project is from the International Skin Imaging Collaboration (ISIC) Archive.

## Contact
Created by [@SaadTeli] - feel free to contact me!
