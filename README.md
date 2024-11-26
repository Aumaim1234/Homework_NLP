# Homework_NLP
# Text Preprocessing and Analysis
# note that I was run in colab and then copy all code into git later
# https://colab.research.google.com/drive/1vEfKf98VWCCGt8CzFmNeduamiJHd_nxA#scrollTo=fXyze3VKWib3

This project processes and analyzes text data using three natural language processing (NLP) frameworks: **NLTK**, **TextBlob**, and **spaCy**. The analysis involves cleaning the text, tokenizing it into sentences and words, and performing a basic frequency analysis to identify the most common words.
---

## Features
- **Cleaned Text**: Removes unnecessary whitespace and formatting issues.
- **Tokenized Sentences and Words**: Extracts sentences and words from the text.
- **Frequency Analysis**: Identifies the top 10 most common words in the text.
- **Framework Comparison**: Measures the performance of NLTK, TextBlob, and spaCy.

---

## Files Generated
1. `cleaned.txt`: The cleaned version of the input text.
2. `words.txt`: Tokenized words for all frameworks.
3. `top10words.txt`: Top 10 most frequent words and their counts for all frameworks.
4. `time_compares.txt`: Runtime comparison of the three frameworks.
5. `sentences_nltk.txt`: Tokenized sentences from NLTK.
6. `nltk_words.txt`: Tokenized words from NLTK.
7.  `sentences_textblob.txt`: Tokenized sentences from textblob.
8.  `words_textblob.txt`: Tokenized words from textblob.
9. `sentences_spacy.txt`: Tokenized sentences from spacy.
10.  `words_spacy.txt`: Tokenized words from spacy.



---

## Requirements
- Python 3.6+
- Libraries: `nltk`, `textblob`, `spacy`, `pandas`, `time`, `collections`
- `en_core_web_sm` model for spaCy

---

Framework Comparison
The performance of the three frameworks is saved in time_compares.txt for analysis. This file contains the runtime of each framework in seconds.

Example Outputs
Tokenized Sentences (NLTK):
txt
Copy code
['Alice was beginning to get very tired...', 'So she was considering in her own mind...']
Top 10 Words:
txt
Copy code
[('Alice', 50), ('the', 30), ('and', 25), ('to', 22), ('she', 20)]
