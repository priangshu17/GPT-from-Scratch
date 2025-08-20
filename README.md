# GPT-from-Scratch

# GPT Language Model from Scratch

This repository contains a Jupyter Notebook that builds a simple, character-level Generative Pre-trained Transformer (GPT) from scratch using PyTorch. The code is written for educational purposes to demystify the core components of the Transformer architecture, particularly the self-attention mechanism.

## ✨ Acknowledgement

This project is a personal implementation that closely follows the phenomenal "Let's build GPT: from scratch, in code, spelled out." tutorial by **Andrej Karpathy**. Full credit and thanks go to him for creating such an intuitive and insightful guide.

You can watch the original tutorial here:
**[Andrej Karpathy - Let's build GPT on YouTube](https://www.youtube.com/watch?v=kCc8FmEb1nY)**

## 📝 Project Overview

The goal of this notebook is to construct a simple language model that can generate text one character at a time, in the style of Shakespeare. It starts with a basic bigram model and progressively builds up to the self-attention mechanism that powers modern models like GPT.

### Key Concepts Covered:
* **Character-level Tokenization**: Creating a vocabulary and mapping characters to integers.
* **Data Batching for Language Models**: Preparing context blocks (x) and targets (y) for training.
* **Bigram Model**: A simple baseline to understand the task of next-token prediction.
* **Self-Attention**: A step-by-step breakdown of the self-attention mechanism, including:
    * Aggregating past information using weighted averages.
    * Implementing causal (masked) self-attention with queries, keys, and values.
* **Text Generation**: A `generate` method to sample new text from the trained model.

## 📚 Dataset

The model is trained on the **Tiny Shakespeare** dataset, which contains a collection of Shakespeare's works concatenated into a single text file.











 
