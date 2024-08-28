# Topic-Modeling-and-Semantic-Classification-on-Queries

## Overview
This project involves web scraping data from answers.com and reddit.com, followed by topic modeling and semantic analysis. We use Latent Dirichlet Allocation (LDA) and k-means clustering algorithms to analyze and categorize the textual data. The primary goals of this project are to extract meaningful patterns and insights from the scraped data and to identify distinct topics and clusters.

## Contents
Data Collection: Scripts for scraping data from answers.com and reddit.com
Data Processing: Scripts for cleaning and preparing data for analysis
Topic Modeling: Implementation of LDA for topic discovery
Semantic Analysis: Implementation of k-means clustering for semantic grouping
Results: Summary of findings and analysis

## Requirements
To run this project, you need to have Python and the following libraries installed:
requests – For making HTTP requests to web pages
BeautifulSoup – For parsing HTML and extracting data
pandas – For data manipulation and analysis
numpy – For numerical operations
scikit-learn – For machine learning and data mining
gensim – For topic modeling with LDA
matplotlib – For plotting and visualizing results
nltk – For natural language processing tasks

### Data Collection
Data retrieval(web Scraping) for topic modeling.ipynb for webscraping the data.

### Data Processing
Data is cleaned and prepared for analysis in the data_processing.py script. This includes:

Removing HTML tags and special characters
Tokenizing and lemmatizing text
Removing stop words
Creating term-document matrices

### Topic Modeling
The topic_modeling.py script implements LDA (Latent Dirichlet Allocation) to identify topics within the data. It includes:
Building the LDA model
Training the model on the prepared data
Analyzing and visualizing the identified topics

### Semantic Analysis
The semantic_analysis.py script performs k-means clustering to group similar documents based on their semantic content. It includes:
Preprocessing text data for clustering
Applying k-means clustering algorithm
Evaluating and visualizing clustering results

## Results
The results of the topic modeling and semantic analysis are summarized, which includes:
Identified topics with keywords
Clusters of semantically similar documents
Visualizations of topics and clusters


