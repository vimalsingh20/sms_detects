# SMS Spam Detection

A Machine Learning project that detects whether an SMS message is **Spam** or **Not Spam (Ham)**.

The project uses text preprocessing and feature extraction to convert SMS messages into numerical features and then uses a Machine Learning model to classify the messages.

## Project Overview

The main goal of this project is to build a simple text classification model that can identify unwanted or spam SMS messages.

The project is implemented in a Jupyter Notebook and includes data exploration, text preprocessing, feature extraction, model training, and prediction.

## Features

- SMS text classification
- Data preprocessing
- Text feature extraction using CountVectorizer
- Machine Learning model training
- Spam and Ham classification
- Saved trained model
- Saved CountVectorizer for transforming new messages

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook

## Dataset

The project uses an SMS spam dataset containing messages labelled as:

- `spam` — unwanted or spam message
- `ham` — normal message

The dataset is stored in:

```text
spam.csv

## Model Structure  

sms_detects/
│
├── spam.csv
├── sms_spam.ipynb
├── CountVectorizer.pkl
├── model.pkl
├── .gitignore
└── README.md