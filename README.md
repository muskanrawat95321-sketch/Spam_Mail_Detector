📧 Spam Mail Detector
📌 Project Overview

This project was completed as part of an Artificial Intelligence & Machine Learning Internship.

The objective of this project is to build a machine learning model that classifies SMS messages as Spam or Safe (Non-Spam) using Natural Language Processing (NLP) techniques.

🎯 Objective

Develop a classification model that automatically identifies whether an SMS message is Spam or Safe, helping users filter unwanted messages.

📂 Dataset
Dataset: SMS Spam Collection Dataset
Source: UCI Machine Learning Repository / Kaggle
Total Messages: 5,572
Classes:
Safe (Ham)
Spam
🛠️ Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Google Colab
📚 Libraries Used
pandas
numpy
matplotlib
seaborn
scikit-learn
🔄 Project Workflow
Import required libraries
Load the SMS Spam dataset
Explore and understand the data
Clean the dataset
Visualize class distribution
Calculate message lengths
Convert text into numerical features using TF-IDF
Split the data into training and testing sets
Train a Logistic Regression model
Evaluate the model
Predict custom SMS messages
📊 Data Visualization

The project includes:

Safe vs Spam Count Plot
Message Length Distribution
Confusion Matrix Heatmap
🤖 Machine Learning Model

Algorithm Used

Logistic Regression
🧠 NLP Technique

Feature Extraction

TF-IDF (Term Frequency–Inverse Document Frequency)
📏 Evaluation Metrics
Accuracy Score
Precision
Recall
F1-Score
Confusion Matrix
📈 Results
Successfully classified SMS messages into Spam and Safe categories.
Achieved high accuracy (around 97–99%) on the test dataset.
Demonstrated the effectiveness of TF-IDF with Logistic Regression for spam detection.
📁 Project Structure
Spam-Mail-Detector/
│── Spam_Mail_Detector.ipynb
│── spam.csv
│── README.md
│── requirements.txt
│── images/
│   ├── count_plot.png
│   ├── message_length_distribution.png
│   └── confusion_matrix.png
Future Improvements
Compare multiple algorithms (Naive Bayes, SVM, Random Forest)
Add text preprocessing using stemming and lemmatization
Build a Streamlit web application
Deploy the model online
Add real-time email or SMS classification
👩‍💻 Author

Muskan Rawat

B.Tech – Computer Science & Engineering (Data Science & Artificial Intelligence)




