# Text Summarization

## Overview

This repository contains the Text Summarization project developed as part of the B.Tech Final semester Project. The project focuses on extractive text summarization, which involves selecting the most relevant sentences from the original text to create a summary. The summarization process includes data preprocessing, context classification using various machine learning models, and summarization using advanced NLP algorithms.

## Methodology

### Data Preprocessing
- Removal of unnecessary characters, stopwords, and noise from the text.

### Context Classification
The preprocessed data was classified based on its context using the following machine learning models:
- **Naive Bayes**: A probabilistic classifier based on Bayes' theorem with strong independence assumptions.
- **Random Forest**: An ensemble method using multiple decision trees to improve classification accuracy.
- **XGBoost**: An optimized gradient boosting machine learning algorithm for better performance and speed.

### Text Summarization
The classified data was summarized using the following algorithms:
- **TextRank**: A graph-based ranking algorithm for extracting key sentences based on their importance.
- **LexRank**: A graph-based algorithm using cosine similarity and centrality measures to select the most significant sentences.

## Tech Stack

- **Python**: Programming language used for implementation.
- **NLTK**: Natural Language Toolkit for text processing.
- **scikit-learn**: Machine learning library for context classification.
- **XGBoost**: Optimized gradient boosting library for classification.

## Usage
- Clone the repository:
```
git clone https://github.com/vjkanna2/Text_Summarization.git
cd Text_Summarization
```
- Install the required packages (mentioned in the Requirements.txt file):
```
pip install -r requirements.txt
```

- Run the main script:
```
python main.py
```
- View the summarized text as output that will be displayed in the console.

## Acknowledgements
This project was developed as part of the B.Tech Final semester. Thanks to the professors and mentors who provided guidance and support throughout the development process.

