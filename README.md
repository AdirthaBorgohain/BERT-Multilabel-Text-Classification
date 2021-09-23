# BERT-Text-Classification
A BERT multilabel classification model built on augmented text data on an imbalanced dataset. Backtranslation has been used to artificially balance the classes in the dataset.

## Steps to run:
1. Run data_preparation.ipynb to generate augmented data and save to a CSV file.
2. Run bert_base_en_model.ipynb to train a BERT classifier and save the model weights.
