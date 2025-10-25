# NLP for Disaster Tweets

> **Classifying disaster-related tweets using Natural Language Processing and Machine Learning**

## Overview

This project uses NLP techniques to automatically identify real disaster tweets from social media noise. It demonstrates practical machine learning applications for emergency response systems.

## Problem Statement

During disasters, social media becomes flooded with information. Not all tweets with disaster-related keywords indicate actual emergencies. This project aims to distinguish real disaster tweets from casual mentions, helping emergency responders focus on genuine crises.

## Approach

**Data Processing:**
- Cleaned 10,876 tweets (removing URLs, special characters, stop words)
- Applied stemming, lemmatization, and tokenization
- Used TF-IDF for feature extraction

**Models Evaluated:**
- K-Nearest Neighbors
- Logistic Regression (Best performer)
- K-Means Clustering

## Results

**Best Model: Logistic Regression**
- **Accuracy:** 84.38%
- **Precision:** 83.65%
- **Recall:** 76.32%
- **F1 Score:** 83.54%

The model successfully balances precision (avoiding false alarms) and recall (catching real disasters), making it practical for emergency response applications.


## Key Files

- `TF-IDF_method.ipynb` - Main analysis notebook
- `reports/` - Final report and presentation

## Installation

```bash
pip install -r requirements.txt
```

## What I Learned

- Text preprocessing and feature engineering for NLP tasks
- Handling imbalanced datasets in binary classification
- Model evaluation beyond accuracy (precision/recall trade-offs)
- Applying ML to real-world emergency response scenarios

---

**Authors:** Ting-An Andy Wang, Jie Huang  
**Course:** Principles of Data Science
