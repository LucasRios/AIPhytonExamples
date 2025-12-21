# AI Python Examples 🤖🐍

This repository contains a collection of practical examples in Artificial Intelligence and Image Processing using Python. The goal is to demonstrate everything from basic data manipulation to training deep neural networks.

---

## 🚀 Projects in this Repository

### 1. Cat vs. Dog Classifier (Transfer Learning)
A Deep Learning model that leverages the **VGG16** architecture (Transfer Learning) to classify animal images.
- **Technologies:** TensorFlow, Keras, NumPy.
- **Highlights:** - Handling corrupted images during the loading process.
    - RAM optimization using `float16` and manual cache clearing (`gc.collect`).
    - Prediction interface with human-readable probability outputs.

### 2. Image Transformation: Color to Binary (Black & White)
A script focused on Digital Image Processing (DIP) to convert color photos into grayscale and binary (black and white) images without relying solely on built-in high-level functions.
- **Technologies:** OpenCV, PIL (Pillow), Matplotlib, NumPy.
- **Concepts:** Grayscale conversion (Luminosity Method), Thresholding (binarization), and pixel matrix manipulation.

---

## 🛠️ Install dependencies
 
   ```bash
   pip install tensorflow numpy matplotlib pillow opencv-python requests
   ```
---

## 🧠 Core Concepts Applied

  Data Normalization: Scaling pixel values to the [0, 1] range for faster neural network convergence.
  One-Hot Encoding: Converting categorical labels into numerical vectors for multi-class classification.
  Memory Management: Strategies to handle large datasets (like Kaggle Cats and Dogs) in RAM-limited environments (Google Colab Free).
  Thresholding: Segmenting images by intensity levels to isolate foreground objects from the background.
  Luminosity Formula: Implementing Y=0.299R+0.587G+0.114B for accurate grayscale conversion.

## 📄 License
This project is licensed under the MIT License - see the LICENSE file for details.

