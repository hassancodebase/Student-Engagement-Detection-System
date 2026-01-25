# Trained Models

This directory is intended to store trained deep learning models used in the **Student Engagement Detection System**.

## 📌 Models Used in This Project

The following models were trained and evaluated:

### 1️⃣ Baseline MobileNetV2
- Architecture: MobileNetV2 (transfer learning)
- Pre-trained on: ImageNet
- Trainable layers: Frozen base model
- Purpose: Baseline performance comparison

### 2️⃣ Optimized MobileNetV2
- Architecture: MobileNetV2 + optimized dense layers
- Optimization Techniques:
  - Hyperparameter tuning (learning rate)
  - Increased dense layer capacity
  - Batch normalization
  - Dropout regularization
- Best performing model in this study

### 3️⃣ Custom CNN
- Architecture: Traditional CNN
- Layers:
  - Convolution + MaxPooling blocks
  - Fully connected dense layers
- Purpose: Comparison with transfer learning models

## 💾 Model Files

Due to file size limitations and repository best practices, **trained model files (`.keras`, `.h5`) are not included** in this GitHub repository.

You can generate the models locally by running the training notebooks:

- `notebooks/StudentEngagementDetection_v1.ipynb`
- `notebooks/StudentEngagementDetection_v2.ipynb`

## ⚠️ Notes
- Ensure sufficient disk space before saving models.
- GPU acceleration (Google Colab) is recommended for training.
- Model performance may vary slightly due to random initialization and dataset splits.
