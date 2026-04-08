# financial-sentiment-nlp
Twitter Financial News Sentiment Classification using DistilBERT

# Twitter Financial News Sentiment Classifier

Fine-tuned DistilBERT on the Twitter Financial News Sentiment dataset
to classify tweets as **Bullish**, **Bearish**, or **Neutral**.

## Results
| Metric   | Score  |
|----------|--------|
| Accuracy | 88.2%  | 
| F1 Score | 0.88   | 

## Tech Stack
- Python
- HuggingFace Transformers
- DistilBERT
- PyTorch
- Kaggle GPU (T4)

## Dataset
[zeroshot/twitter-financial-news-sentiment](https://huggingface.co/datasets/zeroshot/twitter-financial-news-sentiment)

## How to Run
1. Open the notebook in Kaggle or Jupyter
2. Enable GPU accelerator
3. Run all cells — training takes ~10 minutes on GPU

## Project Structure
financial-sentiment-nlp/
├── financial_sentiment.ipynb   # main notebook
└── README.md
