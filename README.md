# Kenya Airways Custommer Feedback Analysis

This repository contains a Jupyter Notebook (`Kenya Airways Reviews.ipynb`) that performs sentiment analysis and emotions analysis on reviews of Kenya Airways. The data used for analysis is scraped from Airline Quality.

## Notebook Content

### Data Cleaning and Preprocessing
- The notebook begins with importing the necessary libraries and the dataset.
- Text preprocessing functions are defined to clean the text data, including removing useless text, converting text to lowercase, removing punctuation, tokenization, and handling stop words.

### Emotion Analysis
- Emotion dictionary function is created to map emotions from a file into a dictionary.
- Sentiment analysis using Vader Sentiment Analyzer is implemented.

### Plot Findings
- Visualizations are created to summarize the sentiment distribution, frequent emotions, frequent categories, and aspect-based sentiment analysis.
- The visualizations include pie charts, bar plots, and word clouds to represent the findings effectively.

### Aspect-based Sentiment Analysis using BERT
- Pre-trained BERT model is utilized for aspect-based sentiment analysis.
- Aspects like flight, service, seat, food, and crew are extracted from the text, and sentiment analysis is performed for each aspect.

## Usage
- Ensure you have the necessary dependencies installed as specified in the notebook.
- Run each cell sequentially to execute the analysis.
- The notebook provides detailed comments and explanations for better understanding.

## Libraries Used
- pandas
- NLTK
- Matplotlib
- WordCloud
- transformers
- spacy

## Note
- Some parts of the notebook require downloading NLTK data and emotion dictionary files.
- The notebook provides comprehensive analysis and visualization of Kenya Airways reviews, aiding in understanding customer sentiments and emotions associated with different aspects of the airline service.
