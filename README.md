# Disaster-Tweets-BERT
Analyzing Tweets using BERT, RoBERTa, and Feed-forward Neural Networks

This notebook is submitted on Kaggle under the competition "NLP Disaster Tweets". Check out my submission here:
https://www.kaggle.com/code/kaileighstopa/nlp-disaster-tweets

The dataset of Disaster Tweets comprises several thousand tweets that have been manually categorized by humans as either being relevant to an actual disaster or not having anything to do with a disaster. For example, someone may colloquially use the word "fire" to describe a song, while other tweets containing the word "fire" may actually be describing a real fire.

In this notebook, I will be building NLP classification models to predict whether tweets in the test dataset are actual disasters or just false alarms. The models will rely mostly on BERT and RoBERTa, two powerful NLP models created by researchers at Google AI Language and at Facebook AI, respectively. I will also be comparing the performance of BERT and RoBERTa against a simple Feed-forward Neural Network (FNN) with metadata features that will be extracted from the text.

To build my models, I will be using the transformers library from HuggingFace with PyTorch. The transformers library from HuggingFace is a widely used open-source library for working with transformer-based models such as BERT, GPT-2, and RoBERTa. It provides a comprehensive set of pre-trained models as well as tools for pre-processing, fine-tuning, and evaluation, making it easy to implement and experiment with these NLP models.
