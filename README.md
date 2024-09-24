# Stock Trend Prediction Using Sentiment Analysis

Predict Google (GOOGL) stock movements by analyzing Twitter sentiment.

## Overview

- **Data Collection**: Gather tweets mentioning GOOGL and historical stock data.
- **Sentiment Analysis**: Use VADER to compute sentiment scores for each tweet.
- **Data Merging**: Merge average daily sentiment scores with stock data.
- **Prediction**: Compare sentiment direction with actual stock movement.
- **Result**: Achieved a prediction accuracy of **51%**.

## Requirements

- Python 3.x
- PySpark
- TensorFlow
- vaderSentiment

## Usage

1. **Install Required Packages**:
   ```bash
   pip install tensorflow vaderSentiment
