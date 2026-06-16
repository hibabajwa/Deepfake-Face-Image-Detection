# Deepfake Face Image Detection Using Machine Learning

This project detects whether a face image is Real or Fake using machine learning and deep learning techniques.

## Project Overview

Deepfake technology uses artificial intelligence to generate realistic fake images, videos, and voices. This project focuses on detecting deepfake face images using a binary classification approach.

## Dataset

The dataset used in this project is the StyleGAN and StyleGAN2 DeepFake Face Images dataset from Kaggle.

Dataset link:
https://www.kaggle.com/datasets/kshitizbhargava/deepfake-face-images

The dataset contains:
- 5,890 Real images
- 7,000 Fake images
- Total images: 12,890

The full dataset is not uploaded to GitHub because of file size limits.

## Models Used

Three models were implemented and compared:

1. Random Forest Classifier
2. Convolutional Neural Network
3. ResNet50 Transfer Learning

## Results

| Model | Accuracy | AUC Score |
|---|---:|---:|
| Random Forest | 71.68% | 0.8049 |
| CNN | 77.00% | 0.8658 |
| ResNet50 | 84.76% | 0.9270 |

ResNet50 achieved the best performance among all models.

## Tools and Libraries

- Python
- OpenCV
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- TensorFlow/Keras
- Jupyter Notebook

## Project Workflow

1. Dataset loading
2. Data cleaning
3. Image preprocessing
4. Train-test split
5. Random Forest model training
6. CNN model training
7. ResNet50 transfer learning
8. Model evaluation
9. Model comparison
10. Testing on new images

## Conclusion

The project shows that deep learning models perform better than traditional machine learning models for deepfake face image detection. ResNet50 achieved the highest accuracy and AUC score.