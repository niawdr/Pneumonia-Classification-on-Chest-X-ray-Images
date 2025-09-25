# Pneumonia Classification on Chest X-ray Images  

This repository contains a **course project** for the Deep Learning class, focusing on the classification of pneumonia using **Convolutional Neural Networks (CNN)** and **Transfer Learning (ResNet152V2)**.  

## 📌 Dataset
The dataset used in this project is the **Chest X-ray Images (Pneumonia)** dataset from Kaggle
- **Chest X-ray Dataset**: 5,856 validated images (Normal vs. Pneumonia).  
- Data split into training and test sets.

⚠️ **Note:**  
The full dataset is too large to be included in this repository due to GitHub storage limits.  
Please download it directly from Kaggle.

## ⚙️ Methods  
1. **Custom CNN Model**  
   - Achieved **89.8% accuracy** on training and **93.9% validation accuracy**.  
   - Test Accuracy: **85.9%**.  

2. **Transfer Learning with ResNet152V2**  
   - Fine-tuned pre-trained weights for pneumonia classification.  
   - Validation Accuracy: **96.6%**.  
   - Test Accuracy: **91.3%**.  

## 📊 Results  
- **Custom CNN** → Test Accuracy: **85.9%**  
- **ResNet152V2 (fine-tuned)** → Test Accuracy: **91.3%**  
- Fine-tuning significantly improved model generalization and performance.  
