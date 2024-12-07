# LSTM-based Language Modeling

This project demonstrates the implementation of causal language modeling using LSTM (Long Short-Term Memory) networks. It shows the fundamental steps in building and training a word-level LSTM-based language model, where the model predicts the next word in a sequence based on the previous context.

<p align="center">
  <img src="https://github.com/masoud-ml/LSTM-based_Language_Modeling/blob/main/misc/image.png" style="width:550px; height:400px">
</p>

## Overview

Causal language modeling predicts the next token in a sequence of tokens, and the model can only attend to tokens on the left. This means the model cannot see future tokens. GPT-2 is an example of a causal language model.

## Dataset

This project is based on the WikiText-2 dataset, which consists of a large collection of articles extracted from Wikipedia and features a vocabulary of over 30,000 words. It is specifically designed for language modeling tasks and provides high-quality, diverse text, making it ideal for training and evaluating models in natural language processing applications.

