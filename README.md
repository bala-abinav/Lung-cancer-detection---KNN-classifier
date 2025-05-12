# Lung Cancer Prediction using Machine Learning

This project implements a machine learning pipeline to predict lung cancer presence based on medical, behavioral, and demographic features using a Kaggle dataset.

## Problem Statement

Lung cancer remains one of the leading causes of cancer-related deaths worldwide. Early detection can significantly improve patient outcomes. This project leverages health-related symptoms and behavioral attributes to build a model capable of predicting the presence of lung cancer using supervised machine learning techniques.

## Algorithm Used

### Model Selection
The K-Nearest Neighbors (KNN) algorithm was chosen due to its simplicity and superior performance on this classification task compared to other models tested.

### Input Features
- Smoking habits
- Yellow fingers
- Anxiety
- Peer pressure
- Chronic disease
- Fatigue
- Allergy
- Wheezing
- Alcohol consumption
- Coughing
- Shortness of breath
- Swallowing difficulty
- Chest pain
- Gender

### Training Process
- The data was preprocessed and scaled using `StandardScaler`.
- Imbalanced classes were handled using `ADASYN` (Adaptive Synthetic Sampling).
- KNN was trained on the resampled data and validated using a 20% holdout test set.

## Results

- **Accuracy**: 89.29%
- The model showed high reliability in identifying negative lung cancer cases, with some scope for improving positive case detection.
- Confusion matrix and classification reports were generated for evaluation.
- ![image](https://github.com/user-attachments/assets/ab2dec61-60bd-4ea5-a6d3-024b8bb5c058)


## Model Validation

- Evaluated using a confusion matrix and classification metrics
- Accuracy was computed to quantify performance.

## System Requirements

- Python 3.x
- Jupyter Notebook / Google Colab
- Libraries:
  - pandas
  - numpy
  - seaborn
  - matplotlib
  - scikit-learn
  - imbalanced-learn

## Future Scope

- Developing a web based or mobile based application that allows real time lung cancer assessment using user input
- Integrating X ray and MRI images with deep learning can improve performance and accuracy
- More quality data availability improves accuracy of classification

---

