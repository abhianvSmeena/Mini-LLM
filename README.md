# Custom Mini GPT-2 Language Model

This project demonstrates how to fine-tune a small GPT-2 language model using Hugging Face's `transformers` library and PyTorch. It provides a hands-on introduction to the complete workflow of building a basic language model: from preprocessing and training to text generation.

## Project Overview

- Fine-tunes a pre-trained GPT-2 (`GPT2LMHeadModel`) on a custom dataset.
- Implements a training loop using PyTorch and the AdamW optimizer.
- Visualizes training loss to monitor performance.
- Generates text based on user-defined prompts after training.

## Files

- `Custom_mini_LLM.ipynb`: Main notebook containing code, training logic, and outputs.
- (Optional) `requirements.txt`: List of dependencies for setup.

## Setup Instructions

1. Clone the repository:

```bash
git clone https://github.com/abhianvSmeena/Mini-LLM.git
cd Mini-LLM
