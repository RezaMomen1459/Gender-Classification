# Gender-Classification
# 🎭 Gender Classification using Transfer Learning (VGG16)

An end-to-end Deep Learning pipeline built with TensorFlow/Keras that accurately classifies gender from facial images using a pre-trained **VGG16** backbone and custom classification heads.

---

## 📥 Model Weights

Due to GitHub's file size limit (100MB), the trained VGG16 model weights (`Best_GENDER_Model.keras`, ~115MB) are hosted externally:

👉 **[Download Trained VGG16 Model from Google Drive](https://drive.google.com/file/d/1OB-8vITre-DGQN4YaRRPDv0CqHw-pF3F/view?usp=drive_link)**

---

## 📌 Project Overview

This repository demonstrates the application of **Transfer Learning** in Computer Vision. By leveraging feature representations learned from ImageNet via VGG16, the model achieves high training efficiency and generalization accuracy on facial gender recognition.

### 🔑 Key Technical Highlights
- **Architecture:** Pre-trained `VGG16` backbone paired with custom Dense layers and $L_2$ regularization to prevent overfitting.
- **Pipeline & Preprocessing:** Advanced data preprocessing, dynamic color conversion (BGR to RGB), and dynamic data augmentation (`ImageDataGenerator`).
- **Optimization & Callbacks:** Integrated `ModelCheckpoint`, `ReduceLROnPlateau`, and `EarlyStopping` for optimal convergence.

---

## 🛠️ Tech Stack & Tools

- **Language:** Python 3.x
- **Frameworks:** TensorFlow / Keras
- **Computer Vision & Math:** OpenCV, NumPy, Pandas
- **Visualization:** Matplotlib, Seaborn

---

## 👤 Mentorship & Acknowledgment

Special thanks to **Mehrshad Eisaei** for technical supervision and guidance throughout this project.
