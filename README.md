# Do Language Models Encode Semantic Relations? Probing and Sparse Feature Analysis

Code repository for the paper:

> **Do Language Models Encode Semantic Relations? Probing and Sparse Feature Analysis**
> Andor Diera, Ansgar Scherp — Ulm University
> *Accepted at LREC 2026*

## Overview

This repository provides code and data for investigating how large language models encode four semantic relations — synonymy, antonymy, hypernymy, and hyponymy — using linear probing, sparse autoencoders (SAEs), and activation patching. We study three models of increasing scale: Pythia-70M, GPT-2-124M, and Llama 3.1 8B.

## Repository Structure

```
├── dataset/                 # Pre-built datasets
├── dataset_creation.ipynb   # Dataset construction from WordNet
```
## Requirements

For dataset creation only:

- Python ≥ 3.9
- `nltk`
- `pandas`
- `scikit-learn`

For the full pipeline (probing + SAE analysis — code coming soon):

- `torch`
- `transformers`
- `sae-lens`

