# 🧠 Skin Disease Classification using Deep Learning

## 📌 Overview
Skin diseases affect millions of people worldwide, and early detection plays a crucial role in effective treatment. This project presents an **AI-powered skin disease classification system** using **Convolutional Neural Networks (CNNs)** to analyze dermoscopic images and predict various skin conditions.

The system allows users to upload an image and receive **real-time predictions**, confidence scores, and basic medical recommendations.

---

## 🎯 Objectives
- Develop an automated skin disease detection system
- Implement CNN for multi-class classification
- Provide real-time predictions via web interface
- Evaluate performance using accuracy, precision, recall, and F1-score

---

## 🧪 Dataset
- **Name:** HAM10000 Dataset  
- **Source:** Kaggle  
- **Link:** https://www.kaggle.com/datasets/kmader/skin-cancer-mnist-ham10000  
- **Description:**  
  A dataset of ~10,000 dermoscopic images categorized into 7 different skin diseases.

---

## ⚙️ Technologies Used
- **Programming Language:** Python  
- **Deep Learning:** TensorFlow, Keras  
- **Image Processing:** OpenCV  
- **Visualization:** Matplotlib, Seaborn  
- **Web Framework:** Flask  
- **Development Tools:** Jupyter Notebook / Google Colab  

---

## 🚀 Features
- Multi-class skin disease classification  
- Real-time image prediction  
- Confidence score display  
- Probability analysis visualization  
- Confusion matrix and performance metrics  
- User-friendly web interface  
- Scalable architecture  

---

## 🧠 Model Architecture
- Convolutional Neural Network (CNN)
- Layers:
  - Conv2D + ReLU
  - MaxPooling
  - Dropout
  - Fully Connected Dense Layers
- Optimizer: Adam  
- Loss Function: Categorical Crossentropy  

---

## 🔄 Workflow
1. Data Collection (HAM10000 dataset)
2. Data Preprocessing (resizing, normalization, augmentation)
3. Model Training using CNN
4. Model Evaluation (accuracy, loss, confusion matrix)
5. Deployment using Flask
6. User uploads image → Model predicts disease

---

## 📊 Results
- Achieved ~85%+ training accuracy
- Good validation performance
- Effective classification across 7 categories
- Visualized using:
  - Accuracy & Loss graphs
  - Confusion Matrix

---

## Install Dependencies
pip install -r requirements.txt

## Run Flask App
python app.py

## ⚠️ Limitations
Requires high-quality dermoscopic images
Limited dataset diversity
Not a replacement for medical professionals
May not generalize to all skin tones

## 🔮 Future Scope
Mobile app integration
Transfer learning (ResNet, EfficientNet)
Real-time camera detection
Cloud deployment
Explainable AI (XAI)

## 💡 Project Impact
Supports early detection of skin diseases
Reduces dependency on dermatologists for initial screening
Useful in rural and remote areas
Demonstrates AI in healthcare applications
