# Network Intrusion Detection Using Machine Learning

## Overview

This project implements a Machine Learning-based Network Intrusion Detection System (NIDS) using the NSL-KDD dataset. The objective is to identify and classify malicious network activities and cyber attacks using multiple machine learning and deep learning algorithms.

The system helps improve network security by detecting intrusions and distinguishing between normal and malicious traffic.

---

## Objectives

* Detect network intrusions using machine learning.
* Classify attacks into different categories.
* Compare the performance of various algorithms.
* Improve cybersecurity through intelligent intrusion detection.

---

## Features

* Binary Classification (Normal vs Attack)
* Multi-class Attack Classification
* Data Preprocessing and Feature Engineering
* Model Training and Evaluation
* Performance Visualization
* Deep Learning-based Intrusion Detection

---

## Technologies Used

### Programming Language

* Python

### Libraries

* NumPy
* Pandas
* Scikit-learn
* TensorFlow
* Keras
* Matplotlib
* Seaborn

### Development Environment

* Jupyter Notebook

---

## Project Structure

```text
Network-Intrusion-Detection-Using-Machine-Learning/
│
├── datasets/
├── models/
├── weights/
├── labels/
├── plots/
│
├── Data_Preprocessing_NSL_KDD.ipynb
├── Intrusion_Detection_NSL_KDD.ipynb
├── Classifiers_NSL_KDD.ipynb
│
├── README.md
└── LICENSE
```

---

## Dataset

This project uses the **NSL-KDD dataset**, an improved version of the KDD Cup 1999 dataset.

Dataset files:

* KDDTrain+.txt
* KDDTest+.txt
* Binary classification dataset
* Multi-class classification dataset

---

## Algorithms Used

### Machine Learning Algorithms

* K-Nearest Neighbors (KNN)
* Linear Discriminant Analysis (LDA)
* Quadratic Discriminant Analysis (QDA)
* Linear Support Vector Machine (LSVM)
* Quadratic Support Vector Machine (QSVM)

### Deep Learning Models

* Multi-Layer Perceptron (MLP)
* Autoencoder
* Long Short-Term Memory (LSTM)

---

## Performance Evaluation

The models are evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* ROC Curve
* Confusion Matrix

Several performance plots are included in the `plots` directory.

---

## How to Run

### Clone the repository

```bash
git clone https://github.com/yourusername/Network-Intrusion-Detection-Using-Machine-Learning.git
cd Network-Intrusion-Detection-Using-Machine-Learning
```

### Install dependencies

```bash
pip install numpy pandas matplotlib scikit-learn tensorflow keras jupyter
```

### Run Jupyter Notebook

```bash
jupyter notebook
```

Open:

* Data_Preprocessing_NSL_KDD.ipynb
* Classifiers_NSL_KDD.ipynb
* Intrusion_Detection_NSL_KDD.ipynb

---

## Results

The project provides:

* Accuracy graphs
* Loss curves
* ROC curves
* Prediction plots
* Binary and multi-class classification results

---

## Future Enhancements

* Real-time intrusion detection.
* Integration with live network traffic.
* Web dashboard for monitoring.
* Deployment using Flask or Django.
* Cloud-based intrusion detection system.

---

## Author

**Tarun Reddy**
B.Tech Student
Indian Institute of Information Technology and Management, Gwalior

---


