# Lung-Cancer-Detection
Lung cancer detection from histopathological images using six CNN models (VGG16, ResNet50, DenseNet121, MobileNetV2, InceptionV3, Xception) with advanced preprocessing (edge detection, histogram equalization, blurring). Xception achieved 99.46% accuracy (99.53% fine-tuned), proving CNNs with enhancements enable accurate, automated diagnosis.
# 🫁 Lung Cancer Detection Using Deep Learning with Enhanced CNN Architectures

## 📌 Overview
This project focuses on **automated classification of histopathological lung images** into three categories:
- **Normal Lung Tissue**
- **Lung Adenocarcinoma**
- **Lung Squamous Cell Carcinoma**

We evaluate **six pre-trained CNN architectures**:
- VGG16
- ResNet50
- DenseNet121
- MobileNetV2
- InceptionV3
- Xception

Advanced **image enhancement techniques** were applied to improve classification accuracy.

---

## 🗂 Dataset
- **Source:** Public Lung & Colon Cancer Histopathological Image Dataset
- **Total Images:** 15,000 (balanced classes)
- **Split:** 70% Train, 20% Validation, 10% Test
- **Image Size:**  
  - 224×224 (VGG16, ResNet50, DenseNet121, MobileNetV2)  
  - 299×299 (InceptionV3, Xception)  

---

## 🛠 Image Enhancement Techniques
- Sobel Edge Detection  
- Canny Edge Detection  
- Unsharp Masking  
- Histogram Equalization  
- Median Blurring  
- Gaussian Blurring  
- Non-Local Means Denoising  
- Morphological Operations  
- **Final Processed Combinations** (M+H+C+MR, MR+C+H+M, etc.)

---

## ⚙ Methodology
1. **Preprocessing** → Resize, normalize, and enhance images  
2. **Feature Extraction** → Transfer learning from ImageNet weights  
3. **Training** → Adam optimizer, batch size 46, 10 epochs  
4. **Evaluation** → Accuracy, Confusion Matrix, ROC Curves  
5. **Fine-Tuning** → Unfreeze selected layers for improved accuracy

---

## 📊 Results

| Model        | Best Enhancement  | Test Accuracy (%) | Fine-Tuned Accuracy (%) |
|--------------|-------------------|-------------------|-------------------------|
| Xception     | Histogram Eq.     | **99.46**         | **99.53**               |
| ResNet50     | Median Blur       | 97.23              | 99.93                   |
| InceptionV3  | Unsharp Masking   | 98.97              | 99.83                   |
| DenseNet121  | Original          | 95.83              | 99.53                   |
| VGG16        | Original          | 98.46              | 99.93                   |
| MobileNetV2  | Final Proc. 2     | 96.36              | 99.87                   |

✅ **Image enhancement significantly improved CNN accuracy**  
✅ **Xception, ResNet50, and InceptionV3 are top performers**  

---

## 📂 Repository Structure
