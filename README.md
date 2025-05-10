# 🧠 Brain Tumor Classification with Deep Learning

Welcome to the **Brain Tumor Classification** project! This project leverages deep learning to classify brain tumors from MRI scans into three types: **Meningioma**, **Glioma**, and **Pituitary**.

## 🌟 Project Highlights

* **Deep Learning Models Used:** MobileNetV2, ResNet50, VGG16, VGG19, EfficientNetB0
* **Dataset:** MRI scans with three tumor types
* **Tech Stack:** Python, TensorFlow, Keras, Jupyter Notebook
* **Training Techniques:** Transfer Learning, Data Augmentation

## 🎯 Objective

The goal of this project is to develop a deep learning model to classify brain tumors from MRI images. The classification task involves three types of tumors:

* **Meningioma** (708 images)
* **Glioma** (1,426 images)
* **Pituitary Tumor** (930 images)

The dataset contains a total of **3,064 MRI images** from **233 patients**.

## 🛠️ Implementation Approaches

1. **Transfer Learning Approach:**

   * Pretrained models used: MobileNet, MobileNetV2, ResNet, VGG16/VGG19, ResNet50, EfficientNet.
   * Fine-tuning performed to optimize classification performance.
2. **Training from Scratch Approach:**

   * Custom CNN model architecture developed.
   * Justification of architecture and hyperparameters.

## 🚀 Getting Started

### Prerequisites

Make sure you have the following libraries installed:

```bash
pip install tensorflow matplotlib
```

### Installation

Clone this repository:

```bash
git clone https://github.com/dev28616/brain-tumor-classification.git
cd brain-tumor-classification
```

### Dataset

Download the dataset and place it in the following structure:

```
brain-tumor-classification/
├── Train/
└── Test/
```

## 🧩 Model Saving & Submission

The trained model is saved in the following formats:

* .h5 / .keras / .pb (TensorFlow/Keras)
* .pt (PyTorch)

## 📊 Results

The models achieved remarkable accuracy on the test set, demonstrating the efficacy of transfer learning in medical image classification.

## 📁 File Structure

```
brain-tumor-classification/
├── data/
├── notebooks/
│   └── updated_brain_tumor.ipynb
└── README.md
```

## 📜 License

This project is licensed under the MIT License.

Feel free to reach out if you have any questions or suggestions:

* **Author:** Debojyoti Mondal
* **Email:** [your.email@example.com](mailto:mondal.debojyoti17.@gmail.com)

If you like this project, give it a ⭐ on GitHub!
