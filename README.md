# Vowel Speech Recognition

A Python project for vowel classification using Mel-Frequency Cepstral Coefficients (MFCCs) and a K-Nearest Neighbours (KNN) classifier.

## About

This project is an adapted version of a laboratory assignment from the **PSPM (Processing Speech and Music)** course. The original lab has been reorganized into a standalone machine learning project with improved documentation and result visualization.

## Contents

* `Speech_Recognition.ipynb` – Complete notebook containing the implementation, experiments, visualizations, and discussion.
* `requirements.txt` – Required Python libraries.
* `DBvocals_train_list_times.txt` – Training annotations.
* `DBvocals_test_list_times.txt` – Testing annotations.
* `DB/DBvocals/` – Audio recordings used in the experiments.

The notebook includes:
* Audio preprocessing
* MFCC feature extraction
* Frame-level vowel labelling
* KNN classification
* Accuracy evaluation
* Results visualization

## Requirements

Install the required packages:

```bash
pip install -r requirements.txt
