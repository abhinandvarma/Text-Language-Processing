# Text-Language-Processing
POS Tagging | Sentiment Analysis

##################################################################################
POS Tagging on Code Mixed Languages [x]

Dataset : Bengali/Hindi/Telugu-English sentences from http://www.amitavadas.com/Code-Mixing.html (Course dataset)

CRF model : 
A program to tag Parts Of Speech on code-mixed data. We have extracted n-gram features, neighboring words and language to train a 3 CRF models. Achieved an F1_score of 0.79,0.79,0.71 for Bengali, Hindi and Telugu respectively
##################################################################################
Deep Sentiment Analysis [x]

Dataset : Movie Review data set from https://ai.stanford.edu/~amaas/data/sentiment/aclImdb_v1.tar.g

LSTM model : 
A program to test various architectures on LSTM, I deployed a model with 4 layers, a 128size GRU cell layer, a dropout layer and 2 Dense layers to train the model on 25,000 highly polar movie reviews. Achieved an F1-score of 81.72%
