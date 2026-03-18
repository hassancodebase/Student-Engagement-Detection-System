# 🎓 Student Engagement Detection System

**AI-Based Student Engagement Detection in Online Classes Using Optimized MobileNetV2**

## 📌 Project Overview

Student engagement is a critical factor influencing learning outcomes in online education, yet it is difficult to monitor in virtual environments. This project presents an **AI-based student engagement detection system** that analyzes facial expressions to classify student engagement levels in real time.

The system leverages **transfer learning with MobileNetV2**, applies multiple optimization techniques, and compares performance against a **custom CNN model**. Experimental results demonstrate that the **optimized MobileNetV2 model** achieves the highest accuracy while maintaining computational efficiency suitable for real-time educational platforms.

## 🎯 Objectives

- Automatically detect student engagement during online classes  
- Compare baseline and optimized deep learning models  
- Evaluate performance using standard classification metrics  
- Address ethical and practical challenges in AI-based education systems  

## 🧠 Engagement Categories

The system classifies students into the following six engagement-related categories:

- Engaged  
- Confused  
- Frustrated  
- Bored  
- Drowsy  
- Looking Away  

## 🧪 Models Implemented

### 🔹 Baseline MobileNetV2
- Transfer learning with frozen base layers  
- Lightweight and efficient architecture  

### 🔹 Optimized MobileNetV2 (Best Model)
- Enhanced dense layers  
- Batch normalization  
- Dropout regularization  
- Tuned learning rate  

### 🔹 Custom CNN
- Traditional convolutional neural network architecture  
- Implemented for comparative performance analysis  

## 📊 Results Summary

| Model                  | Accuracy (%) |
|------------------------|--------------|
| Baseline MobileNetV2   | 94.58        |
| Optimized MobileNetV2  | **95.68**    |
| Custom CNN             | 93.25        |

The **optimized MobileNetV2** demonstrated improved generalization, reduced overfitting, and superior performance across **precision, recall, and F1-score** metrics.

## ⚙️ Technologies Used

- **Programming Language:** Python  
- **Frameworks & Libraries:** TensorFlow, Keras  
- **Deep Learning Models:** MobileNetV2, CNN  
- **Data Processing:** NumPy, OpenCV  
- **Visualization:** Matplotlib, Seaborn  
- **Development Platform:** Google Colab  

## 📥 Dataset Information

This project uses the **Student Engagement Facial Expression Dataset** obtained from **Kaggle**.

⚠️ Due to licensing restrictions, the dataset is **not included** in this repository.

Dataset download instructions and details can be found in:

dataset/README.md

## ▶️ How to Run the Project

### 1️⃣ Clone the Repository

### 2️⃣ Extract the zip file of Dataset

### 3️⃣ Place the dataset to the appropriate directory

### 4️⃣ Run the Notebooks

Open Google Colab and run:

- `StudentEngagementDetection_v1.ipynb`
- `StudentEngagementDetection_v2.ipynb`

## ⚠️ Ethical & Practical Considerations

- **Data Privacy:** User consent and secure data storage are essential
- **Bias & Fairness:** Balanced datasets and regular bias audits are required
- **Deployment Challenges:** Hardware limitations and internet reliability
- **Responsible AI:** Ethical handling of facial data in educational environments

## 🎓 Academic Context

- **Course:** Artificial Intelligence
- **Semester:** 3rd
- **Assignment Type:** Project-Based Learning (PBL)
- **Department:** Software Engineering

## 🔮 Future Enhancements

- 🎧 Multimodal engagement detection (audio + gaze)
- 🔍 Explainable AI (XAI) for transparency
- 🔐 Federated learning for privacy preservation
- 🏫 Real-time deployment in smart classrooms

## 👤 Author

- **MUHAMMAD HASSAN**
- Software Engineering Student
- Batch 2024 – Fall 2025
