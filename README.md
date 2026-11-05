# NLP News Analysis

An exploratory Natural Language Processing project focused on analyzing and classifying news articles using Python.

## Overview

This project explores different NLP techniques to analyze news articles labeled as **Fake News** or **Factual News**.

## Techniques & Methods

- **POS Tagging & NER:** Extracting grammatical categories and named entities using spaCy.
- **Text Preprocessing:** Text cleaning, tokenization, stopword removal, and lemmatization.
- **Sentiment Analysis:** Analyzing article sentiment using VADER.
- **Topic Modeling:** Exploring topics using Latent Dirichlet Allocation (LDA) and Latent Semantic Analysis (LSA).
- **Text Classification:** Classifying news articles using Bag-of-Words, Logistic Regression, and SGDClassifier.

## Technologies

Python · Pandas · NLTK · spaCy · Scikit-learn · Gensim · VADER · Matplotlib · Seaborn

## Project Structure

```text
nlp-news-analysis/
├── README.md
├── nlp_project.ipynb
└── fake_news_data.csv
```

## Dataset

The dataset contains 198 news articles with the following fields:

- `title`: Article title
- `text`: Article content
- `date`: Publication date
- `fake_or_factual`: Article classification

## Getting Started

The project was developed using Google Colab.

1. Clone or download this repository.
2. Open `nlp_project.ipynb` in Google Colab.
3. Upload `fake_news_data.csv` to the Colab environment.
4. Run the notebook cells.

## Learning Context & Acknowledgments

This project was completed as part of the **The AI Engineer Course 2026: Complete AI Engineer Bootcamp** by 365 Careers on Udemy.

[View the course on Udemy](https://www.udemy.com/course/the-ai-engineer-course-complete-ai-engineer-bootcamp/)

This repository documents my implementation and exploration of the NLP concepts covered in the course.
