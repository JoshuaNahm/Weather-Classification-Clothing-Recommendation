# DS340 Project: Weather Classification & Clothing Recommendation System

## 📋 Project Overview

This project was conducted to develop a deep learning model that classifies weather conditions from images and recommends appropriate clothing based on the detected weather.

By leveraging **Convolutional Neural Networks (CNNs)** and **transfer learning**, we aimed to bridge the gap between weather forecasts and actionable advice.

- **Focus:** Weather image classification & rule-based clothing recommendations

The project was divided into key phases:

1. **Data Collection & Preprocessing**
2. **Model Development (CNN & Transfer Learning)**
3. **Ensemble Learning for Improved Accuracy**
4. **Clothing Recommendation System**

---

## ⚙️ Technologies Used

- **Programming Language:** Python
- **Frameworks:** TensorFlow, Keras
- **Model Architectures:** Custom CNN, VGG19, ResNet50, MobileNet
- **Techniques:** Data Augmentation, Transfer Learning, Ensemble Learning

---

## 🚀 Methodology

### 1. **Data Preprocessing**

- Resized images to 100x100 pixels for model compatibility.
- Applied data augmentation techniques:
  - Random rotations (up to 30°)
  - Zooming (±15%)
  - Horizontal flipping
  - Brightness adjustments
  - Shifting images horizontally/vertically (up to 20%)

### 2. **Model Development**

- **Custom CNN:** Established baseline performance with a simple architecture.
- **Transfer Learning:**
  - Fine-tuned pre-trained models (VGG19, ResNet50, MobileNet) from ImageNet.
  - Added custom dense layers for weather classification.

### 3. **Ensemble Learning**

- Combined predictions from multiple models to improve accuracy and reduce overfitting.
- Ensemble models outperformed individual models, showcasing better generalization.

### 4. **Clothing Recommendation System**

- Rule-based system providing clothing suggestions based on classified weather conditions:
  - E.g., **Rainy:** Raincoat, umbrella | **Snowy:** Thick jackets, boots

---

## 📈 Results & Key Findings

- **Custom CNN:** 66% accuracy (baseline)
- **VGG19:** 77% accuracy
- **MobileNet:** 80% accuracy (lightweight, suitable for deployment)
- **ResNet50:** **83% accuracy** (best performance)

- **Key Observations:**
  - ResNet50 demonstrated excellent generalization due to its skip connections.
  - MobileNet offered a good balance between efficiency and accuracy.
  - Data augmentation significantly improved model robustness.

---

## ✅ Insights & Recommendations

- **ResNet50** is the most reliable model for weather classification.
- **Ensemble Learning** enhances accuracy compared to single models.
- **Data Augmentation** is crucial for handling real-world image variability.

---

## 🎯 Conclusion

This project successfully demonstrated the potential of combining **image classification** with **practical recommendations**.

By utilizing transfer learning and ensemble models, we achieved high accuracy in classifying weather conditions and provided actionable clothing recommendations, enhancing user convenience in daily decision-making.
"""
