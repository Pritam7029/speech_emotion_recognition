# Speech Emotion Recognition

This repository contains the implementation of a Speech Emotion Recognition (SER) system using Python. The project leverages deep learning techniques to detect and classify emotions from speech audio files.

## Project Overview

Speech Emotion Recognition (SER) is a challenging task where the goal is to accurately classify emotions from speech signals. This project uses multiple datasets, audio processing techniques, and a convolutional neural network (CNN) model to achieve this task.

## Features

- **Multiple Datasets**: Utilizes various publicly available datasets for training and evaluation, including RAVDESS, CREMA-D, TESS, and SAVEE.
- **Audio Processing**: Employs Librosa to extract key audio features like Mel Frequency Cepstral Coefficients (MFCCs), chroma, and Mel spectrograms.
- **Deep Learning Model**: Implements a Convolutional Neural Network (CNN) using Keras, designed for the classification of emotions in speech.
- **Model Training**: Includes advanced training techniques with callbacks such as `ModelCheckpoint` and `ReduceLROnPlateau` to optimize model performance.
- **Performance Evaluation**: Provides a detailed evaluation using confusion matrices and classification reports to assess model accuracy.

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/speech-emotion-recognition.git
   cd speech-emotion-recognition
   ```

2. **Install dependencies:**

   Ensure you have Python 3.7+ and use pip to install the required packages:

   ```bash
   pip install -r requirements.txt
   ```

3. **Download the datasets:**

   Download the RAVDESS, CREMA-D, TESS, and SAVEE datasets, and place them in the appropriate directories as specified in the code.

## Usage

1. **Data Preprocessing:**

   The code processes the raw audio files, extracts features such as MFCCs, chroma, and Mel spectrograms, and labels them according to their emotions.

2. **Model Training:**

   Train the model using the preprocessed data:

   ```bash
   python train.py
   ```

   This will initiate training, with the best model saved automatically.

3. **Model Evaluation:**

   Evaluate the trained model's performance on the test set and visualize the results:

   ```bash
   python evaluate.py
   ```

## Results

- **Model Accuracy**: The trained CNN model achieves a high accuracy in classifying emotions from speech.
- **Confusion Matrix**: Visualizes the performance across different emotion classes.
- **Loss & Accuracy Curves**: Provides insights into the training process.

## Contribution
This is a group project made with the contribution of Mandir das and Pritam Chakraborty


