# DNA Sequence Classification using NLP Techniques

This repository contains a Colab notebook that demonstrates the application of natural language processing (NLP) techniques to classify DNA sequences into different taxonomic groups. The notebook can found on Colab [here](https://colab.research.google.com/drive/1mIg1L_7voRTsU6nUCT1YVizyh5sVCF5I?usp=sharing). It explores two approaches:

1. Multinomial Naive Bayes Classifier: This simple approach predicts the taxonomic group based on the presence and frequency of k-mers in the input sequence.
2. Fine-tuned Transformer Model: The notebook leverages a pre-trained transformer model from InstaDeep, which has been trained on a set of 850 genomes across various phyla.
