# Simple Text Summarizer

## Overview
This project provides a simple text summarizer that scrapes web pages, processes the text using various NLP techniques, and returns a concise summary. The summarizer leverages powerful libraries including NLTK, BERT Extractive Summarizer, and Transformers to analyze and summarize content effectively.

## Features
- **Web Scraping**: Extracts complete textual data from web pages in JSON format.
- **NLP Processing**: Utilizes NLTK for natural language processing tasks like lemmatization to refine the text for summarization.
- **Summarization**: Employs the BERT Extractive Summarizer and Transformers to generate summaries that are less than 200 words.

## Feature-based Summarisation
The feature-based model evaluates sentence importance based on several textual features:
- **Location**: Position of the sentence within the document.
- **Sentence Length**: The length of sentences contributes to their significance.
- **Term Frequency**: How often terms appear within the text.
- **Proper Nouns**: Identification and emphasis on proper nouns.
- **Formatting and Styles**: Influence of specific formatting and styles used within the text.

## How to Use
To use this summarizer, ensure you have the necessary Python packages installed:
```bash
pip install nltk bert-extractive-summarizer transformers
