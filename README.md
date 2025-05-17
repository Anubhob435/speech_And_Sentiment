i# Speech and Sentiment Analysis Project

## Overview
This project demonstrates various Natural Language Processing (NLP) techniques using Python libraries like NLTK, SpaCy, and Transformers. It includes functionalities for speech-to-text conversion, text preprocessing, exploratory text analysis, sentiment analysis, topic modeling, and text classification.

## Features
- Speech-to-text conversion using SpeechRecognition
- Text preprocessing and tokenization
- Text statistics and visualization
- Sentiment analysis using multiple approaches (NLTK VADER, TextBlob, Transformers)
- Topic modeling with Latent Dirichlet Allocation (LDA)
- Text classification using machine learning

## Dependencies
- Python 3.8+
- See requirements.txt for complete list of packages

## Setup
1. Clone this repository
2. Install dependencies: `pip install -r requirements.txt`
3. Download necessary NLTK data:
   ```python
   import nltk
   nltk.download('punkt')
   nltk.download('stopwords')
   nltk.download('wordnet')
   nltk.download('vader_lexicon')
   ```
4. Run the Jupyter notebook: `speech_and_sentiment.ipynb`

## Usage
The project is organized in a Jupyter notebook that guides you through each step of the NLP pipeline with detailed explanations and visualizations.

## Contribution
Open to all contributions 🤗

Anubhob Dey