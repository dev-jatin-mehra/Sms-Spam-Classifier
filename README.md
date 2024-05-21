# Spam Mail/SMS Detection using Machine Learning with Streamlit

## Overview

This project implements a spam mail/SMS detection system using Machine Learning techniques and Streamlit for visualization and deployment. The goal is to accurately classify incoming messages as either spam or legitimate (ham).

## Features

- **Data Collection and Preprocessing**: Gathering and cleaning a diverse dataset of emails and SMS messages.
  
- **Model Selection**: Experimenting with various ML algorithms like Naive Bayes, SVM, XGB, DecisionTree, RFC, etc.
  
- **Feature Engineering**: Creating features such as word frequencies and message length.
  
- **Evaluation**: Using metrics like accuracy, precision and confusion_matrix to evaluate model performance.
  
- **Deployment**: Setting up the model for real-time detection using Streamlit.

## Technologies Used

- Python
- Scikit-learn
- Pandas
- NumPy
- Streamlit

## Project Structure

├── data<br>
│ ├── .csv<br>
├── models<br>
│ └── model.pkl/vectorizer.pkl<br>
├── app.py<br>
├── requirements.txt<br>
├── sms_spam.ipynb<br>
└── README.md<br>

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/dev-jatin-mehra/Sms-Spam-Classifier.git
   cd Sms-Spam-Classifier

2. ```bash
    pip install -r requirements.txt

## Usage
- To run the Streamlit app locally 
    ```bash
    streamlit run app.py

## Model Training
- Model was trained using voting classifier . It was also validated by other classifiers such as MultinomialNB,SVC,XGB,DecisionTree

## Contributing
Feel free to fork the repository, create pull requests, and suggest improvements.
