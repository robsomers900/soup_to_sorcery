# Jupyter Notebook Project: Text Classification

This GitHub repository contains a Jupyter Notebook project focused on text classification for books, movies, and music data scraped using BeautifulSoup. The main components of the project are as follows:

## Data Scraping and Analysis
- HTML data was scraped using BeautifulSoup to obtain information on books, movies, and music.
- The structure of the HTML data was analyzed to gain clarity.

## Functionality
- The project introduces a function called `scrape_page` that extracts relevant data and returns it as a list of dictionaries, each representing an article with keys: title, category, and snippet.

## Binary Text Classification
- Binary classification is performed on the Books and Films category pairing.
- The process is generalized by creating functions for efficient classification on multiple category pairs.
- Tokenization and custom stop words are used to improve accuracy.
- A KNN model is built and evaluated with precision, recall, F1 scores, and a confusion matrix.

## Multi-Class Text Classification
- Term frequency analysis is conducted.
- A KNN model is trained and evaluated for multi-class text classification.
- The confusion matrix outlines the model's performance on each class.

## Data Summary
- The dataset consists of articles from Film, Music, and Books categories.
- The Document-Term Matrix has 38 distinct terms for the binary classification and 35 terms for multi-class classification.

The project showcases text classification techniques and the ability to efficiently analyze and evaluate models across different categories. Feel free to explore the Jupyter Notebook and experiment with the code to further enhance the text classification process.
