# Surface Crack Detection Using Convolutional Neural Networks and Transfer Learning

## Project Overview

This project presents a deep learning-based approach for automated surface crack detection in concrete structures. The objective is to classify concrete surface images into two categories: **Crack** and **No Crack** using Convolutional Neural Networks (CNNs).

The project compares the performance of a custom CNN model with state-of-the-art transfer learning models, including **MobileNetV2** and **ResNet50**, to identify the most effective approach for industrial defect detection.

This project was developed as part of the **Machine Learning** course.

---

## Problem Statement

Manual inspection of concrete structures is labor-intensive, time-consuming, and susceptible to human error. Automated crack detection using deep learning can improve inspection efficiency, reduce costs, and support early maintenance decisions.

The goal of this project is to build and evaluate deep learning models capable of accurately detecting surface cracks from concrete images.

---

## Dataset

**Dataset Name:** Surface Crack Detection

**Source:**
https://www.kaggle.com/datasets/arunrk7/surface-crack-detection

### Dataset Summary

- Total Images: 40,000
- Crack Images: 20,000
- Non-Crack Images: 20,000
- Classes: 2
- Image Type: RGB Images
- Image Size: 227 × 227 pixels

Dataset Structure

```
Positive/
Negative/
```

---

## Project Workflow

1. Dataset Loading
2. Data Exploration
3. Image Preprocessing
4. Image Resizing
5. Data Normalization
6. Train / Validation / Test Split
7. Data Augmentation
8. Custom CNN Development
9. Transfer Learning
10. Model Training
11. Model Evaluation
12. Model Comparison
13. Grad-CAM Visualization
14. Error Analysis

---

## Models Implemented

### Custom CNN

- Convolution Layers
- Max Pooling
- Batch Normalization
- Dropout
- Dense Layers

### Transfer Learning Models

- MobileNetV2
- ResNet50

---

## Evaluation Metrics

The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC
- Confusion Matrix
- Classification Report

Additional Analysis:

- Grad-CAM Visualization
- Error Analysis
- Model Comparison

---

## Project Structure

```
Surface-Crack-Detection-CNN/
│
├── notebooks/
│   └── concrete-crack-detection-using-cnns.ipynb
│
├── proposal/
│   └── Project_Proposal.pdf
│
├── outputs/
│   ├── accuracy_curve.png
│   ├── loss_curve.png
│   ├── confusion_matrix.png
│   ├── roc_curve.png
│   ├── gradcam.png
│   └── model_comparison.png
│
├── README.md
├── requirements.txt
└── LICENSE
```

---

## Installation

Clone the repository

```bash
git clone https://github.com/yourusername/Surface-Crack-Detection-CNN.git
```

Install dependencies

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook

```bash
jupyter notebook
```

Open

```
concrete-crack-detection-using-cnns.ipynb
```

---

## Python Libraries

- Python 3.10+
- TensorFlow / Keras
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- OpenCV
- Pillow
- SHAP

---

## Results

The project compares a custom CNN with MobileNetV2 and ResNet50 for binary crack classification.

The notebook includes:

- Training and Validation Accuracy
- Training and Validation Loss
- Confusion Matrix
- ROC Curve
- Classification Report
- Grad-CAM Visualizations
- Model Performance Comparison
- Error Analysis

---

## Future Improvements

- Vision Transformers (ViT)
- EfficientNet
- Real-time crack detection
- Object detection using YOLO
- Crack segmentation using U-Net
- Deployment using TensorFlow Lite

---

## Author

**Jacob Nicholas Maggidi**

Master's in Data Science

University of Europe for Applied Sciences, Germany

---

## Acknowledgements

- Kaggle
- TensorFlow
- Keras
- Surface Crack Detection Dataset Authors

---

## License

This project is intended for educational and academic purposes.
