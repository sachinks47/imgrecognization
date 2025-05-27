

# Image Recognition with KNN and PCA

This project performs **image classification** using a simple machine learning pipeline:

- Image Preprocessing
- Dimensionality Reduction with **PCA**
- Classification with **K-Nearest Neighbors (KNN)**

It includes dataset splitting, preprocessing, model training, and evaluation — with specific guidance for running in **Google Colab** using **Google Drive**.

## 🧠 Algorithms Used

- **Principal Component Analysis (PCA)** – Reduces dimensionality of image features.
- **K-Nearest Neighbors (KNN)** – Classifies images based on similarity in reduced space.

> If only `Train/` exists, you can split it into a `Test/` folder automatically.

## 🚀 How to Run (Google Colab Setup)

### 1. Mount Google Drive

from google.colab import drive
drive.mount('/content/drive')

### 2. Update the paths according to your Drive:

train_dir = '/content/drive/MyDrive/IMG/Train'
   test_dir = '/content/drive/MyDrive/IMG/Test'

## 🛠️ Libraries Used

numpy, pandas: Data manipulation
PIL: Image processing
sklearn: ML models, PCA, scaling, evaluation
matplotlib, seaborn: (Optional) Visualization
os, shutil: File management

## 📌 Notes

Ensure consistent folder structure between Train/Test datasets.
You can change image resolution (size=(64, 64)) or PCA components (n_components=50) to suit your use case.
Accuracy will vary depending on image quality and data balance.


