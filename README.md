## Overview  
This project implements **Sentiment Analysis** on restaurant reviews using **Natural Language Processing (NLP)** and **Machine Learning**. The model predicts whether a review is positive or negative based on text preprocessing and a **Naïve Bayes classifier**.  

## Dataset  
- The dataset consists of restaurant reviews stored in `.tsv` (Tab-Separated Values) format.  
- The model is trained on `Dataset.tsv`.  
- Predictions are made on `Data_topredict.tsv`.  

## Features  
- **Text Preprocessing:**  
  - Removing special characters  
  - Converting text to lowercase  
  - Removing stopwords (except "not")  
  - Stemming words  
- **Feature Extraction:**  
  - Bag-of-Words (BoW) representation  
  - CountVectorizer for text transformation  
- **Machine Learning Model:**  
  - **Naïve Bayes Classifier** trained on preprocessed reviews  
  - Accuracy evaluation using a confusion matrix  
- **Prediction Pipeline:**  
  - Uses a pre-trained BoW model  
  - Predicts sentiment labels for new reviews  

