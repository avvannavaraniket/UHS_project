# UHS_project
# Audio Classification using MFCC (Cats vs Dogs)

## Overview
This project implements an end-to-end audio classification pipeline using MFCC features and machine learning. The Cats vs Dogs audio dataset is used as a benchmark to validate the approach before applying it to jackfruit maturity assessment.

## Dataset
- Dataset: Cats vs Dogs Audio Dataset (Kaggle)
- Sampling Rate: 16 kHz
- Classes: Cat, Dog

## Methodology
1. Audio loading and preprocessing
2. Fixed-length normalization (crop & pad)
3. MFCC feature extraction
4. Feature vector formation (mean & std)
5. Audio augmentation (noise, volume, time shift)
6. SVM classification
7. Evaluation using accuracy and confusion matrix

## Results
- Model performance compared before and after augmentation
- Augmentation improves robustness and generalization

## Relevance to Jackfruit Project
The same pipeline can be directly applied to jackfruit tapping sounds for non-destructive maturity assessment.

## How to Run
Open the notebook and run cells sequentially. Dataset can be accessed via Kaggle.
