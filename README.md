# 🎧 Quran Audio Classification using CNN

Beginner ML project on Audio Classification. This project implements a Convolutional Neural Network (CNN) for classifying
Quran recitation audio. Audio signals are converted into Mel-spectrograms
and used as input to a CNN model.

## 🔍 Overview
- Audio preprocessing with Librosa
- Mel-spectrogram feature extraction
- CNN-based classification using PyTorch
- Train / validation / test evaluation

## 🧠 Methodology
1. Load Quran recitation audio files
2. Convert audio to Mel-spectrograms
3. Train a CNN on spectrogram images
4. Evaluate classification performance

## 🛠️ Tech Stack
- Python
- PyTorch
- Librosa
- NumPy
- Scikit-learn
- Matplotlib

## 📂 Dataset
Dataset used from Kaggle:
**Quran Recitations for Audio Classification**

Audio files are not included in this repository.

## ▶️ How to Run
```bash
pip install -r requirements.txt
jupyter notebook Audio_Classification_Quran.ipynb
