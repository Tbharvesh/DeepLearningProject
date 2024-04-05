# X-ray Image Classifier Model


![Deep Learning](https://img.shields.io/badge/Deep-Learning-blue)
![Python](https://img.shields.io/badge/Language-Python-green)
![TensorFlow](https://img.shields.io/badge/Framework-TensorFlow-orange)

## Project Overview

This project aims to develop a deep learning model capable of classifying chest X-ray images into three distinct categories: COVID-19, Viral Pneumonia, and Normal. By leveraging a curated dataset of chest X-ray images, this model intends to assist in the rapid and accurate diagnosis of respiratory conditions, contributing to better healthcare outcomes.

## Dataset Description

The dataset, sourced from Kaggle, comprises a well-structured collection of chest X-ray images divided into training and testing sets across three categories: COVID-19, Viral Pneumonia, and Normal chest X-rays.

- **Dataset Source:** [COVID-19 Image Dataset on Kaggle](https://www.kaggle.com/datasets/pranavraikokte/covid19-image-dataset/data)
- **Structure:** The dataset is organized into 'test' and 'train' directories, further subdivided into respective classes corresponding to the condition depicted in the images.
- **Contents:** It contains approximately 137 cleaned images of COVID-19 cases and a total of 317 images including Viral Pneumonia and Normal Chest X-Rays. The dataset is meticulously prepared to facilitate machine learning model training and testing.

## Preprocessing Steps

To optimize the dataset for effective model training, several preprocessing techniques are applied to the images:

1. **Resizing and Rescaling:** Images are resized to a uniform dimension to ensure consistency. Additionally, pixel values are normalized to facilitate model processing.
2. **Data Augmentation:** To enhance the dataset and improve model robustness, various transformations such as flipping, rotation, and blurring are applied to the images, creating a more diverse training set.
3. **Noise Reduction:** While noise reduction is a common preprocessing step, its application is carefully considered in this project. Given the critical nature of medical images, any technique that potentially obscures relevant details is cautiously evaluated. The team is exploring noise reduction methods that maintain the integrity and diagnostic value of the images.

## Technologies Used

This project utilizes several key technologies in the field of deep learning and data science:

- **Python:** A versatile programming language that serves as the backbone for implementing the model and preprocessing data.
- **TensorFlow:** An open-source deep learning framework used for building and training the neural network model. TensorFlow provides the tools necessary for high-performance numerical computation, essential for processing complex datasets like medical images.
- **Deep Learning:** The project leverages deep learning algorithms to analyze and classify X-ray images accurately. These algorithms enable the model to learn from the vast amounts of data and make predictions or classifications based on its learning.

## Conclusion

The X-ray Image Classifier Model project represents a significant step towards harnessing the power of machine learning in medical imaging. By accurately classifying chest X-rays into categories indicative of specific respiratory conditions, this model aims to support healthcare professionals in delivering timely and precise diagnoses.
