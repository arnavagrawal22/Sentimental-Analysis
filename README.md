# Sentimental Analysis IMDB
## Description
Classification of sentences depending on polarity- Positive or Negative achieved using training on the IMDB Dataset

*Concepts*
1. RNN
2. LSTM
3. Word Embeddings
4. Multilayer and Bi-Directional RNNs

**RESULTS**


Trained for 5 epochs on Kaggle.

Test Accuracy of ~90%

### Dataset

[IMDB](https://torchtext.readthedocs.io/en/latest/datasets.html)

### Code Structure 

[Simple-RNN](./simple_rnn.ipynb) : Used simple one layer RNN with no pretrained embeddings.

[Improved-RNN](./improved-rnn-sentimental-analysis.ipynb) : Used LSTM along with glove-6b embeddings, with a 2 layered bi-directional RNN.


## This project in PyTorch
### Requirements:
- PyTorch
- Torchtext (Used ```torchtext.legacy```)
- Spacy

### Usage

- You can pretrain the model
- You can use the predict sentiment to try your own sentences

### Acknowledgements 

Thanks to the author of  [this](https://github.com/bentrevett/pytorch-sentiment-analysis) for this amazing repo and its explanation and help.




