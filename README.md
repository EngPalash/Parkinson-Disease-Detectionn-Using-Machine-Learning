# Parkinson-Disease-Detectionn-Using-Machine-Learning

Overview

This project aims to develop a machine learning model to detect Parkinson's disease based on voice and speech patterns. Early detection can lead to better management and treatment options.

Table of Contents:

Introduction
Dataset
Installation
Usage
Model
Results
Contributing
License
Introduction
Parkinson's disease affects movement and speech. By analyzing voice recordings, we can identify features that may indicate the presence of the disease. This project uses machine learning to classify whether an individual has Parkinson's disease or not.

Dataset
The dataset used in this project includes voice recordings from individuals with and without Parkinson's disease. You can find the dataset here.
https://www.kaggle.com/datasets/debasisdotcom/parkinson-disease-detection

Features
Voice recordings: Various audio features such as pitch, frequency, and tone.
Labels: Indicate whether the individual has Parkinson's disease (1) or not (0).
Installation
To set up the project, follow these steps:

Clone the repository:

bash
Copy code
git clone https://github.com/EngPalash/parkinson-disease-detection.git
cd parkinson-disease-detection
Install the required packages:

bash
Copy code
pip install -r requirements.txt
Usage
To train the model, run the following command:

bash
Copy code
python train.py
To make predictions, use:

bash
Copy code
python predict.py --input <path_to_audio_file>
Model
This project uses a machine learning model (e.g., Random Forest, SVM, or Neural Network) to classify the audio features. The model is trained on the dataset and can predict the likelihood of Parkinson's disease based on new voice recordings.

Results
After training, the model achieves an accuracy of over 89% on the test set. You can view detailed metrics such as precision, recall, and F1-score in the results section of the report.
