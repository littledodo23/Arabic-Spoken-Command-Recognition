# Arabic-Spoken-Command-Recognition
A spoken Arabic command recognition system using MFCC features and classical ML classifiers (SVM, KNN, GMM, Random Forest).
# Commands

افتح، اغلق، ابدأ، توقف، يمين، يسار
# Results
Best accuracy: 95.56% (SVM, KNN, GMM)

# How it works

1-Preprocess audio (silence removal + normalization)
2-Extract 20 MFCC features → 40-dim vector (mean + std)
3-Train & compare classifiers
# Dataset
https://drive.google.com/drive/u/0/folders/1_ynpDqRgfeB2MgxOuq8KbLB9ubGI9tJq
# Requirements
librosa, scikit-learn, numpy
