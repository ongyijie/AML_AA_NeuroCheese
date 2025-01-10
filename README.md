# Skin Lesion Classification for Cancer Detection

## Overview
Deep learning-based classification system for skin lesions using the HAM10000 dataset. The project compares multiple CNN architectures for identifying 7 types of skin lesions, achieving 82.3% accuracy with an ensemble model combining EfficientNetB0 and DenseNet121.

## Models Implemented
- Baseline CNN
- Enhanced CNN
- Ensemble Model (EfficientNetB0 + DenseNet121)
- UNet Variation (experimental)

## Key Results
- Best Model: Ensemble Model (EfficientNetB0 + DenseNet121)
  - Accuracy: 82.3%
  - Precision: 81.5%
  - AUC Score: 0.9584

## Dataset
HAM10000 dataset containing 10,015 dermatoscopic images across 7 diagnostic categories:
- Melanoma (mel)
- Basal cell carcinoma (bcc)
- Actinic keratoses (akiec)
- Melanocytic nevi (nv)
- Benign keratosis (bkl)
- Vascular lesions (vasc)
- Dermatofibroma (df)

## Technical Stack
- Framework: TensorFlow/Keras 3.5.0
- Python Libraries: NumPy 1.26.4, Pandas 2.2.2
- Hardware: NVIDIA A100 GPU (Google Colab)

## Key Features
- Data augmentation and preprocessing pipeline
- Class imbalance handling
- Grid search hyperparameter optimization
- Early stopping and learning rate scheduling