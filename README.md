# Unimodal-Emotion-Recognition-Text-Audio-and-Video


This repository presents a deep learning-based research project focused on *unimodal emotion recognition* using three independent data streams: *Video, **Audio, and **Text*. Each modality is explored and processed individually to understand how emotions can be effectively classified using only one type of input at a time.

The models are trained and evaluated using domain-specific features and deep learning architectures suitable for each modality. The goal is to assess the performance and characteristics of unimodal systems in recognizing human emotions.

## 📁 Repository Structure

- /Video/  
  Contains all code and resources related to video-based emotion recognition. This includes frame extraction, preprocessing, and CNN-based or 3D CNN-based architectures that learn spatio-temporal features from facial expressions and body gestures.

- /Audio/  
  Focuses on audio-only emotion recognition. It includes audio preprocessing (e.g., MFCC extraction), spectrogram generation, and the use of sequential models such as LSTM and Bi-LSTM to detect emotional tone and prosody in speech signals.

- /Text/  
  Covers text-based emotion classification using natural language processing techniques. The models use tokenization, embedding layers (e.g., GloVe or BERT), and recurrent neural networks to classify text into emotional categories based on semantics and syntax.

## 🎯 Objective

To analyze and compare the effectiveness of *independent unimodal models* in emotion recognition by:
- Isolating the contribution of each modality (video, audio, text).
- Studying the strengths and limitations of modality-specific deep learning models.
- Laying the groundwork for future multimodal integration.

## 📊 Emotion Categories

The models are trained to classify emotions into the following categories:
- *Anger*
- *Fear*
- *Joy*
- *Love*
- *Sadness*
- *Surprise*

