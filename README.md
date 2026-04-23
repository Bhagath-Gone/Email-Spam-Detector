📧 Email Spam Detection using Naïve Bayes
📌 Overview

This project builds a spam detection system using the Multinomial Naïve Bayes algorithm. It classifies SMS messages as Spam or Ham using Natural Language Processing techniques.

🎯 Objectives
Preprocess text data (lowercase, punctuation, stopwords)
Apply TF-IDF vectorization
Implement Naïve Bayes classifier
Manually verify conditional probabilities
Evaluate using Precision, Recall, and F1-score
📊 Dataset
SMS Spam Collection Dataset (UCI Repository)
~5,500 labeled messages (Spam / Ham)
⚙️ Methodology
Load dataset and visualize class distribution
Perform text preprocessing
Compute manual probabilities for key words
Apply CountVectorizer and TF-IDF
Train Multinomial Naïve Bayes model
Evaluate using metrics and confusion matrix
Test on custom messages
📈 Results
Accuracy: ~97%
High Precision & Recall
Improved spam detection using Laplace smoothing
📊 Visualizations
Class distribution (Spam vs Ham)
Top spam words
Confusion matrix
Precision-Recall curve
🧪 Sample Predictions
Message	Prediction
Win money now!	Spam
Hello friend	Ham
🛠️ Technologies Used
Python
Pandas, NumPy
Scikit-learn
Matplotlib
📁 Project Structure
project/
│
├── spam.csv
├── notebook.ipynb
├── report.docx
├── presentation.pptx
└── README.md
👨‍💻 Team Members
Siraparapu Karthik
Pitta Sri Charan
Gone Bhagath
📚 References
UCI Machine Learning Repository
Scikit-learn Documentation
🚀 Conclusion

The model effectively detects spam messages with high accuracy and demonstrates the efficiency of Naïve Bayes for text classification tasks.
