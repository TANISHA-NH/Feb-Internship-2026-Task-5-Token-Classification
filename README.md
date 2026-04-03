# NLP Task 5 – Token Classification (POS Tagging & Chunking)

This project implements token classification using a transformer model (DistilBERT) to perform sequence labeling tasks similar to POS tagging and chunking.

## Dataset

WNUT-17 dataset is used for training and evaluation.

## Approach

* Tokenization with label alignment
* Fine-tuning DistilBERT using Hugging Face Trainer
* Evaluation using Precision, Recall, and F1 Score

## Result

The model successfully learns token-level predictions and demonstrates effective sequence labeling performance.

## Tech Stack

Python, Transformers, PyTorch, Hugging Face, SeqEval
