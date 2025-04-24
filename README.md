

# Fake News Detection using DistilBERT and Passive Aggressive Classifier

# Overview
This repository contains code for a fake news detection system using DistilBERT and Passive Aggressive Classifier. The system is built using Python and utilizes various libraries such as pandas, numpy, scikit-learn, NLTK, Flask, and PyTorch.

# Requirements
- Python 3.x
- pandas
- numpy
- scikit-learn
- NLTK
- Flask
- PyTorch
- Transformers
- Flask-Ngrok
- PyNgrok

# Installation
To install the required libraries, run the following command:


bash
pip install -r requirements.txt


Alternatively, you can install the libraries individually using the following commands:


bash
!pip install pandas numpy scikit-learn nltk flask-ngrok torch transformers flask-cors pyngrok


# Dataset
The dataset used for this project consists of two CSV files: Fake.csv and True.csv. These files contain labeled news articles, with Fake.csv containing fake news articles and True.csv containing true news articles.

# Model
The system uses two models:

1. DistilBERT: A pre-trained language model that is fine-tuned for fake news detection.
2. Passive Aggressive Classifier: A linear classifier that is trained on TF-IDF features extracted from the news articles.

# Usage
To run the system, execute the following command:


bash
python app.py


This will start the Flask server, and you can access the system using the provided ngrok URL.

# API Endpoints
The system provides the following API endpoints:

- /predict: Accepts a news article as input and returns a prediction (fake or true).

# Contributing
Contributions are welcome! If you'd like to contribute to this project, please fork the repository and submit a pull request.

