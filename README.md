# 🖼️ DeepFake Detection Using Convolutional Neural Networks (CNN)

This project leverages CNNs to detect **DeepFake images** by classifying images into **Real** or **Fake**. It uses a custom CNN model trained on a dataset of labeled images.

---

## 🌟 Project Highlights

- **Dataset Preprocessing**: Extracted and organized labeled images from the dataset. 🖼️
- **Custom CNN Model**: Designed a CNN with multiple convolutional blocks for robust classification. 🤖
- **Evaluation Metrics**: Achieved a **ROC-AUC score of 0.966** and **90% classification accuracy**. 📈
- **Model Deployment Ready**: Saved the trained model for practical usage. 💾

---

📊 **Data Overview**

Dataset:

Images are categorized into two classes: Real and Fake.

The dataset is split into training, validation, and test sets.

Classes: Binary classification (Real, Fake).

🤖 **Model Details**

Architecture:

Input Layer: 128x128 grayscale image.

Convolutional Blocks: Seven convolutional layers with ReLU activation.

Pooling Layers: Max-pooling layers for dimensionality reduction.

Dense Layer: Fully connected layer with a sigmoid output for binary classification.

Global Average Pooling: Used to aggregate spatial information.

Loss Function: Binary Cross-Entropy

Optimizer: Adam

🧪 **Model Performance**

Training Accuracy: 93.04%

Validation Accuracy: 91.0%

ROC-AUC Score: 0.966

Average Precision (AP) Score: 0.965
