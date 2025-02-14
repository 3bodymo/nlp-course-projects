# Onion Article Classification

This project implements a text classification system to distinguish between real news articles and satirical articles from The Onion using various machine learning approaches.

## Overview

The system uses Natural Language Processing (NLP) techniques and different machine learning classifiers to determine whether a given news article headline is from The Onion (satirical) or a genuine news source.

## Features

- Text preprocessing including punctuation removal and stopword filtering
- Data balancing using RandomOverSampler
- Implementation of multiple classifiers:
  - Naive Bayes
  - Support Vector Machine (SVM)
  - Logistic Regression
- Model evaluation with accuracy metrics and confusion matrices

## Dataset

The dataset used in this project is from Kaggle:
[Onion or Not - News Headlines Dataset](https://www.kaggle.com/datasets/chrisfilo/onion-or-not)

## Requirements

To install all required packages, run:

```bash
pip install -r requirements.txt
```
