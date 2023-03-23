1.sentiment-Analysis:

One of the key areas where NLP has been predominantly used is sentiment analysis. The understanding of customer behaviour and needs on a comany's products and services is vital for organizations. Generally, the feedback provided by a customer on a product can be categorized into positive, negative and neutral. interpreting customer feedback through product reviews helps companies evaluate how satisfied the customers are with their products/services.

2.RoBERTa:

RoBERTa is a reimplementation of a BERT with some notifications to the key hyperparameters and minor embedding tweaks. it uses a byte-level BPE as a tokenizer and a different pretraining scheme.

RoBERTa is trained for longer sequences,too,i.e the number of iterations is increased from 100k to 300k and the further 500k.

RoBERTa uses larger byte-level BPe vocabulary with 50k subword units instead of cahracter-level BPE vocabulary of size 30k used in BERT.

In the masked language model (MLM) training objective, RoBERTa employs dynamic masking to generate the masking pattern every time a sequence is fed to the model.


