# 2023-SE-29_DIP_OEL
DIP_OEL
Skin Lesion Analysis using Dermoscopic Images

This repository implements an end-to-end pipeline for skin lesion analysis and classification using dermoscopic images from the PH2 dataset. The workflow covers image preprocessing, lesion segmentation, feature extraction, and machine learning-based classification.

# Features

Image preprocessing (resizing, brightness/contrast adjustment)

Hair and noise removal using morphological operations and inpainting

Color normalization using CLAHE

Lesion segmentation and mask generation

Feature extraction (texture, color, and shape features)

Classification using SVM, KNN, Decision Tree, and Logistic Regression

# Dataset

PH2 Dermoscopic Image Dataset

Ground-truth lesion masks used for segmentation evaluation

Image labels provided via an external Excel file

# Technologies

Python, Google Colab, OpenCV, NumPy, Pandas, scikit-image, scikit-learn, Matplotlib

# Usage

Upload the PH2 dataset to Google Drive

Update dataset paths in the code

Run the notebook sequentially in Google Colab

# Output

Segmented lesion images

Extracted feature datasets (CSV)

Classification results and evaluation metrics
