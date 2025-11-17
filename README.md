# Sports News Sentiment Analysis

This project analyzes public sentiment in sports news headlines, focusing on football and cricket. The goal is to understand whether headlines related to these sports tend to carry positive or negative emotions.

## Project Overview

In this project, we manually created a small dataset of football and cricket headlines. The sentiment of each headline was analyzed using the VADER Sentiment Analyzer, a tool from the Natural Language Toolkit (NLTK). 

The sentiment scores were then compared between football and cricket, with the aim of visualizing which sport tends to generate more positive sentiment overall. A bar chart is used to display the comparison between the average sentiment of football and cricket headlines.

## Key Features
- Manual dataset creation for football and cricket headlines.
- Use of VADER Sentiment Analyzer (from NLTK) to calculate sentiment scores.
- Comparison of average sentiment scores between football and cricket headlines.
- Visual representation using a bar chart to showcase sentiment trends.

## Technologies Used
- Python 3.x
- NLTK (Natural Language Toolkit) for sentiment analysis
- Matplotlib for data visualization

## Requirements

To run this project, you will need to install the following Python libraries:

- `nltk`
- `matplotlib`
- `pandas` (if applicable for any data handling)

You can install them using `pip`:

```bash
pip install nltk matplotlib pandas
