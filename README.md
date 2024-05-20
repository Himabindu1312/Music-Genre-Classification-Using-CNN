## Music Genre Classification Using Neural Networks and CatBoost

## Overview:
This repository contains code for a music genre classification project using machine learning techniques. The project utilizes neural networks implemented with TensorFlow/Keras and the CatBoost algorithm for classification tasks.

## Requirements:
Python 3.x
Libraries: numpy, pandas, matplotlib, scipy, scikit-learn, librosa, tensorflow, xgboost, catboost, ipywidgets
## Dataset:
The dataset used in this project is the GTZAN genre collection, which contains audio samples from 10 different genres. The features extracted from the audio files include various statistical properties and spectrogram-related features.

## File Descriptions:
music_genre_classification.ipynb: Jupyter Notebook containing the code for data preprocessing, feature extraction, model building, training, evaluation, and visualization.
README.md: This file providing an overview of the project and instructions for setup.
LICENSE: License information for the project.
## Usage:
Clone the repository to your local machine.
Install the required dependencies using pip: pip install -r requirements.txt
Run the Jupyter Notebook music_genre_classification.ipynb to execute the code step by step.
## Results:
The neural network model achieved a test accuracy of approximately 93%.
The CatBoost classifier obtained an accuracy of around 90%.
