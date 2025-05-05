# Fake News Detection System

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.0.2-orange)
![License](https://img.shields.io/badge/License-MIT-green)

A machine learning-based system to automatically classify news articles as "Real" or "Fake" using text analysis and ensemble learning techniques.

## Table of Contents
- [Features](#features)
- [Installation](#installation)
- [Dataset](#dataset)


## Features
- Text preprocessing pipeline (URL/HTML removal, lowercasing, punctuation removal)
- TF-IDF vectorization for feature extraction
- Multiple classifier comparison (Logistic Regression, Decision Trees, Random Forest, Gradient Boosting)
- Manual testing interface for real-time predictions
- Achieves 99.59% accuracy with Gradient Boosting

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/fake-news-detection.git
cd fake-news-detection
