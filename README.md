# Natural Language Processing Labs (ARTI452)

## Overview
This repository contains a collection of laboratory assignments for the **ARTI452 - Natural Language Processing** course. The labs focus on bridging the gap between theoretical NLP concepts and practical implementation using Python.

## Technologies & Libraries Used
* **Programming Language:** Python 3
* **Core Libraries:** 
  * `NLTK`: For comprehensive text preprocessing, tokenization, stemming, lemmatization, and n-gram modeling.
  * `spaCy`: For advanced object-oriented text processing, tokenization, and handling stop words.
  * `re` (Regular Expressions): For pattern matching, data extraction, and text manipulation.
  * `Pandas`: For data manipulation and handling structured datasets (e.g., CSV files).
  * `emoji`: For handling and cleaning emojis from text data.

## Repository Structure

### [Lab 2: Text Pre-processing and Regular Expressions](NLP-Labs/Lab2/)
* **Regular Expressions (Regex):** Utilizing `re.compile()`, `re.split()`, `re.sub()`, `re.search()`, and `re.match()` for pattern matching and text substitution.
* **Text Preprocessing Pipeline:** Implementing essential steps to clean raw data, including tokenization, lower casing, and handling special characters.
* **Stemming & Lemmatization:** Applying `PorterStemmer`, `SnowballStemmer`, and `WordNetLemmatizer` to reduce words to their base or dictionary forms.
* **Stop Words Management:** Removing non-informative words using both NLTK and spaCy, and customizing the stop words list.

### [Lab 3: N-Grams Language Modeling](NLP-Labs/Lab3/)
* **Probabilistic Modeling:** Building a Maximum Likelihood Estimation (MLE) language model.
* **N-Grams:** Extracting and analyzing sequences using Unigrams, Bigrams, and Trigrams.
* **Sequence Padding:** Applying start (`<s>`) and end (`</s>`) symbols to normalize sentence lengths for neural networks.
* **Model Evaluation:** Generating text predictions based on Bigram probabilities and evaluating the model's performance using Perplexity.

*(More labs will be added as the course progresses...)*


**Maria Mohammed Al-Sadiq   7FA1**
