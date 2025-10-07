📧 Spam Email/SMS Prediction using Machine Learning

This project builds a Machine Learning model to classify messages as Spam or Not Spam (Ham). The model analyzes the content of emails/SMS messages and predicts whether they are legitimate or potentially harmful. This kind of system is widely used in email filtering, messaging platforms, and cybersecurity applications.

📌 Project Overview

The project implements a full ML pipeline:

Data Collection – Used a publicly available dataset of SMS/Email messages labeled as spam or ham.

Data Preprocessing –

Text cleaning (removing special characters, numbers, punctuation).

Tokenization and stop-word removal.

Feature extraction using Bag of Words (BoW), TF-IDF, and Word Embeddings.

Model Training – Trained multiple classifiers:

Logistic Regression


Model Evaluation – Compared performance using Accuracy, Precision, Recall, F1-Score, and Confusion Matrix.


🚀 Tech Stack

Programming Language: Python

Libraries: Pandas, NumPy, Scikit-learn, NLTK, Matplotlib, Seaborn

Version Control: Git & GitHub

📊 Results

Achieved high accuracy (>95%) with Logistic Regression .

Successfully identified spam messages with strong precision-recall tradeoff.

📂 Repository Structure

├── data/                # Dataset (or link to dataset)

├── notebooks/           # Jupyter notebooks for EDA & model building

├── requirements.txt     # Project dependencies

├── README.md            # Project documentation