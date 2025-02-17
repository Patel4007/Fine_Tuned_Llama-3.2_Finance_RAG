## Fine-Tuned Llama 3.2 for Finance RAG

This project demonstrates the fine-tuning of Meta's Llama 3.2 model for financial domain-specific tasks using Retrieval-Augmented Generation (RAG) techniques. The goal is to enhance the model's ability to provide accurate and contextually relevant answers to finance-related queries by integrating external knowledge sources.

## Project Overview

The repository includes a Jupyter Notebook, Finance_RAG_Pipeline.ipynb, which outlines the complete pipeline for fine-tuning the Llama 3.2 model in the financial domain. The notebook covers:

**Data Preparation**: Loading and preprocessing financial datasets.

**Model Fine-Tuning**: Applying Low-Rank Adaptation (LoRA) techniques for efficient fine-tuning.

**Retrieval-Augmented Generation**: Integrating external financial data to improve response accuracy.

**Evaluation**: Assessing the models performance on finance-specific tasks.

## Prerequisites

- Python 3.8 or higher
- Pytorch
- Transformers 4.47.x
- Huggingface datasets library
- PEFT (Parameter Efficient Fine Tuning) library
- TRL (Transformer Reinforcement Learning) library

## Installation

Clone the repository:

```bash
git clone https://github.com/Patel4007/Fine_Tuned_Llama-3.2_Finance_RAG.git
```

Navigate to the repository and open the notebook:

```bash
cd Fine_Tuned_Llama-3.2_Finance_RAG
jupyter notebook Finance_RAG_Pipeline.ipynb
```

## License

This project is licensed under the MIT License.

