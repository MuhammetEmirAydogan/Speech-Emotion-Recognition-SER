# 🎙️ Speech Emotion Recognition (SER) Project

![Python](https://img.shields.io/badge/Python-3.10-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange)
![Streamlit](https://img.shields.io/badge/Streamlit-App-red)
![License](https://img.shields.io/badge/License-MIT-green)

## 📖 Proje Hakkında (About the Project)
Bu proje, ses verilerini işleyerek konuşmacının duygu durumunu (Mutlu, Kızgın, Üzgün, vb.) tespit eden uçtan uca bir **Yapay Zeka** uygulamasıdır. 

**RAVDESS** veri seti kullanılarak geliştirilen projede; veri işleme, öznitelik çıkarımı (MFCC), veri çoğaltma (Augmentation) ve model kıyaslama (Benchmarking) süreçleri uygulanmıştır.

## 🚀 Özellikler
* **Veri Seti:** RAVDESS (Ryerson Audio-Visual Database of Speech and Song).
* **Preprocessing:** Librosa ile gürültü temizleme, MFCC çıkarma.
* **Modeller:** CNN, LSTM ve MLP mimarileri kıyaslandı.
* **Arayüz:** Streamlit ile web tabanlı prototip geliştirildi.

## 📊 Model Performansları

| Model | Mimari | Doğruluk (Accuracy) |
|-------|--------|---------------------|
| **CNN** | Convolutional Neural Network | **%88.61** 🏆 |
| LSTM  | Long Short-Term Memory | %82.81 🥈 |
| MLP   | Multi-Layer Perceptron | %71.52 🥉 |

## 🛠️ Nasıl Çalıştırılır? (How to Run)

Proje Google Colab veya Jupyter Notebook üzerinde çalıştırılmaya uygundur.

1. `SER_Projesi_Sprint4_Web_App.ipynb` dosyasını açın.
2. Gerekli kütüphaneleri yükleyin.
3. Not defteri içerisindeki adımları takip ederek Web Arayüzünü başlatabilirsiniz.

---
**Geliştirici:** Muhammet Emir Aydoğan