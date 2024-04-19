# AI Text Generation with Llama-3

This Jupyter notebook demonstrates how to set up and use the Llama-3 model for AI text generation on a MacBook. The model is loaded from the `mlx-community/Meta-Llama-3-8B-Instruct-4bit` repository.

## Setup

The environment is set up using conda and pip. The required packages include `mlx`, and `mlx_lm`.

## Model Loading

The Llama-3 model and its tokenizer are loaded using the `load` function from the `mlx_lm` package. The tokenizer is configured with the correct end-of-text (EOT) token.

## Text Generation

Text is generated using the `generate` function from the `mlx_lm` package. The function takes a prompt, which is formatted using the `apply_chat_template` method of the tokenizer. The generated text is then printed.

## Example

The notebook includes an example where the AI is asked to answer the question: "Which is heavier a kilo of feathers or 2.49 pounds of stone?" The AI provides a detailed response.

- This document is AI generated and might not be correct
- Original work: https://freshprinceofstandarderror.com/ai/how-to-set-up-and-use-llama-3-on-your-macbook/