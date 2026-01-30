# 🌶️ Chili Plant Disease Detection Using Deep Learning

This project focuses on detecting diseases in chili plant leaves using a **Convolutional Neural Network (CNN)**. The model is trained on a publicly available Kaggle dataset and can classify images of chili leaves into healthy or diseased categories.

---

## 📌 Project Overview

Plant diseases significantly affect agricultural productivity. Early and accurate detection can help farmers take preventive action.  
This project applies **deep learning and computer vision** techniques to automatically identify chili plant diseases from leaf images.

---

## 🧠 Model & Approach

- Image-based classification using **CNN**
- Data augmentation for improved generalization
- Train / validation split
- Performance evaluation using accuracy and confusion matrix

---

## 📂 Dataset

- **Source:** Kaggle  
- **Dataset Name:** Chili Plant Disease Detection  
- **Author:** Shuvo Kumar Basak  
- **Link:** https://www.kaggle.com/datasets/shuvokumarbasak4004/chili-plant-disease-detection

### Dataset Access (Used in This Project)

The dataset is downloaded programmatically using `kagglehub`:

```python
import kagglehub

path = kagglehub.dataset_download(
    "shuvokumarbasak4004/chili-plant-disease-detection"
)
print("Path to dataset files:", path)
