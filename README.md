Fine-Tune a Model: Description: Load a pre-trained LSTM-based NMT model and use it to translate a sentence from one language to another. Description: GUI is not necessary.
Brief Introduction: Neural machine translation (NMT) uses Deep learning (DL) to translate text from one language to another. It is a powerful state-of-art language translation. In this task, a LSTM-based NMT model is built to translate the text from one to another language. Data Source: 'Tab-delimited Bilingual Sentence Pairs' (English to French)

The steps it includes :
1.Load Data
2.Data Preprocessing
3.Evaluating the maximum length of both English and French phrases.
4.Fitting Tokenizer to the phrases and generating padded sequences
5.Determining vocabulary length
6.Adding layers
7.Training of the model
8.Training and Validation Accuracy Plot
9.Validating the model
10.Test the model: Translation from English to French
