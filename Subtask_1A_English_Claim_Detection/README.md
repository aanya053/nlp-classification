# English Claim Detection using BERT

## Objective
This task focuses on identifying whether a given English tweet contains a verifiable claim or not.

## Dataset
- English COVID-19 tweets
- Binary classification:
  - Claim (1)
  - Not Claim (0)

## Model Used
- BERT (bert-base-uncased)

## Methodology
1. Data preprocessing
   - Removed URLs
   - Removed mentions and hashtags
   - Cleaned tweet text
2. Tokenization using BERT tokenizer
3. Fine-tuning BERT for sequence classification
4. Model evaluation on test data

## Technologies
- Python
- Google Colab
- Hugging Face Transformers
- PyTorch

## Learning Outcomes
- Binary text classification
- Transformer fine-tuning
- NLP preprocessing techniques
- Model evaluation
