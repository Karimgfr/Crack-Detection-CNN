# Crack-Detection-CNN

## 📸 Cracked vs Non-Cracked Image Classification

Welcome to the **Cracked vs Non-Cracked Image Classification** project! This repository focuses on building and training a model for image classification to distinguish cracked surfaces from non-cracked ones.  

This project is designed as an educational resource to explore the following:  
- Image preprocessing and augmentation techniques.  
- Designing, training, and evaluating CNNs.  
- Visualizing model performance and interpretability.  

The trained model will be provided in **H5 format**, allowing for further deployment and experimentation in different environments.  

## 🚀 Key Features

- **Deep Learning Model**: Implements a CNN for accurate binary classification of images.  
- **End-to-End Workflow**: Covers data preprocessing, model training, evaluation, and visualization.  
- **Explainable AI**: Visualizes convolutional filters, activation maps, and Grad-CAM heatmaps to interpret the model's predictions.  
- **Performance Metrics**: Detailed evaluation using accuracy, precision, recall, F1-score, and confusion matrix.
- **Theoretical Documentation**: A separate file explaining core concepts, methods, and rationale behind the design choices in the project.

## 🗂 Dataset

The dataset used for this project is **Surface Crack Detection**, available on Kaggle. It consists of labeled images that are categorized into two classes:  
- **Cracked**: Images depicting surface cracks.  
- **Non-Cracked**: Images without any visible cracks.  

### Key Statistics:
- **Number of Images**: 20000 cracked and 20000 non-cracked images.  
- **Image Dimensions**: Uniform dimensions of 227x227 pixels.  
- **File Structure**:  
  - `/Positive`: Contains cracked images.  
  - `/Negative`: Contains non-cracked images.  

### Dataset Source:
You can access the dataset from Kaggle [here](https://www.kaggle.com/arunrk7/surface-crack-detection).  

### Preprocessing Steps:
- **Resizing**: Ensured all images are scaled to the required input size for the CNN.  
- **Normalization**: Pixel values scaled to a range of [0, 1] to improve convergence during training.  
- **Augmentation**: Techniques such as flipping, rotation, and contrast adjustments were applied to enhance diversity in the training data.
