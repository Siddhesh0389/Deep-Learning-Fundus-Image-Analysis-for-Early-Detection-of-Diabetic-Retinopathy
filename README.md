# 🩺 Diabetic Retinopathy Detection using Deep Learning

## 📌 Project Description

This project aims to detect **Diabetic Retinopathy (DR)** from retinal fundus images using a Deep Learning model based on **Xception (Transfer Learning)** architecture.

Diabetic Retinopathy is a serious eye condition caused by diabetes that can lead to blindness if not detected early. This system helps in early-stage detection using AI.

The project includes:

- ✔ Model Training (Xception CNN)
- ✔ Performance Evaluation
- ✔ Flask Web Application
- ✔ Image Upload & Real-Time Prediction
- ✔ User Login & Registration System

---

## 🧠 Model Details

- **Base Model:** Xception (Pre-trained on ImageNet)
- **Input Size:** 299 × 299 × 3
- **Output Classes:** 5
- **Optimizer:** Adam
- **Loss Function:** Categorical Crossentropy
- **Activation:** Softmax
- **Framework:** TensorFlow / Keras

---

## 🏷 Classification Categories

| Class | Condition |
|-------|------------|
| 0 | No Diabetic Retinopathy |
| 1 | Mild NPDR |
| 2 | Moderate NPDR |
| 3 | Severe NPDR |
| 4 | Proliferative DR |

---

## 📂 Dataset

The dataset is organized into training and testing folders:

