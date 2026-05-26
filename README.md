# Deep Learning Experiments

A collection of deep learning and data science notebooks covering image classification, digit recognition, and exploratory data analysis. All notebooks are runnable in Google Colab.

## Getting Started

If you are new here, start with **[simple_digit_training_using_keras.ipynb](simple_digit_training_using_keras.ipynb)**. It is a beginner-friendly walkthrough of training a neural network on the classic MNIST handwritten digit dataset — the "Hello World" of deep learning.

## Notebooks

### [simple_digit_training_using_keras.ipynb](simple_digit_training_using_keras.ipynb)
**Start here.** Trains a simple ANN on the MNIST dataset (70,000 handwritten digit images) using Keras.

Topics covered:
- Loading and exploring the MNIST dataset
- Visualizing image data with Matplotlib
- Normalizing pixel values
- Building a Sequential model with Dense layers
- Training, evaluating, and saving/loading a model
- Making predictions on test images

Achieved ~97% accuracy on the test set in just 3 epochs.

---

### [digit_recognition/elective_project_digit_recognition.ipynb](digit_recognition/elective_project_digit_recognition.ipynb)
A deeper exploration of digit recognition using the **SVHN (Street View House Numbers)** dataset — real-world digit images captured from Google Street View, making it a harder problem than MNIST.

Topics covered:
- Multiple ANN iterations: baseline → normalization → deeper networks → batch normalization
- Diagnosing overfitting
- CNN (Convolutional Neural Network) models
- Data augmentation to improve generalization

Dataset file: [digit_recognition/SVHN_single_grey1.h5](digit_recognition/SVHN_single_grey1.h5)

---

### [food_hub/FDS_Project_LearnerNotebook_FullCode_Narayanan.ipynb](food_hub/FDS_Project_LearnerNotebook_FullCode_Narayanan.ipynb)
An exploratory data analysis (EDA) project on a food delivery aggregator dataset (FoodHub). Focuses on data science fundamentals before applying ML.

Topics covered:
- Handling missing data (rating imputation by restaurant mean)
- Univariate and multivariate analysis
- Business questions: top restaurants, popular cuisines, delivery time analysis
- Revenue calculations and promotional offer criteria

Dataset file: [food_hub/foodhub_order.csv](food_hub/foodhub_order.csv)

---

### facial_emotion/ *(coming soon)*
Dataset ([Facial_emotion_images.zip](facial_emotion/Facial_emotion_images.zip)) is available. Notebook in progress.

---

## Requirements

All notebooks are designed to run on **Google Colab** (no local setup required). For local execution:

```bash
pip install tensorflow keras numpy pandas matplotlib seaborn
```

## Learning Path

```
simple_digit_training_using_keras.ipynb   ← Start here (MNIST, basic ANN)
        ↓
digit_recognition/elective_project_...    ← SVHN, ANN vs CNN, augmentation
        ↓
food_hub/FDS_Project_...                  ← EDA and data science fundamentals
```
