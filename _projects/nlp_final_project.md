---
layout: default
title: NLP Final Project
excerpt: GPT-2 pipeline for generating structured biographies with retrieval-augmented memory.
---

# NLP Final Project

This project demonstrates a **pipeline for generating structured biographies** using **GPT-2** with retrieval-augmented memory.  
It combines language modeling, classification, and memory retrieval to produce accurate and context-aware biographical text.

## Tech Stack
- Python
- PyTorch
- HuggingFace Transformers
- Key-Value Memory Networks
- GPT-2

## Description
The pipeline works as follows:

1. **Text Generation:** GPT-2 generates an initial biography draft.  
2. **Retrieval Trigger Classification:** A classifier predicts when GPT-2 needs to access additional knowledge.  
3. **Memory Retrieval:** Relevant information is fetched from a trained key-value memory network.  
4. **Integration:** Retrieved facts are incorporated back into the generation, producing coherent and factually enriched biographies.  

This approach demonstrates how language models can be augmented with external memory to improve factual accuracy and structure in generated content.

## GitHub Repository
[View on GitHub](https://github.com/robson31/nlp-bio-generator)
