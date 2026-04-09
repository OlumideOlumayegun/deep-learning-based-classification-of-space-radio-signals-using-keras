# 📡 Deep Learning-Based Classification of Space Radio Signals

## 🚀 Overview

This project focuses on building a deep learning model to classify radio signals from space into four categories: **squiggle, narrowband, noise, and narrowbanddrd**. Using Keras, the solution demonstrates how neural networks can effectively identify patterns in complex signal data.

The project showcases an end-to-end workflow including data preprocessing, model development, training, evaluation, and performance analysis.

---

## 🧠 Problem Statement

Radio signal data collected from space contains a mix of meaningful and noisy patterns. The goal is to automatically classify these signals into predefined categories to support scientific analysis and signal interpretation.

---

## 📊 Dataset

* Multi-class labelled dataset of radio signals
* Classes:

  * Squiggle
  * Narrowband
  * Noise
  * Narrowbanddrd

> Note: Dataset may require preprocessing such as normalisation and reshaping before model training.

---

## ⚙️ Technologies Used

* Python
* TensorFlow / Keras
* NumPy, Pandas
* Matplotlib / Seaborn
* Jupyter Notebook

---

## 🏗️ Project Workflow

1. Data Loading and Exploration
2. Data Preprocessing
3. Model Building (Keras)
4. Model Training and Validation
5. Model Evaluation
6. Performance Visualisation

---

## 🤖 Model Architecture

* Fully connected neural network (Dense layers)
* Activation functions: ReLU, Softmax
* Regularisation: Dropout (to reduce overfitting)
* Loss Function: Categorical Crossentropy
* Optimiser: Adam

---

## 📈 Evaluation Metrics

* Accuracy
* Confusion Matrix
* Loss Curves (Training vs Validation)

---

## 📊 Results

* Achieved strong multi-class classification performance
* Effective distinction between subtle signal patterns
* Balanced performance across all four classes

---

## ▶️ How to Run

1. Clone the repository:


2. Install dependencies:


3. Launch Jupyter Notebook:

```bash
jupyter notebook
```

4. Open and run:

```
notebooks/deep-learning-classification-with-keras.ipynb
```

---

## 🔐 Prerequisites

* Python 3.8+
* Jupyter Notebook
* TensorFlow / Keras installed

---

## 📜 License

This project is licensed under the MIT License.

---

