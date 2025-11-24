# A Comparative Evaluation of Parameter-Efficient Fine-Tuning Techniques for Large Language Models

This repository contains the code, experiments, and report for the project:

**“A Comparative Evaluation of Parameter-Efficient Fine-Tuning Techniques for Large Language Models.”**

The goal of this work is to compare different fine-tuning strategies for adapting large pretrained language models to downstream tasks while reducing computational cost. We focus on:

- **Full Fine-Tuning**
- **LoRA (Low-Rank Adaptation)**
- **Prefix-Tuning**

Experiments are conducted on two representative NLP tasks:
- **AG News** – Topic Classification (RoBERTa-base)
- **CommonGen** – Generative Commonsense Reasoning (BART-base)

---

## 🚀 Project Overview

Modern LLMs require significant compute and memory to fine-tune.
Parameter-Efficient Fine-Tuning (PEFT) methods address this by updating only a *small subset* of model parameters.

This project:
- Implements Full FT, LoRA, and Prefix-Tuning
- Runs experiments on classification and generation tasks
- Tracks trainable parameters, memory usage, training time, and performance
- Produces learning-curve plots for each method
- Generates a detailed research-style PDF report (arXiv format)

---

## 📊 Experimental Results

We evaluate three fine-tuning methods on two datasets.
Metrics recorded:

- Accuracy (AG News)
- BLEU-4 (CommonGen)
- Trainable parameters
- GPU memory usage
- Total training time
- Validation curve progression (plots)

All generated results are stored as JSON files under `results/Jsons/`.

Plots of each learning curve are stored in `results/Plots/`.

---



