# Image Classification: Facial Emotion Recognition (FER)

## Overview
This project explores various machine learning and deep learning approaches for facial emotion classification, using a subset of the FER2013 image dataset. The notebook demonstrates a structured approach to image data feature extraction and classification, beginning with conventional machine learning methods and progressing to deep learning techniques using Keras. This project was part of a [Kaggle competition](https://www.kaggle.com/competitions/emotion-recognition-from-human-faces/leaderboard) where this submission achieved a third place out of 32 participants. Note that the data can be found there.

## Structure
1. **Library and Data Import**
2. **Data Preprocessing and Feature Descriptor Extraction for Conventional ML**
   - Image Sharpening
   - Image Augmentation
   - Histogram of Oriented Gradients
   - Harris Corner Detectors
   - Local Binary Patterns
   - Canny Edge Detector
   - Gray-Level Co-Occurrence Matrix
4. **Conventional Machine Learning Approaches**
   - Support Vector Machine
   - Ensemble Methods
   - Gradient Boosting
   - Stacking Approaches
   - Feature Selection based on SHAP
6. **Deep Learning Approaches**
   - Transfer Learning
   - Error Analysis
   - Regularisation Approaches
   - Test Time Augmentation & Monte Carlo Dropout
8. **Discussion**

## Key Findings
- **Best Deep Learning Approach**:
  - Achieved a test accuracy of 72.36%
  - Leveraged a transfer learning approach, regularisation, training and test time augmentation, Monte Carlo Dropout
- **Comparative Analysis**: Deep learning models demonstrated superior performance over conventional ML methods for this task (18.6% improvement)
- **FER is a Hard Learning Task** due to emotion ambiguity, labeling, and image quality

## Potential Improvements
- **Hyperparameter Tuning**: Further tuning of the deep learning models' hyperparameters might yield better results
- **Model Architecture Optimization**: Experimenting with different neural network architectures to find the most effective structure for this task
- **Ensemble Methods for Deep Learning**: Combining the predictions of different Convolutional Neural Networks is expected to further improve results

