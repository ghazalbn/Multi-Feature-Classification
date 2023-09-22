# Multi-Feature Image Classification

### Table of Contents
1. [Introduction](#introduction)
2. [Features](#features)
3. [Dataset](#dataset)
4. [Model and Classifier](#model-and-classifier)
5. [Testing and Visualization](#testing-and-visualization)
6. [License](#license)

---

### Introduction <a name="introduction"></a>

This repository contains a multi-feature image classification project developed using Python and popular deep learning libraries. The project leverages various image features, including compactness, eccentricity, solidity, and Local Binary Pattern (LBP) histograms, to classify images into different categories. This README provides an overview of the project and how to use it.

---

### Features <a name="features"></a>

This multi-feature image classification project offers the following features:

1. **Compactness Calculation**: Calculate compactness for an input image.
2. **Eccentricity Calculation**: Calculate eccentricity for an input image.
3. **Solidity Calculation**: Calculate solidity for an input image.
4. **Local Binary Pattern (LBP) Histogram**: Extract and analyze LBP histograms from images.
5. **Data Preprocessing**: Automatically download and prepare a dataset for training and testing.
6. **Model Training**: Train a linear Support Vector Machine (SVM) classifier on the extracted features.
7. **Testing and Evaluation**: Test the classifier on a test dataset and calculate accuracy.
8. **Visualization**: Visualize the prediction results on a randomly selected image from the test dataset.

---

### Dataset <a name="dataset"></a>

The project includes a dataset of images for two categories: "ship" and "airplane." The dataset is automatically downloaded and prepared when running the provided code.

---

### Model and Classifier <a name="model-and-classifier"></a>

The project employs a linear Support Vector Machine (SVM) classifier to classify images based on the extracted features, including compactness, eccentricity, solidity, and LBP histograms.

---

### Testing and Visualization <a name="testing-and-visualization"></a>

After training the classifier, you can test its performance on a test dataset and visualize the results. The project includes functionality to display a randomly selected image from the test dataset, along with the ground truth label and the predicted class label.

---

### License <a name="license"></a>

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.


