## Transfer Learning for Melanoma Detection

This repository contains the Python and Jupyter Notebook code used for a skin cancer detection study leveraging transfer learning techniques.

This is the link to the dataset: https://www.kaggle.com/datasets/bilalakgz/brain-tumor-mri-dataset

### Project Overview

The core objective of this project is to compare the performance of different Convolutional Neural Network (CNN) architectures, including a custom-built CNN and several pre-trained models, for classifying melanoma images.

### Models Explored

The following models were trained and evaluated using the same dataset and data augmentation pipeline:

* **Custom CNN**
* **VGG16** (Transfer Learning)
* **ResNet50** (Transfer Learning)
* **MobileNetV2** (Transfer Learning)
* **InceptionV3** (Transfer Learning)

### Performance Summary

The best performance was achieved by the **ResNet50** transfer learning model, which attained a validation accuracy of **91.90%** and the lowest validation loss of **0.1956**.

| Model | Validation Accuracy | Validation Loss (Best) |
| :--- | :---: | :---: |
| Custom CNN | 85.40% | 0.4031 |
| VGG16 | 91.50% | 0.2330 |
| **ResNet50** | **91.90%** | **0.1956** |
| MobileNetV2 | 87.70% | 0.2900 |
| InceptionV3 | 82.10% | 0.3644 |

### Repository Contents

* `Skin Cancer with Transfer Learning.ipynb`: Main Jupyter Notebook with all data loading, model definitions, training, and evaluation code.
* `LICENSE`: Licensing information for the code (MIT License).

### Data Source

The models were trained using the "Melanoma Skin Cancer Dataset of 10000 Images."

* The training set contains **9605 files**.
* The test set contains **1000 files**.
* **Classes:** `benign` and `malignant`.

### Requirements

The code requires standard Python packages for deep learning, primarily:

* `tensorflow` (and `tensorflow.keras`)
* `numpy`
* `matplotlib`
* `seaborn`
* `scikit-learn`

### Contact

For questions regarding the code, please contact Dr Sakinat Folorunso;   sakinat.folorunso@oouagoiwoye.edu.ng
