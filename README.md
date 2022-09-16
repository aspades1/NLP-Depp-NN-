# NLP-Depp-NN-Sentiment-Analysis
8 hour Datathlon, part of BigBlue bootcamp.

# Game Reviews Sentiment NLP Analysis
The Datathlon from Big Blue Data Academy where we had 8 hours to perform sentiment analysis on game reviews using ML and DL techniques.

We tried various preprocessing techniques: stopwords removal, pos tagging, regex cleaning and applied different LSTM Neural network architectures. Finally, the highest accuracy we got from tranfer learning using tensorflow's [nnlm-en-dim50](https://tfhub.dev/google/nnlm-en-dim50/1) model which we retrained with our cleaned dataset. 

We found that stop-word removal and POS cleaning did not have any effect on accuracy which by the end of datathlon was at 88%.

Furthermore, we performed spell and profanity checking, emojies and emoticon analysis and finally delivered the classifier in a command-line-based UI that performed tha classification on unseen test data and delivered the results.
