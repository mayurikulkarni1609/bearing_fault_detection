# Bearing Fault Detection

Machine learning project for detecting and classifying bearing faults using vibration signals from the CWRU dataset.

## Fault Classes
- Normal
- Inner Race Fault (BPFI)
- Outer Race Fault (BPFO)
- Ball Fault (BSF)

## Feature Extraction

### Time-Domain Features
- RMS
- Mean
- Standard Deviation
- Kurtosis
- Skewness
- Peak
- Crest Factor

### Frequency-Domain Features
- Spectral Mean
- Spectral Standard Deviation
- Spectral Skewness
- Spectral Kurtosis
- Peak Frequency
- Signal Energy

### Time-Frequency Features
- Wavelet Packet Transform (WPT) energy features
- Wavelet: db4
- Decomposition level: 4

## Machine Learning Classifiers
- K-Nearest Neighbors (KNN)
- Decision Tree
- Support Vector Machine (SVM)
- Naive Bayes

## Dataset
Case Western Reserve University (CWRU) Bearing Dataset

- Sampling rate: 48 kHz
- Load condition: 1 HP

Download the `.mat` files from Kaggle or the official CWRU repository and place them directly inside the project folder.

## Project Objective
To compare the effectiveness of time-domain, frequency-domain, and time-frequency domain features for bearing fault classification.

## Novelty
Wavelet Packet Transform (WPT) features are specifically used to improve Ball Fault (BSF) classification performance, addressing a limitation identified in:

Alonso-González et al., 2023, IEEE Access
