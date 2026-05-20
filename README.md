# 🎧 ML Audio Emotion Visualizer

**🤖 AI/ML Project | Audio Emotion Recognition & Visualization**

A machine learning–based project built in Google Colab that analyzes audio and generates visual representations driven by predicted emotional state (mood). The project combines audio feature processing with deep learning to create emotion-driven visualizations.

## 🧠 Overview

This project explores the relationship between audio signals and emotion by:
- Extracting audio features from input sound
- Using a trained CNN model to predict emotional state
- Mapping predictions through a custom mood table system
- Generating visual outputs based on predicted mood

The entire workflow was developed and executed in **Google Colab notebooks**.

---

## 📁 Repository Structure

```text
music-emotion-cnn-training.ipynb      # CNN model training on music emotion dataset
audio-to-visualizer-pipeline.ipynb    # End-to-end audio → emotion → visual pipeline
audio_mood_csv.ipynb                  # Audio analysis and mood CSV generation
audio_mood_video_generator.ipynb       # Generates videos from mood and audio features

emotion_model/
├── best_cnn_model.keras              # Trained CNN model for emotion classification
├── label_scaler.pkl                  # Label/feature scaler used for normalization
├── config.json                       # Model configuration and parameters
```
