
# Task 1: News Topic Classifier Using BERT

## Objective
Fine-tune a BERT transformer model to classify news headlines into four categories:
World, Sports, Business, and Sci/Tech.

## Dataset
AG News Dataset (Hugging Face Datasets)
- 120,000 training samples
- 7,600 testing samples

## Methodology
- Tokenized text using bert-base-uncased tokenizer
- Fine-tuned BERT for sequence classification
- Used a subset of dataset for faster training
- Evaluated performance using Accuracy and Macro F1-score
- Deployed the model using Gradio for live interaction

## Results
The model achieved strong classification performance using transfer learning.
Fine-tuning BERT significantly improves accuracy compared to traditional ML models.

## Conclusion
This task demonstrates end-to-end NLP workflow including:
- Transformer fine-tuning
- Model evaluation
- Real-time deployment
