# 🌾 Plant Pathology Analysis Using CNN 🌟

## 🧐 Project Overview  
Plant health is critical to agricultural productivity. This project leverages *Convolutional Neural Networks (CNNs)* to classify plant diseases into four categories:  
- *Healthy*  
- *Multiple Diseases*  
- *Rust*  
- *Scab*  

The primary objective is to develop a reliable multi-class classification model to support *agricultural health monitoring* and enhance plant disease management.

---

## ✨ Key Highlights  
- *📊 Dataset*:  
  Utilized the [Plant Pathology 2020](https://www.kaggle.com/c/plant-pathology-2020-fgvc7/data) dataset containing labeled plant images.  

- *🔍 Techniques*:  
  1. *Data Preprocessing*:  
     - Normalization of images.  
     - Augmentation: rotations, flips, shifts, zoom.  
     - Encoded target variables.  
  2. *Model Architecture*:  
     - CNN with three convolutional layers.  
     - Batch normalization and max-pooling layers.  
     - Fully connected dense layers for classification.  
  3. *Data Splitting*:  
     - Training set: 80%  
     - Validation set: 20%  

---

## 🌟 Results  
- Accurate classification of plant health conditions into distinct categories.  
- Balanced and robust model ensured through detailed histogram analysis of label distribution.  

---

## 🚀 Features  
- *Dynamic Data Augmentation*: Improved model generalization with real-time transformations.  
- *Visualization Tools*: Visualized both raw and augmented image samples to gain insights into data diversity.  
- *Optimized Model*:  
  - Framework: *TensorFlow/Keras*  
  - Optimizer: Adam  
  - Loss Function: Categorical Crossentropy  

---

## 🔭 Future Scope  
- *Expand Disease Coverage*: Incorporate additional plant diseases for a more comprehensive model.  
- *Real-Time Deployment*: Deploy the model as an application for real-time agricultural use cases to aid farmers and agronomists.  

---

💡 *Join the effort to enhance plant disease detection and contribute to a healthier agricultural ecosystem!* 🌱
