# Emoji Sentiment Dataset

A dataset containing emojis, their textual descriptions, and sentiment scores. Useful for sentiment analysis, Natural Language Processing (NLP), AI chatbots, and emotion-based filtering.

## 📂 Dataset Contents

- **description**: Textual description of the emoji (e.g., "grinning face").
- **score**: Sentiment score (ranges from 0 to 1, where higher values indicate a more positive sentiment).
- **emoji**: The actual emoji character.
- **Additional Columns**: Empty or unused fields that can be ignored.

## 📥 Download the Dataset

- **CSV Format**: [dataset.csv](./dataset.csv)
- **Excel Format**: [dataset.xlsx](./dataset.xlsx) *(if included in the repo)*

## 🔍 Usage Example

You can load this dataset in Python using Pandas:

# Python
import pandas as pd

# Load dataset
df = pd.read_csv("dataset.csv")

# Display first few rows
print(df.head())

## 📊 Applications

- **Sentiment Analysis: Assign sentiment scores to text messages.
- **Chatbot Development: Improve emoji-based responses.
- **NLP Research: Analyze emoji usage in social media.
  
## 📡 Also Available on Kaggle
- **Find this dataset on Kaggle: [[Kaggle Dataset Link](https://www.kaggle.com/datasets/dhruvhada/emoji-sentiments-and-description)] 
