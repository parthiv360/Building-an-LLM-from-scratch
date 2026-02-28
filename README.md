# GPT-2 From Scratch

This repository contains a complete, ground-up implementation of the GPT-2 Large Language Model (LLM) architecture using PyTorch. The goal of this project is to demystify the inner workings of Transformer-based models by building the core components—from self-attention mechanisms to the final text generation loop—without relying on high-level abstraction libraries like Hugging Face `transformers` for the core architecture.



## 🚀 Overview

Understanding how Large Language Models work under the hood is crucial for modern AI research and engineering. This notebook (`GPT2 from Scratch.ipynb`) walks through the entire lifecycle of an LLM:
* Implementing the Token embedding and Positional encoding layers.
* Building the core Causal Self-Attention mechanism.
* Assembling Transformer Decoder blocks.
* Creating the training loop and handling data loading.
* Generating text recursively using the trained weights.

## 📂 Repository Structure

```text
├── GPT2 from Scratch.ipynb   # Main Jupyter Notebook containing the full implementation
└── README.md                 # Project documentation

```

## 🧠 Key Features Implemented
* Byte Pair Encoding Algorithm and Different Positional Encoding
* Different Attention Mechanisms like **Mutli Head Attention** and **Grouped Query Attention**
* Different Decoding Techniques.
