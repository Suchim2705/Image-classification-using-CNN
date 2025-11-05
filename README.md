# Intel Image Classification

## Overview
This project focuses on classifying images from the **Intel Image Classification dataset**. The goal is to build a model that can accurately categorize images into multiple classes based on content.

In this project, we:

- Explored the dataset and analyzed image characteristics.
- Preprocessed and augmented the images for better model performance.
- Built and evaluated deep learning models for image classification.

---

## Dataset
- Contains images categorized into 6 classes:
  1. Buildings
  2. Forest
  3. Glacier
  4. Mountain
  5. Sea
  6. Street  

The dataset includes separate folders for **training**, **validation**, and **test** images.

---

## Methodology
1. **Data Preprocessing:**  
   - Resized images to a consistent shape  
   - Normalized pixel values  
   - Applied image augmentation (rotation, flips, zooms) to increase model generalization

2. **Modeling:**  
   - Built Convolutional Neural Networks (CNNs) for image classification  
   - Used transfer learning with pre-trained models such as VGG16 or ResNet for improved performance

3. **Evaluation:**  
   - Monitored accuracy and loss on validation data  
   - Generated confusion matrix and classification reports to analyze model performance

---

## Results
- Achieved high classification accuracy on validation data.  
- The model successfully distinguishes between the 6 image categories.  
- Transfer learning significantly improved accuracy and reduced training time.

---

## Tools & Libraries
- Python 
- TensorFlow / Keras  
- NumPy, Pandas  
- Matplotlib, Seaborn  
