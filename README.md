# TinyGPT Text Generator

This project is a character-level TinyGPT text generation model built with PyTorch.

The model is trained on an English text file and learns to predict the next character from previous context. After training, it can generate new text that follows a similar style to the training data.

## Project Overview

This project uses a small GPT-like Transformer model.

The model includes:

- Character-level tokenization
- Token embeddings
- Positional embeddings
- Masked multi-head self-attention
- Feedforward layers
- Residual connections
- Layer normalization
- Transformer blocks
- Next-character prediction

## How It Works

1. Load an English text file.
2. Convert each character into a numerical token.
3. Create input and target sequences.
4. Train a TinyGPT model to predict the next character.
5. Generate new text from a user-provided prompt.

## How to Run

1. Open `TinyGPT_Text_Generator.ipynb` in Google Colab.
2. Upload an English `.txt` file.
3. Run all cells.
4. Train the model.
5. Enter a prompt and generate text.

## Example Prompt

```text
ROMEO:
