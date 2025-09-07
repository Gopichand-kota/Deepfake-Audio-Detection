Deepfake Audio Detection
 Project Overview

This project aims to detect deepfake audio-synthetically generated speech-by analyzing audio files and classifying them as real or fake. Utilizing machine learning models such as LSTM, MFCC-based classifiers, and Transformer architectures, the system identifies subtle inconsistencies in audio signals that differentiate genuine speech from AI-generated content.

 Technologies Used

Programming Language: Python 3.8+

Libraries:

librosa: Audio processing and feature extraction

scikit-learn: Machine learning algorithms and preprocessing

tensorflow / keras: Deep learning models

streamlit: Interactive web application for real-time inference

joblib: Model serialization

Development Tools:

Jupyter Notebook / Python Scripts

IDE: VS Code / PyCharm

 Project Structure
deepfake-audio-detection/

1:- data/
 dataset.csv               # Raw dataset
 sample_dataset.csv        # Sample dataset for testing

2:- notebooks/
 DeepFakeAudio.ipynb       # Data exploration and preprocessing
deepfake_voice_classification_lstm.ipynb # LSTM model training

3:-models/
model.py                  # Model training and evaluation
model.pkl                 # Serialized model
Deep-Fake-Audio-Detection__PPT.pptx # Presentation slides

4:-app.py                        # Streamlit app for model deployment
requirements.txt              # Project dependencies
README.md                     # Project documentation

 Dataset

The dataset used in this project consists of audio files labeled as real or fake. It includes features such as:

MFCC (Mel-frequency cepstral coefficients): Represents the short-term power spectrum of sound.

Chroma Features: Relates to the twelve different pitch classes.

Spectral Features: Includes spectral centroid, bandwidth, and flatness.

Zero Crossing Rate: The rate at which the signal changes sign.
