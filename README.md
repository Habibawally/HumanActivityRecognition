# Human Activity Recognition

This project focuses on recognizing human physical activities using machine learning techniques applied to sensor data. The analysis is done using a Jupyter Notebook.

## 📁 File Included

- `Recognition_of_human_activity (2).ipynb`: A notebook containing data preprocessing, model training, and evaluation steps for activity recognition.

## 📌 Key Features

- Data visualization and preprocessing
- Machine learning model training
- Evaluation metrics and analysis
- Human activity classification

- 
## 🧠 Key Concepts

### 🔹 Autoencoder (AE)

An **Autoencoder** is a type of neural network used to learn efficient representations (encodings) of input data in an unsupervised manner. It consists of two main parts:

- **Encoder**: Compresses the input data into a lower-dimensional latent representation.
- **Decoder**: Reconstructs the input data from the latent representation.

Autoencoders are useful for dimensionality reduction, feature extraction, and anomaly detection.

---

### 🔹 Denoising Autoencoder (DAE)

A **Denoising Autoencoder** is a variant of the standard Autoencoder designed to remove noise from data. It is trained by intentionally corrupting the input data (adding noise), then learning to reconstruct the clean/original version of it.

📌 Why use DAE?

- To improve robustness of learned features.
- To remove unwanted noise from sensor signals (e.g., EMG, IMU, accelerometers).
- Commonly used in biomedical signal preprocessing or human activity recognition.

---

### ✨ Use in This Project

In the context of **Human Activity Recognition**, Autoencoders and Denoising Autoencoders can help in:

- Learning compact representations of time-series data.
- Enhancing model performance by reducing noise from sensor signals.
- Improving classification accuracy by extracting denoised features before feeding into classifiers (e.g., LSTM, CNN, or Random Forest).

## 🧠 Algorithms Used

- Classification models (e.g., Decision Tree, Random Forest, or others used in the notebook)
- Data normalization and feature extraction
- Confusion matrix and accuracy metrics

## 📊 Dataset

>📁 Dataset used: `dataset/UCI(Dataset)` (from UCI Human Activity Recognition Dataset)


## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Habibawally/HumanActivityRecognition.git
   cd HumanActivityRecognition
