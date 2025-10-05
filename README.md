# OCR-Alphanumeric-CNN (A–Z, 0–9)

This project builds a **Convolutional Neural Network (CNN)** model to classify handwritten characters consisting of **letters (A–Z)** and **digits (0–9)**. The dataset used is **[Standard OCR Dataset](https://www.kaggle.com/datasets/preatcher/standard-ocr-dataset/)**.

---

## ⚙️ Libraries
- TensorFlow / Keras  
- NumPy  
- Matplotlib  
- scikit-learn  

---

## 🏗️ Model Architecture
The model is based on a simple **CNN**, including:
- Conv2D + MaxPooling layers (feature extraction)  
- Flatten + Dense layers (classification)  
- Softmax output with **36 classes (0–9, A–Z)**  

---

## 🚀 Results
- Training accuracy: **~97%**  
- Validation accuracy: **~95%**  
- Test accuracy: **~94%**  

The model performs well in recognizing handwritten letters and digits, with minor misclassifications in similar-looking characters (e.g., `O` vs `0`).  

---

## 📌 Notes
- Input images are **grayscale** with size **64x64**.  
