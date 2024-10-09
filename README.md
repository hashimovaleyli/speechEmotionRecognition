Project Overview
This project implements a Speech Emotion Recognition (SER) system using audio data and a Convolutional Neural Network (CNN) model. The goal is to classify emotions expressed in speech such as anger, fear, happiness, sadness, etc. Audio features like Mel Frequency Cepstral Coefficients (MFCCs), zero crossing rate, and root mean square are extracted using librosa, and data is augmented to improve model performance.

Key Components
Data Loading & Preprocessing:

Audio data is loaded, emotions are categorized based on file names, and visualizations of audio signals (waveplots) are generated.
Data Augmentation:

Techniques such as noise injection, time stretching, and pitch shifting are used to increase the diversity of the training data.
Feature Extraction:

Extracts key audio features like zero crossing rate, spectral centroid, root mean square, and MFCC to represent each audio file numerically.
Model Development:

A CNN model is built using Keras to classify the emotions from the extracted features. The model is trained, validated, and tested on the dataset.
