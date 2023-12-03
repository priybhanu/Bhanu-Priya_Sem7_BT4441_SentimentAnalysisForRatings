# Bhanu-Priya_Sem7_BT4441_SentimentAnalysisForRatings
This is an academic project for B.Tech semester 7 project work.
Sure, a README file is a great way to introduce users to your repository! Here's a template you can use:

---

# Sentiment Analysis Tool

This repository contains a Python-based sentiment analysis tool using Flask and NLTK's VADER sentiment analyzer, as well as a comparison with a pre-trained RoBERTa model for sentiment analysis.

## Usage

### Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/sentiment-analysis-tool.git
   cd sentiment-analysis-tool
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### Running the Application

Run the Flask app:
```bash
python app.py
```

Access the application in your web browser at `http://localhost:5000`.

## Overview

### Files

- `app.py`: Contains the Flask application for sentiment analysis.
- `model_code.py`: Demonstrates sentiment analysis using NLTK's VADER and a pre-trained RoBERTa model.

### Features

- **VADER Sentiment Analysis**: Utilizes NLTK's `SentimentIntensityAnalyzer` to provide sentiment scores for text input.
- **RoBERTa Pretrained Model**: Demonstrates sentiment analysis using a pre-trained transformer model.
- **Visualization**: Includes visualizations for sentiment scores based on both VADER and the RoBERTa model.

### How It Works

1. **VADER Sentiment Analysis**: Analyzes sentiment using a lexicon and rules-based approach.
2. **RoBERTa Pretrained Model**: Employs a transformer-based model to understand text context and derive sentiment.

## Additional Notes

- The repository includes additional functionalities like using the Transformers pipeline for quick sentiment predictions.
- Explore the `model_code.py` file for an in-depth analysis and comparison between VADER and RoBERTa.

Feel free to contribute, open issues, or suggest improvements!

---

Feel free to adjust and expand on the sections based on your preferences or any additional information you'd like to include.
