# ai_finance
Financial News Sentiment Analysis using FinBERT

This project performs financial news sentiment analysis using the pretrained FinBERT transformer model from Hugging Face. The model classifies financial headlines into:

Positive
Neutral
Negative

The notebook includes:

Data preprocessing & cleaning
Exploratory Data Analysis (EDA)
FinBERT tokenization & fine-tuning
Model training and evaluation
Confusion matrix & performance metrics
Custom sentiment predictions
Saving the trained model
Tech Stack
Python
Pandas
Scikit-learn
PyTorch
Hugging Face Transformers
Matplotlib & Seaborn
Dataset

Dataset file:

all-data.csv

Required columns:

Column	Description
text	Financial news text
label	Sentiment label
Installation
pip install pandas numpy scikit-learn torch transformers datasets matplotlib seaborn
Run the Notebook
jupyter notebook finbert_sentiment.ipynb
Applications
Stock market analysis
Financial news monitoring
Investment research
Trading sentiment analysis
