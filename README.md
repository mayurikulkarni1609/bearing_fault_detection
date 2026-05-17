# Bearing Fault Detection

Machine learning project to detect and classify bearing faults using vibration signals from the CWRU dataset.

## Classes
- Normal
- Inner Race Fault (BPFI)
- Outer Race Fault (BPFO)
- Ball Fault (BSF)

## Features Extracted
- Time domain: RMS, Mean, Std, Kurtosis, Skewness, Peak, Crest Factor
- Frequency domain: Spectral Mean, Std, Skewness, Kurtosis, Peak Frequency, Energy
- Time-frequency domain: WPT energy features (db4 wavelet, level 4)

## Classifiers
KNN, Decision Tree, SVM, Naive Bayes

## Dataset
CWRU Bearing Dataset — 48k sampling rate, load condition 1
Download from Kaggle and place .mat files directly in project folder.

## Novelty
WPT features specifically improve Ball Fault (BSF) classification — a gap identified in the base paper (Alonso-González et al., 2023, IEEE Access).
