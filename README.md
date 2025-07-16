# Deep Learning Based Emotion Analysis from EEG Data

This project implements a deep learning-based approach to recognize emotional states from EEG signals using an LSTM (Long Short-Term Memory) neural network. The EEG signals are preprocessed using Fast Fourier Transform (FFT) to extract frequency-domain features for effective learning and classification.

## 🧠 Objective

To analyze brainwave signals (EEG) and classify emotional states such as **Happy**, **Sad**, **Fearful**, etc., using a robust LSTM model trained on frequency-based features extracted via FFT.

## 📌 Features

- Preprocessing of raw EEG signals using **Fast Fourier Transform (FFT)**
- Emotion classification using a **deep LSTM model**
- Custom dataset support (e.g., recorded using Muse headband or Emotiv)
- Real-time or offline batch analysis
- Accuracy and loss visualization after training

## 🧪 Model Architecture

- Input: FFT-transformed EEG data (multi-channel)
- LSTM layers for temporal sequence learning
- Dense layers for classification
- Output: Emotion class probabilities


## 📊 Dataset Used

- EEG signals recorded using Muse headband or similar devices
- Dataset includes emotional labels (e.g., Postive , Negative, Neutral)
- Input format: CSV with time-series EEG channel data and corresponding emotion labels

## 🧪 Evaluation Metrics

- Accuracy
- Loss
- Confusion Matrix
- Precision / Recall / F1 Score

## 🛠️ Tech Stack

- Python
- NumPy, Pandas
- Matplotlib, Seaborn
- TensorFlow / Keras
- Scikit-learn

> Accuracy may vary depending on dataset quality and size.

## ✍️ Author

**Mahesh Nayak**  
[GitHub](https://github.com/mahesh-nayak53) | [LinkedIn](https://www.linkedin.com/in/mahesh-nayak-008159281/)

