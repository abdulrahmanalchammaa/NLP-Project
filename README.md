# NLP Project — Turkish Sentiment Analysis

A Jupyter/Colab notebook that classifies the sentiment (positive/negative) of Turkish e-commerce product reviews using a pretrained BERT model.

## Approach

- Model: [`savasy/bert-base-turkish-sentiment-cased`](https://huggingface.co/savasy/bert-base-turkish-sentiment-cased) via Hugging Face `transformers`
- Dataset: Turkish product review comments (Hepsiburada)
- Pipeline: Hugging Face `sentiment-analysis` pipeline for inference over the review text

## Running

Open `NLP-Project.ipynb` in Google Colab (it mounts Google Drive for the dataset) or Jupyter, and run the cells top to bottom. Requires:

```bash
pip install transformers pandas numpy
```

> The notebook is packaged as `NLP-Project.rar` in this repo.
