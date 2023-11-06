# Welcome to Classically Punk
***

## Task
The problem involves classifying music tracks into the "Classically Punk" genre. 

The challenge lies in accurately identifying the distinguishing audio features of this specific 
genre from a diverse dataset. It requires extracting meaningful features and training a machine 
learning model to make precise genre predictions.


## Description
To address this challenge, the code defines a comprehensive pipeline. It starts by extracting 
relevant audio features such as chroma energy, MFCC, chroma STFT, zero-crossing rate, 
spectral centroid, and spectral rolloff from the audio files. These features provide crucial 
information for genre classification.

The dataset is then split into training, validation, and test sets, followed by scaling the features 
using StandardScaler. A neural network model is constructed using Keras and TensorFlow, with 
layers for feature processing and genre classification. The model is trained on the training data 
and evaluated on the test set.


## Installation
The code provided doesn't require installation via npm or make. It's a Python script that you 
can run directly if you have the necessary libraries installed, such as Librosa, NumPy, pandas, 
Matplotlib, scikit-learn, and TensorFlow.


## Usage
To utilize the code, you need to provide a dataset of music tracks, organized into subfolders by genre. You can then run the code, which performs the following steps:

•	Extracts audio features from the dataset.
•	Visualizes audio waveforms, MFCC spectrograms, chroma energy spectrograms, chroma 
    STFT spectrograms, zero-crossing rate plots, spectral centroid plots, and spectral rolloff 
    plots for exploratory data analysis (EDA).
•	Splits the data into training and testing sets.
•	Scales the features for model training.
•	Constructs and trains a neural network model for genre classification.
•	Evaluates the model's performance, providing accuracy, precision, and recall scores.
