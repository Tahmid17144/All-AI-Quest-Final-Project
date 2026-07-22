Project Overview
This project performs Sentiment Analysis on Amazon product reviews using Natural Language Processing (NLP) and Machine Learning techniques. The objective is to classify customer reviews into sentiment categories based on the textual content.
The project includes complete data preprocessing, feature extraction using TF-IDF, class balancing with SMOTE, and comparison of multiple machine learning algorithms.

Features
- Data Cleaning
- Text Preprocessing
- Stopword Removal
- Tokenization
- Lemmatization
- TF-IDF Feature Extraction
- Class Balancing using SMOTE
- Model Training
- Model Evaluation
- Confusion Matrix
- Classification Report
- Accuracy Comparison

Dataset Source:
  https://raw.githubusercontent.com/rashakil-ds/Public-Datasets/refs/heads/main/amazon.csv
  The dataset contains Amazon product reviews used for sentiment classification.

Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- NLTK
- WordCloud
- Imbalanced-learn (SMOTE)

Machine Learning Models
The following models were trained and evaluated:

- Random Forest Classifier
- Support Vector Machine (SVM)
- Logistic Regression

NLP Pipeline
   Load Dataset
   Remove Missing Values
   Remove URLs
   Convert Text to Lowercase
   Remove Punctuation
   Remove Stopwords
   Tokenization
   Lemmatization
   TF-IDF Vectorization
   Train-Test Split
   SMOTE for Class Balancing
   Model Training
   Performance Evaluation

Evaluation Metrics
The models are evaluated using:

 - Accuracy
 - Precision
 - Recall
 - F1-Score
 - Confusion Matrix
 - Classification Report

Data Visualization
The project includes:

 - Word Cloud
 - Sentiment Distribution
 - Confusion Matrix
 - Performance Analysis
