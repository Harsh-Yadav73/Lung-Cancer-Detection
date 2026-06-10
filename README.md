# 🫁 Lung Cancer Detection Using Deep Learning

### 🚀 AI-Powered Histopathological Image Classification with Enhanced CNN Architectures

> An advanced deep learning project focused on automated lung cancer detection from histopathological images using state-of-the-art CNN architectures and image enhancement techniques for high-accuracy medical diagnosis.

<p align="center">
  <img src="https://img.shields.io/badge/Deep%20Learning-Medical%20AI-red?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Computer%20Vision-Histopathology-blue?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/CNN-Image%20Classification-green?style=for-the-badge"/>
</p>

---

# 🌟 Project Overview

Lung cancer remains one of the leading causes of cancer-related deaths worldwide. Early and accurate diagnosis is critical for improving patient survival rates.

This project leverages **Deep Learning and Computer Vision** to automatically classify histopathological lung images into:

🫁 Normal Lung Tissue
🧬 Lung Adenocarcinoma
🦠 Lung Squamous Cell Carcinoma

The system evaluates multiple **pre-trained CNN architectures** combined with advanced image enhancement techniques to improve feature extraction and classification accuracy.

---

# 🧠 Deep Learning Models Used

The following transfer learning architectures were implemented and evaluated:

✅ VGG16
✅ ResNet50
✅ DenseNet121
✅ MobileNetV2
✅ InceptionV3
✅ Xception

---

# 🗂 Dataset Information

## 📊 Dataset Details

🔹 **Dataset:** Public Lung & Colon Cancer Histopathological Image Dataset
🔹 **Total Images:** 15,000
🔹 **Balanced Multi-Class Dataset**
🔹 **Image Categories:** 3

### 📂 Data Split

📘 Training Set → 70%
📙 Validation Set → 20%
📕 Testing Set → 10%

---

## 🖼 Image Resolution

📌 224×224 → VGG16, ResNet50, DenseNet121, MobileNetV2
📌 299×299 → InceptionV3, Xception

---

# ⚡ Advanced Image Enhancement Pipeline

To improve feature visibility and model performance, multiple preprocessing and enhancement techniques were applied:

✨ Sobel Edge Detection
✨ Canny Edge Detection
✨ Histogram Equalization
✨ Unsharp Masking
✨ Median Blurring
✨ Gaussian Blurring
✨ Non-Local Means Denoising
✨ Morphological Operations

---

## 🔬 Hybrid Processed Pipelines

Advanced enhancement combinations were also tested:

✅ M + H + C + MR
✅ MR + C + H + M
✅ M + C + H + MR
✅ Additional enhancement combinations

Where:

🔹 M → Median Blurring
🔹 H → Histogram Equalization
🔹 C → CLAHE
🔹 MR → Morphological Operations

---

# ⚙️ Methodology

```text id="f7m2x4"
🖼 Histopathological Images
          ↓
🧹 Image Preprocessing & Enhancement
          ↓
🧠 Transfer Learning CNN Models
          ↓
⚡ Model Training & Fine-Tuning
          ↓
📊 Evaluation & Performance Analysis
          ↓
🩺 Automated Lung Cancer Classification
```

---

# 🧪 Training Configuration

🔹 Optimizer → Adam
🔹 Batch Size → 46
🔹 Epochs → 10
🔹 Transfer Learning → ImageNet Weights
🔹 Fine-Tuning → Selective Layer Unfreezing

---

# 📊 Performance Results

| 🧠 Model    | ✨ Best Enhancement     | 📈 Test Accuracy | 🚀 Fine-Tuned Accuracy |
| ----------- | ---------------------- | ---------------- | ---------------------- |
| Xception    | Histogram Equalization | **99.46%**       | **99.53%**             |
| ResNet50    | Median Blurring        | 97.23%           | 99.93%                 |
| InceptionV3 | Unsharp Masking        | 98.97%           | 99.83%                 |
| DenseNet121 | Original               | 95.83%           | 99.53%                 |
| VGG16       | Original               | 98.46%           | 99.93%                 |
| MobileNetV2 | Final Processed 2      | 96.36%           | 99.87%                 |

---

# 🔥 Key Findings

✅ Image enhancement significantly improved CNN performance
✅ Fine-tuning boosted classification accuracy across all models
✅ Xception achieved the best overall performance
✅ Transfer learning proved highly effective for medical imaging tasks
✅ Enhanced preprocessing improved feature extraction capability

---

# 📈 Evaluation Metrics

The models were evaluated using:

📊 Accuracy
📉 Loss Curves
📌 Confusion Matrix
📈 ROC Curves
🎯 Precision & Recall
📋 Validation Performance Analysis

---

# ⚡ Tech Stack

<p align="left">
  <img src="https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54"/>
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white"/>
  <img src="https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white"/>
  <img src="https://img.shields.io/badge/OpenCV-white?style=for-the-badge&logo=opencv&logoColor=black"/>
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white"/>
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white"/>
  <img src="https://img.shields.io/badge/Matplotlib-white?style=for-the-badge&logo=matplotlib&logoColor=black"/>
  <img src="https://img.shields.io/badge/Google%20Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white"/>
</p>

---

# 📂 Repository Structure

```text id="p9x4v7"
Lung-Cancer-Detection/
│── Dataset/
│── Preprocessing/
│── Models/
│── Training/
│── Evaluation/
│── Results/
│── README.md
```

---

# 🚀 Key Highlights

🔥 Multi-model CNN comparison study
🔥 Advanced image enhancement pipeline
🔥 Medical image classification using AI
🔥 High-accuracy automated diagnosis system
🔥 Transfer learning + fine-tuning implementation
🔥 Performance visualization & evaluation

---

# 📚 Key Learnings

💡 Deep Learning for Medical Imaging
💡 Transfer Learning & Fine-Tuning
💡 CNN Architecture Comparison
💡 Image Enhancement Techniques
💡 Computer Vision in Healthcare
💡 Model Evaluation & Optimization

---

# 🔮 Future Enhancements

🚀 Real-time clinical deployment
🚀 Explainable AI (Grad-CAM visualization)
🚀 Integration with hospital diagnostic systems
🚀 Multi-cancer detection expansion
🚀 Web-based AI diagnostic dashboard
🚀 Federated learning for healthcare privacy

---

# 📄 Research Contribution

📌 This project also contributed toward research work in:

🔹 AI-Based Cancer Detection
🔹 Medical Image Processing
🔹 Deep Learning Optimization
🔹 Histopathological Image Analysis

---

# 👨‍💻 Developed By

## 👤 Harsh Yadav

🧠 AI Researcher | Flutter Developer | Deep Learning Enthusiast

---

# 💬 Project Vision

> “Leveraging deep learning and medical image analysis to build accurate, intelligent, and accessible cancer diagnostic systems for the future of healthcare.”

---
