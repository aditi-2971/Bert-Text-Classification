# BERT Complaint Classification

This project is a text classification model using BERT to classify complaints into different departments.

## Features

- Uses BERT (bert-base-uncased) from Hugging Face Transformers
- Tokenization, encoding, and classification pipeline
- Predict department from new complaint text
- Trained on a labeled dataset (`ProjectData.csv`)

## Files

- `BertClassification.ipynb`: Main notebook for training and inference
- `trained_model/`: Saved fine-tuned model and tokenizer
- `ProjectData.csv`: Dataset file
- `requirements.txt`: All required libraries

## How to Use

1. Clone the repo or download the files
2. Open the notebook in Colab or Jupyter
3. Run the cells in order
4. Use `predict_department()` to test new inputs
