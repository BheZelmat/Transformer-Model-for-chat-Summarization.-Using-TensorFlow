# Transformer-Model-for-chat-Summarization-Using-TensorFlow





![alt text](https://github.com/BheZelmat/Transformer-Model-for-chat-Summarization.-Using-TensorFlow/blob/main/Img.png?raw=true)



This repository contains a TensorFlow implementation of a Transformer model designed for the task of chat summarization. The goal of this project is to create a system that can automatically generate concise summaries from chat dialogues, which can be particularly useful for quickly understanding the context and content of conversations.

## Features

* Full implementation of a Transformer model, including both encoder and decoder components.
* Utilization of DotProductAttention and Causal Attention mechanisms to understand the importance of different words within the chat context.
* A step-by-step guide on preprocessing chat data, implementing the Transformer model, and evaluating its performance.
* Use of TensorFlow for building and training the model, demonstrating the framework's capabilities in handling sequence-to-sequence tasks.

## Dataset
* The dataset used in this project consists of chat dialogues and their corresponding summaries. The preprocessing steps include tokenization, adding special tokens for start and end of sentences, and padding/truncating sequences to uniform lengths.

## Model Architecture

The Transformer model implemented follows the original architecture proposed by Vaswani et al., consisting of multiple encoder and decoder layers, multi-head attention mechanisms, and position-wise fully connected feed-forward networks.

## Requirements
* Python 3.x
* TensorFlow 2.x
* NumPy
* Pandas
* Matplotlib

## Usage
The document includes code snippets and explanations for each step of the system development. You can replicate the process, train the model with the provided dataset, and test its organization capabilities on new data.

## Author
Houssem Zelmat 
