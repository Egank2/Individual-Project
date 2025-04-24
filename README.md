# Market Sentiment Analysis

This repository contains a project that analyzes the relationship between financial news sentiment and stock market performance. The sentiment of over 2 million financial news headlines was classified using **FinBERT**, a transformer model specialized for financial text.

## Goals
- Examine sentiment trends in headlines from 2011 to 2020  
- Compare sentiment patterns in bull vs. bear markets  
- Explore potential for short-term market movement prediction based on sentiment

##  Tools & Technologies
- Python (pandas, NumPy, matplotlib, scikit-learn)  
- [FinBERT](https://github.com/ProsusAI/finbert) for sentiment analysis  
- yfinance for stock market data

## ⚠Limitations
- Only a portion of the full dataset was processed due to GPU limits (Google Colab T4)  
- Sentiment classification used basic bullish/bearish/neutral labels  
- Predictive results were limited and mainly descriptive in nature

## Dataset
- [FNSPID Dataset on Hugging Face](https://huggingface.co/datasets/Zihan1004/FNSPID)

## Author
Developed by **Kenneth Egan**, Computer Science student at Wentworth Institute of Technology.

> For academic and non-commercial use only.
