# Emotion Detection in Job Interviews using Speech Analysis

## Overview
This project focuses on detecting human emotions during job interviews by analyzing speech signals. It leverages Machine Learning and Deep Learning techniques to classify emotions such as stress, confidence, nervousness, and neutrality from audio input.

The system aims to assist recruiters in understanding candidate behavior and emotional state during interviews, enabling more data-driven hiring decisions.

---

##  Features
-  Audio-based emotion detection
-  Feature extraction using MFCC, pitch, and energy
-  Deep Learning model (LSTM)
-  Real-time or recorded audio analysis
-  User-friendly interface

##  Tech Stack
- **Programming Language:** Python  
- **Libraries:**  
  - Librosa (audio processing)  
  - NumPy, Pandas  
  - Scikit-learn  
  - TensorFlow / Keras  
- **Visualization:** Matplotlib, Seaborn  
- **Deployment (optional):** Streamlit / Flask  

##  Project Architecture
Audio Input → Preprocessing → Feature Extraction → Model (LSTM) → Emotion Output


---

## 🔍 Methodology

### 1. Data Collection
- Public datasets such as:
  - RAVDESS (Ryerson Audio-Visual Database of Emotional Speech)
  - TESS (Toronto Emotional Speech Set)

### 2. Preprocessing
- Noise reduction
- Audio normalization
- Sampling rate standardization

### 3. Feature Extraction
- MFCC (Mel Frequency Cepstral Coefficients)
- Chroma features
- Spectral contrast
- Zero Crossing Rate

### 4. Model Building
- LSTM (Long Short-Term Memory) network used for sequence modeling
- Captures temporal dependencies in speech signals

### 5. Evaluation
- Accuracy, Precision, Recall, F1-score

##  Output Emotions
- Happy 
- Sad 
- Angry 
- Neutral 
- Fear 
- Disgust 
- Surprise 
-  Stress / Confidence detection

## 📁 Project Structure
src/ -> source code files 
docs/ -> project documentation 
requirements.txt -> python dependencies
setup_intructions.md -> Steps to run the project
