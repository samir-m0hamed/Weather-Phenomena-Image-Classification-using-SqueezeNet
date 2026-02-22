# 🌧️ Weather Phenomena Image Classification using SqueezeNet (Transfer Learning & Fine-Tuning)

## 📌 Project Description

Deep learning project for multi-class weather image classification using transfer learning and CNN fine-tuning. The model distinguishes atmospheric phenomena such as fog, frost, rain, lightning, and snow. Includes training analysis, confusion matrices, and performance evaluation demonstrating strong generalization and improved accuracy after fine-tuning.

---

## 📖 Overview

This project develops a deep learning computer vision model that classifies different weather phenomena from images.
A pre-trained convolutional neural network is used as a feature extractor, then fine-tuned to improve performance on the target dataset.

The system learns to recognize multiple atmospheric conditions and evaluates performance using training curves and confusion matrices.

---

## 🎯 Objectives

* Classify weather conditions from images automatically
* Compare feature extraction vs fine-tuning performance
* Analyze model learning behavior using training history
* Evaluate prediction quality using confusion matrices
* Improve classification accuracy through transfer learning

---

## 🧠 Model Pipeline

```
Raw Images
   ↓
Data Preprocessing & Augmentation
   ↓
Transfer Learning (Feature Extraction)
   ↓
Fine-Tuning Selected Layers
   ↓
Model Evaluation
   ↓
Confusion Matrix Analysis
```

---

## 🌍 Target Classes

The model classifies the following weather phenomena:

* Dew
* Fog / Smog
* Frost
* Glaze
* Hail
* Lightning
* Rain
* Rainbow
* Rime
* Sandstorm
* Snow

---

## 🏗 Training Strategy

### 1️⃣ Feature Extraction Phase

* Freeze pre-trained CNN backbone
* Train classification head only
* Learn high-level representations
* Monitor loss and accuracy convergence

### 2️⃣ Fine-Tuning Phase

* Unfreeze selected deep layers
* Train with smaller learning rate
* Adapt model to dataset-specific patterns
* Improve feature representation quality

---

## 📊 Evaluation Metrics

Model performance is evaluated using:

* Training Loss
* Validation Loss
* Training Accuracy
* Validation Accuracy
* Confusion Matrix per class
* Generalization gap monitoring

---

## 📈 Results Summary

### Feature Extraction

* Fast convergence
* Stable validation performance
* Good baseline accuracy

### Fine-Tuning

* Lower training loss
* Higher classification accuracy
* Improved class-level predictions
* Better generalization

---

## 🛠 Tech Stack

* Python
* Deep Learning Framework (PyTorch)
* NumPy
* Matplotlib
* Seaborn
* Transfer Learning via SqueezeNet

---

## 👨‍💻 Author

* **Samir Mohamed Samir**
* **AI Engineer | Machine Learning & Computer Vision**

---
