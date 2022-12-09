# Question and answering on tabular data with hugging face and tapas

This repository contains a simple example of how to use the [tapas](https://github.com/google-research/tapas)
model from hugging face to answer questions on tabular data.

## Requirements
    transformers==4.4.1
    torch==1.13.0+cu116
    torch-scatter -f https://pytorch-geometric.com/whl/torch-1.8.0+cu101.html
    pandas

## Description
The Tapas and Tabular models are a new way to perform question answering on tabular data. The model is based on BERT and uses a new token type to encode tabular structure. The model can be used in two ways: for question answering and for masked language modeling for tabular data. The first one is the focus of this repository.