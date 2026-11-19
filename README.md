# Financial-Sentiment-Analysis
Financial sentiment classification using FinBERT and Financial PhraseBank dataset.
# Financial Sentiment Analysis using FinBERT

## Project Overview
This project performs financial sentiment analysis
using the FinBERT pretrained language model.

It classifies financial sentences into three categories:
- Positive
- Negative
- Neutral

## Dataset
Financial PhraseBank

Configuration: sentences_50agree

Dataset:
https://huggingface.co/datasets/atrost/financial_phrasebank

## Algorithm
FinBERT

Model:
ProsusAI/finbert

## Technologies Used
- Python
- Google Colab
- PyTorch
- Hugging Face Transformers
- Financial PhraseBank
- Pandas
- Scikit-learn

## Project Workflow
1. Load Financial PhraseBank
2. Inspect dataset
3. Preprocess financial text
4. Split training and testing data
5. FinBERT tokenization
6. Load pretrained FinBERT
7. Fine-tune FinBERT
8. Evaluate the model
9. Predict financial sentiment
10. Save the trained model

## Evaluation
The model is evaluated using:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

## Prediction Example

Input:
The company's profits increased significantly.

Output:
Positive

## Model
ProsusAI/finbert

## Environment
Google Colab with GPU support.

## Author
Machine Learning Project Portfolio
