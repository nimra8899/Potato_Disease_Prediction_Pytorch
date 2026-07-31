# 🥔 Potato Disease Prediction using PyTorch

A deep learning project that classifies potato leaf images into three disease categories using a Convolutional Neural Network (CNN) built from scratch in **PyTorch**.

## 📌 Overview

Potato diseases can significantly reduce crop yield if not detected early. This project uses computer vision and deep learning to automatically classify potato leaf images into different disease categories.

The model is trained on the PlantVillage dataset and demonstrates the complete deep learning pipeline, including data preprocessing, model training, evaluation, and prediction.

---

## 🎯 Classes

The model predicts one of the following classes:

- 🍃 Potato Healthy
- 🟤 Potato Early Blight
- ⚫ Potato Late Blight

---

## 🛠️ Tech Stack

- Python
- PyTorch
- TorchVision
- NumPy
- Matplotlib
- PIL (Pillow)
- Google Colab / VS Code

---

## 📂 Project Structure

```
Potato-Disease-Prediction/
│
├── dataset/
│   └── PlantVillage/
│       ├── Potato___Early_blight
│       ├── Potato___Late_blight
│       └── Potato___healthy
│
├── Potato_Disease_Prediction_Final2.ipynb
├── README.md
└── .gitignore
```

---

## 📊 Dataset

Dataset used:

**PlantVillage Dataset**

Classes:

- Potato___Early_blight
- Potato___Late_blight
- Potato___healthy

---

## ⚙️ Features

- Image preprocessing
- Data augmentation
- Custom CNN built from scratch
- Train / Validation / Test split
- Model training using PyTorch
- Accuracy and loss visualization
- Model evaluation
- Prediction on unseen images
- GPU support (CUDA)

---

## 🧠 Model Architecture

The CNN consists of:

- Convolution Layers
- ReLU Activation
- Max Pooling
- Dropout
- Fully Connected Layers
- Softmax Classification

---

## 🚀 Installation

Clone the repository

```bash
git clone https://github.com/your-username/Potato-Disease-Prediction.git
cd Potato-Disease-Prediction
```

Install dependencies

```bash
pip install torch torchvision matplotlib numpy pillow
```

---

## ▶️ Run the Project

Open the notebook

```
Potato_Disease_Prediction_Final2.ipynb
```

Run all cells.

The notebook automatically detects whether it is running in:

- Google Colab
- VS Code

and loads the dataset accordingly.

---

## 📈 Results

The notebook provides:

- Training Accuracy
- Validation Accuracy
- Training Loss
- Validation Loss
- Model Predictions

---

## 📷 Sample Predictions

| Image | Prediction |
|--------|------------|
| Potato Leaf | Healthy |
| Potato Leaf | Early Blight |
| Potato Leaf | Late Blight |

---

## 📚 Learning Outcomes

This project demonstrates:

- Image Classification
- CNN Implementation
- PyTorch Fundamentals
- Dataset Handling
- Data Augmentation
- Model Training
- Model Evaluation
- Deep Learning Workflow

---

## 🔮 Future Improvements

- Transfer Learning (ResNet50)
- MobileNet Deployment
- EfficientNet
- Streamlit Web App
- Flask API
- Real-time Camera Detection
- Model Optimization
- Explainability using Grad-CAM


## ⭐ If you found this project helpful

Give this repository a ⭐ on GitHub.
