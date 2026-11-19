# 🍅 AI-Based Tomato Plant Disease Detection Using CNN

A deep learning-based web application built from scratch using **Convolutional Neural Networks (CNN)** to detect and classify tomato leaf diseases in real time and provide instant treatment recommendations[cite: 1, 4].

## 📌 Overview
Early identification of crop pathology prevents widespread yield loss. This project automates tomato leaf inspection by training a custom CNN model to distinguish between healthy foliage and major bacterial, fungal, and viral infections, served through an interactive web interface.

## ✨ Key Features
- **Custom CNN Architecture:** Built and trained from scratch to extract spatial and color features of leaf lesions.
- **Multi-Class Disease Classification:** Identifies healthy leaves alongside common tomato infections (such as Bacterial Spot, Early Blight, Late Blight, Leaf Mold, Septoria Leaf Spot, and Yellow Leaf Curl Virus).
- **Real-Time Inference:** Fast image preprocessing and prediction pipeline for instant diagnosis from uploaded leaf photos.
- **Actionable Treatment Guide:** Displays practical organic and chemical management steps tailored to the predicted disease class.

## 🛠️ Tech Stack
- **Deep Learning:** PyTorch / TensorFlow & Keras *(keep the one used in your code)*
- **Image Processing:** OpenCV, PIL, NumPy
- **Web Interface:** Streamlit / Flask *(keep the one used in your code)*
- **Visualization:** Matplotlib, Seaborn

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone [https://github.com/naveenjakkani/AI-Based-Tomato-Plant-Disease-Detection-Using-CNN.git](https://github.com/naveenjakkani/AI-Based-Tomato-Plant-Disease-Detection-Using-CNN.git)
cd AI-Based-Tomato-Plant-Disease-Detection-Using-CNN
```[cite: 4]

### 2. Extract the project archive
```bash
unzip tomato-disease-detection-main.zip
cd tomato-disease-detection-main
```[cite: 4]

### 3. Install dependencies
```bash
pip install -r requirements.txt
