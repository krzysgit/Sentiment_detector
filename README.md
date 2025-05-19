[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/krzysgit/Sentiment_detector/blob/main/Sentiment.ipynb)

# Sentiment Detector — BERT for Tweet Classification

This project fine-tunes a DistilBERT model to classify tweets into three sentiment categories: **positive**, **neutral**, and **negative**.

The model is trained using the [TweetEval dataset](https://huggingface.co/datasets/tweet_eval) and published on the Hugging Face Hub.

---

## Model Summary

-   **Architecture**: DistilBERT (with classification head)
-   **Task**: Sentiment classification
-   **Labels**: `0 = negative`, `1 = neutral`, `2 = positive`
-   **Trained using**: Hugging Face Transformers + Datasets + Accelerate

Model is hosted at:  
👉 [krzyskrzyskrzys/sentiment-detector on Hugging Face](https://huggingface.co/krzyskrzyskrzys/sentiment-detector)

---

## Installation

Before running the notebook, make sure you have the required libraries:

```bash
pip install transformers datasets scikit-learn accelerate
```
