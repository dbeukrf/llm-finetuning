## LLM Fine-Tuning – Google Colab Notebooks

A collection of Python notebooks designed for experimenting with fine-tuning Large Language Models (LLMs) using Google Colab.
These notebooks focus on practical, hands-on workflows for data preparation, training, evaluation, and inference using modern open-source LLM tooling.

# Overview

This repository contains a set of Google Colab notebooks that walk through:

Preparing and cleaning datasets for LLM fine-tuning
- Tokenisation and prompt formatting
- Fine-tuning transformer-based models
- Evaluating model performance
- Running inference on fine-tuned models

The notebooks are modular and intended to be used independently or as a complete pipeline.

# Features

- **Colab-ready:** Designed to run on free or Pro Google Colab environments
- **GPU support:** Automatic GPU detection and configuration
- **Hugging Face ecosystem:** Uses transformers, datasets, and accelerate
- **Reproducible workflows:** Clear step-by-step cells with explanations
- **Customisable:** Easy to swap models, datasets, and training parameters

# Example Use Cases

- Fine-tuning open-source LLMs for domain-specific tasks
- Prompt-based instruction tuning
- Experimenting with parameter-efficient fine-tuning (e.g. LoRA)
- Learning the end-to-end LLM fine-tuning pipeline

# Notebook Structure

Typical notebooks include:
**1. Environment Setup**
  - Install dependencies
  - Mount Google Drive (optional)
**2. Data Preparation**
  - Load and preprocess datasets
  - Format prompts and labels
**3. Model Setup**
  - Load pretrained models and tokenisers
  - Configure training arguments
**4. Fine-Tuning**
  - Train the model
  - Monitor loss and checkpoints
**5. Evaluation & Inference**
  - Run sample prompts
  - Compare outputs before and after fine-tuning

# Requirements

- Google Colab (Python 3)
- GPU runtime recommended (T4 / A100 if available)
- Hugging Face account (for model downloads and uploads)

Common libraries used:
- transformers
- datasets
- torch
- peft
- accelerate

# How to Use

1. Open a notebook in Google Colab
2. Set the runtime to GPU
3. Run cells sequentially
4. Adjust model names, datasets, and hyperparameters as needed
5. Save fine-tuned models to Google Drive or Hugging Face Hub

# Notes

These notebooks are intended for educational and experimental purposes

Fine-tuning large models may exceed free Colab limits

Results may vary depending on dataset size and GPU availability

# Future Improvements

Additional notebooks for evaluation metrics

Support for more PEFT techniques

Multi-GPU / distributed training examples

Experiment tracking integrations (e.g. Weights & Biases)

# License

This project is released under the MIT License.
