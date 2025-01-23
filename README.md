Overview

This project provides a PyTorch Dataset class, AudioTestDataset, to load, preprocess, and handle MFCC (Mel-Frequency Cepstral Coefficients) test data efficiently. The dataset is designed to handle audio features for test data and supports context-based sampling for machine learning tasks such as speech recognition.

Features:
1. Loads MFCC files from a specified directory.
2. Processes MFCC data with cepstral normalization along the time axis.
3. Supports context padding for providing neighboring frames.
4. Ensures that test data is loaded in a sorted order without shuffling, adhering to Kaggle submission requirements.

Requirements:
1. Python 3.8+
2. PyTorch 1.10+
3. NumPy
4. tqdm (optional, for progress visualization during data loading)
