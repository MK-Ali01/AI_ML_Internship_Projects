\# German Traffic Sign Recognition (GTSRB)



\## 📌 Project Overview

This project implements a deep learning solution for traffic sign classification using the \*\*German Traffic Sign Recognition Benchmark (GTSRB)\*\* dataset.



The objective is to classify traffic signs into 43 different categories using:

\- A Custom Convolutional Neural Network (CNN)

\- A Pre-trained MobileNet model (Transfer Learning)



This project also compares both approaches in terms of accuracy and generalization.



---



\## 🎯 Problem Statement

Autonomous vehicles and driver assistance systems rely on accurate traffic sign recognition. The goal of this project is to:



\- Build a custom CNN from scratch

\- Apply transfer learning using MobileNet

\- Compare performance between both models

\- Evaluate using accuracy and confusion matrix



---



\## 📊 Dataset

Dataset Used: \*\*German Traffic Sign Recognition Benchmark (GTSRB)\*\*



\- 43 traffic sign classes

\- Thousands of labeled images

\- Different lighting, angles, and background conditions



You can download the dataset from:

https://benchmark.ini.rub.de/gtsrb\_news.html



Or from Kaggle:

https://www.kaggle.com/datasets/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign



---



\## 🛠 Tools \& Libraries

\- Python

\- NumPy

\- Pandas

\- OpenCV

\- Matplotlib

\- TensorFlow / Keras

\- Scikit-learn



---



\## 🧠 Models Implemented



\### 1️⃣ Custom CNN

\- Conv2D + ReLU

\- MaxPooling

\- Dropout

\- Dense layers

\- Softmax output (43 classes)



\### 2️⃣ MobileNet (Transfer Learning)

\- Pre-trained on ImageNet

\- include\_top=False

\- GlobalAveragePooling

\- Dense classification head

\- Base model frozen during training



---



\## 🔄 Workflow



1\. Load and resize images (32x32 or 224x224 for MobileNet)

2\. Normalize pixel values

3\. Convert labels to categorical

4\. Train Custom CNN

5\. Train MobileNet model

6\. Compare:

&nbsp;  - Training accuracy

&nbsp;  - Validation accuracy

&nbsp;  - Loss curves

7\. Evaluate on test data

8\. Plot confusion matrix



---



\## 📊 Results Visualization

\- Accuracy vs Epochs plot

\- Loss vs Epochs plot

\- Confusion Matrix

\- Sample predictions visualization



---



\## 🚀 How to Run



1\. Clone the repository:



git clone https://github.com/YOUR\_USERNAME/AI\_ML\_Internship\_Projects.git



2\. Navigate to this folder:

\_GermanTrafficSignClassification





Run all cells sequentially.



---



\## 📌 Key Learning Outcomes

\- Understanding CNN architecture design

\- Transfer learning using MobileNet

\- Handling image datasets in TensorFlow

\- Model comparison and evaluation

\- Practical application in computer vision



---



\## 🔮 Future Improvements

\- Fine-tune MobileNet layers

\- Data augmentation for better generalization

\- Deploy as a web app using Streamlit

\- Convert model to TensorFlow Lite for embedded systems



---



\## 👤 Author

Muhammad Khizer Ali  

AI \& ML Student | Deep Learning Enthusiast

